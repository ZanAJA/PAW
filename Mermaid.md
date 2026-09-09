## Diagram Trust Boundary

```mermaid
flowchart LR
    U[User Browser] --> F[Frontend Angular]
    F --> A[REST API Express]
    A --> D[(SQLite Database)]
```
