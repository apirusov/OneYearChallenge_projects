# Basic Concepts

```mermaid
flowchart LR
    Client[Client Request] --> apiGateway{API Gateway}
    
    apiGateway --> orderSvc[Order Service]
    apiGateway --> paymentSvc[Payment Service]
    apiGateway --> inventorySvc[Inventory Service]
    
    orderSvc <--> paymentSvc
    paymentSvc <--> inventorySvc
    
    orderSvc <--> ordersDB[(Orders DB)]
    paymentSvc <--> paymentsDB[(Payments DB)]
    inventorySvc <--> inventoryDB[(Inventory DB)]
