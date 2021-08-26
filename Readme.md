# Hola
### Este repositorio se actualizara a medida que realice el curso de Python, y
### Python con redes neuronales.
## Muchas gracias. 

![Class Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Zingam/Markdown-Document-UML-Use-Test/master/UML/Instance.puml)

@startuml
map "Map **Contry => CapitalCity**" as CC {
 UK => London
 USA => Washington
 Germany => Berlin
}
@enduml


```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D

graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    
    graph LR
    id1(This is the text in the box)
