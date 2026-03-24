```mermaid
---
title: Architecture
---

graph TD
    
subgraph Client 
    client_app[Web App]
end

subgraph Serving Layer 
    api[API Service - <a href='main.go'>main.go</a>]
end

```