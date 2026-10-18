# Basic Questions to ask before building Microservice

```mermaid
graph LR
    subgraph ClientLayer [Client & Gateway]
        Client[fa:fa-laptop Client Request] --> apiGateway{fa:fa-network-wired API Gateway}
    end

    subgraph Services [Microservices]
        direction TD
        orderSvc[fa:fa-cart-shopping Order Service]
        paymentSvc[fa:fa-credit-card Payment Service]
        inventorySvc[fa:fa-cubes Inventory Service]
    end

    subgraph Databases [Databases]
        direction TD
        ordersDB[(fa:fa-database Orders DB)]
        paymentsDB[(fa:fa-database Payments DB)]
        inventoryDB[(fa:fa-database Inventory DB)]
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
    ecApp[E-commerce Application] --> usrSrc[User Service]
    ecApp[E-commerce Application] --> ordSrc[Order Service]
    ecApp[E-commerce Application] --> paySrc[Payment Service]
```
