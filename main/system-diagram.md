# System Diagram

```mermaid
flowchart LR
    UserService[User Service]
    APIGateway[API Gateway]
    Database[Database]

    UserService --> APIGateway
    APIGateway --> Database