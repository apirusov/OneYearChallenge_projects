# Basic Questions to ask before building Microservice

```mermaid
graph LR
    subgraph ClientLayer [Client & Gateway]
        Client["💻 Client Request"] --> apiGateway{"🌐 API Gateway"}
    end

    subgraph Services [Microservices]
        direction TD
        orderSvc["🛒 Order Service"]
        paymentSvc["💳 Payment Service"]
        inventorySvc["📦 Inventory Service"]
    end

    subgraph Databases [Databases]
        direction TD
        ordersDB[("🗄️ Orders DB")]
        paymentsDB[("🗄️ Payments DB")]
        inventoryDB[("🗄️ Inventory DB")]
    end

    %% Connections from Gateway to Services
    apiGateway --> orderSvc
    apiGateway --> paymentSvc
    apiGateway --> inventorySvc

    %% Service-to-Database mapping
    orderSvc <--> ordersDB
    paymentSvc <--> paymentsDB
    inventorySvc <--> inventoryDB
```

## Microservices Architecture Fundamentals

### 1. Monolith vs Microservices

Understand the architectural trade-offs

```mermaid
graph LR
subgraph monvsmcrsc[Monolith vs Microservices]
direction LR
    subgraph Monolith[Monolith Application]
        direction TD
        subgraph ui[UI]
        direction TD
            businessLogic[Business Logic]
            dataAccess[Data Access]
        end
        
        ui --> singleDb[(Single DB)]
    end

    subgraph microservices[Microservices]
        direction LR
        
        subgraph user[User Domain]
            direction TD
            userSvc[User Service] --> userDb[(DB)]
        end

        subgraph order[Order Domain]
            direction TD
            orderSvc[Order Service] --> orderDb[(DB)]
        end

        subgraph payment[Payment Domain]
            direction TD
            paymentSvc[Payment Service] --> paymentDb[(DB)]
        end
    end 
end
```

### 2. Service Boundaries

How do you decide what belongs to each service?

```mermaid
graph LR
    ecApp[E-commerce Application] --> usrSrc["👤User Service<br>(Users, Profiles)"]
    ecApp[E-commerce Application] --> ordSrc["🛒Order Servicee<br>(Orders, Cart)"]
    ecApp[E-commerce Application] --> paySrc["💳Payment Servicee<br>(Payments, Refunds)"]
```

### 3. Loose Coupling

How do you minimize dependencies between services?

```mermaid
graph LR
    srca[Service A] <-.->|Minimal dependency| srcb[Service B]
```

### 4. High Cohesion

Why should each service focus on a closely related set of responsibilities?

```mermaid
graph LR
    invSrc[("📦 Inventory Service")] --> mngInv[Manage inventory]
    invSrc[("📦 Inventory Service")] --> updSt[Update Stock]
    invSrc[("📦 Inventory Service")] --> trStMov[Track stock movements]
    invSrc[("📦 Inventory Service")] --> relBusLog[Related Business Logic]
```

### 5. Database per Service

Why would each service own its data?

```mermaid
graph TD
    subgraph user[User Domain]
            direction TD
            userSvc[User Service] --> userDb[(DB)]
        end

        subgraph order[Order Domain]
            direction TD
            orderSvc[Order Service] --> orderDb[(DB)]
        end

        subgraph payment[Payment Domain]
            direction TD
            paymentSvc[Payment Service] --> paymentDb[(DB)]
        end
```

### 6. Independent Deployment & Scaling

Can you deploy and  scale one service without affecting the others?

```mermaid
    graph TD
    subgraph user[User Domain]
            direction TD
            userSvc[User Service] --> userblock
        end

        subgraph order[Order Domain]
            direction TD
            orderSvc[Order Service] --> orderblock
        end

        subgraph payment[Payment Domain]
            direction TD
            paymentSvc[Payment Service] --> paymentblock
        end
```
