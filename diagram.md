# Simple UML Diagram

```mermaid
classDiagram
  class Animal {
    +String name
    +speak()
  }
  class Dog {
    +bark()
  }
  Animal <|-- Dog
```
