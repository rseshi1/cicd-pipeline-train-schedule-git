# Data Flow

> _Auto-generated DeepWiki. Derived from static analysis of the repository at the referenced commit. Verify against source before relying on operational details._

```mermaid
graph LR
    In["Input / request"]
    In --> N0["views"]
    N0 --> N1["routes"]
    N1 --> N2["public"]
    N2 --> N3["data"]
    N3 --> N4["bin"]
    N4 --> Out["Output / response"]
```
