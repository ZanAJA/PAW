```mermaid
flowchart LR

    subgraph CLIENT["Client Side - Untrusted"]
        U[User Browser]
        F[Frontend Angular]
        U --> F
    end

    subgraph SERVER["Server Side - Trusted"]
        A[REST API Express]
    end

    subgraph DATA["Data Layer"]
        D[(SQLite Database)]
    end

    F --> A
    A --> D

    style CLIENT fill:none,stroke-width:2px
    style SERVER fill:none,stroke-width:2px
    style DATA fill:none,stroke-width:2px
```
