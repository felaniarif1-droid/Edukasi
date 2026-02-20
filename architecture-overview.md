```mermaid
graph LR
    A[User] -->|Uses| B(Frontend)
    B -->|API Call| C(Backend)
    C -->|Database Query| D[(Database)]
    C -->|Fetches Data| E[Cache]
```