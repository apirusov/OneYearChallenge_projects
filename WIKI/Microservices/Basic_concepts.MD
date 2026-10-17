# Basic Concepts

```mermaid
graph LR
    subgraph ClientLayer [Client & Gateway]
        Client[Client Request] --> apiGateway{API Gateway}
    end

    subgraph Services [Microservices Column]
        direction TD
        orderSvc[Order Service]
        paymentSvc[Payment Service]
        inventorySvc[Inventory Service]
    end

    subgraph Databases [Databases Column]
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


