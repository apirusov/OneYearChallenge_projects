# Basic Concepts

```mermaid
Microservices 
Client[Unsorted Array] -> API Gateway{divided by three}
API Gateway -> Order Service[Top Sub-array]
API Gateway -> Payment Service[Middle Sub-array]
API Gateway -> Inventory Service[Bottom Sub-array]
Order Service -> Payment Service[Recursively Sort]
Payment Service -> Order Service[Recursively Sort]
Payment Service -> Inventory Service[Recursively Sort]
Inventory Service -> Payment Service[Recursively Sort]
Order Service -> Orders DB[Recursively Sort]
Orders DB -> Order Service[Recursively Sort]
Payment Service -> Payments DB[Recursively Sort]
Payments DB -> Payment Service[Recursively Sort]
Inventory Service -> Inventory DB[Recursively Sort]
Inventory DB -> Inventory Service[Recursively Sort]