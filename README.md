# DevOps Books

> [Mermaid Diagram Documentation](https://mermaid.ai/open-source/intro/getting-started.html)

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    A-->D;
```




```mermaid
  info
```


```mermaid
---
config:
  look: handDrawn
  theme: neutral
---
flowchart LR
  A[Start] --> B{Decision}
  B -->|Yes| C[Continue]
  B -->|No| D[Stop]
```




```mermaid
---
config:
  architecture:
    idealEdgeLengthMultiplier: 3
---
architecture-beta
    service a(server)[A]
    service b(server)[B]
    service c(server)[C]
    a:R --> L:b
    b:R --> L:c
```