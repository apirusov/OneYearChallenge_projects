# Basic Questions to ask before building Microservice

```mermaid
graph LR
    subgraph ClientLayer [Client & Gateway]
        Client[Client Request] --> apiGateway{API Gateway}
    end

    subgraph Services [Microservices]
        direction TD
        orderSvc[Order Service]
        paymentSvc[Payment Service]
        inventorySvc[Inventory Service]
    end

    subgraph Databases [Databases]
        direction TD
        ordersDB[(Orders DB)]
        paymentsDB[(Payments DB)]
        inventoryDB[(Inventory DB)]
    end

    %% Connections from Gateway to Services
    apiGateway --> orderSvc
    apiGateway --> paymentSvc
    apiGateway --> inventorySvc

    %% Service-to-Database mapping
    orderSvc <--> ordersDB
    paymentSvc <--> paymentsDB
    inventorySvc <--> inventoryDB
end 

## Microservices Architecture Fundamentals

### Monolith vs Microservices

Understand the architectural trade-offs

```mermaid
graph LR
    subgraph Monolith[Monolith]
        direction TD
        subgraph ui[UI]
            businesslogic[Business Logic]
            dataAccess[Data Access]
        end
        singleDb[Single DB]
    end

    subgraph microservices[Microservices]
        direction LR
        subgraph user
            direction TD
                userSvc[User Service]
                userDb[DB]
        end

        subgraph order
            direction TD
                orderSvc[Order Service]
                orderDb[DB]
        end

        subgraph payment
            direction TD
                paymentSvc[Payment Service]
                paymentDb[DB]
        end
    
    ui --> singleDb
    userSvc --> userDb
    orderSvc --> orderDb
    paymentSvc --> paymentDb

end
