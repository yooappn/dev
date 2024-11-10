

```mermaid
graph TD
    A(start)-->B{true?}
    B--Yes-->C[process]
    B--No-->D[exception]
    C-->E(end)
    D-->E
```
