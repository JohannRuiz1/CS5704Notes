### Different ways to show attributes of a class
![[AttributesUML.png]]

### Class Diagram Essentials
![[ClassDiagramEssentials.png]]

### Sequence Diagram
![[SequenceDiagramCentralized.png]]
Centralized Control: The Order objects calls other classes to get information and does the work
![[SequenceDiagramDistributed.png]]
Distributed Control: The Order object delegates work to other classes

### Aggregation and Composition
Both are has-a relationship (More specific association)
![[AggregationComposition.png]]
 Aggregation: part-of relationship, if the container is destroyed, the components are not destroyed. If the club stops existing, the people in the club still exist

Composition: Properties are owned by value; if you delete the polygon, the points should also be destroyed since the points made up the polygon, they don't belong to other polygons

### Interfaces and Abstract Classes

![[InterfaceAbstractUML.png]]
Abstract: Classes and methods are *italics* or <u>underlined</u>
Interfaces are just defined with <<>>
Dependency: is the most general, and can be thought as if the class needs to import the class
Implementation: AbstractList **implements** List
Generalized Arrow (list to collection): List **extends** Collection

### Deployment Diagrams
Def: Shows a system's physical layout, revealing which pieces of software are running on what softwares