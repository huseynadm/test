graph TD
    A[develop] -->|Create Branch| B{Branch Naming}
    B -->|dev/*| C[DEV/akart]
    B -->|feat/*| D[uat/akart]
    B -->|release/*| E[prod/akart]
    
    C --> F[DEV Environment]
    D --> G[UAT Environment]
    E --> H[PROD Environment]
    
    style A fill:#f9f,stroke:#333
    style B fill:#bbf,stroke:#333
    style C fill:#9f9,stroke:#333
    style D fill:#ff9,stroke:#333
    style E fill:#f99,stroke:#333
