# OOAD-WEEK09 Homework
##Usecase Diagram

###Usecase diagram1
code
```

@startuml
Person *-- heart
Person *-- hand
City o-- building
City o-- car

@enduml
```
diagram
<img src = "https://github.com/primmyybaa/OOAD-WEEK09/blob/master/Homework/class6.png?raw=true">

###2
code
```
@startuml
scale 750 width
 package 1 <<Node>>{ 
 class Mobilephone 
 }
package 2 <<Rect>> {
class car
}
package 3 <<Folder>> {
class House
}
package 4 <<frame>>{
class humen
}
package 5 <<cloud>>{
class computer
}
package 6 <<database>>{
class book 
}
@enduml


```
diagram
<img src ="https://github.com/primmyybaa/OOAD-WEEK09/blob/master/Homework/class7.png?raw=true">

###3
 ```
 @startuml
class humen {
+ getName()
+ getAddress()

__
+ eat 
+ talk
--
End of class
}
class car {
+ color
+ type 
+ engine
- blueprint
__
+Drive
--
End of class
}
@enduml

```
diagram
<img src ="https://github.com/primmyybaa/OOAD-WEEK09/blob/master/Homework/class8.png?raw=true">

###4
```
@startuml
papayapokpok  -left--> papaya 
papayapokpok  -right--> chilli 
papayapokpok  -up--> pickled fish
papayapokpok  -down--> lentils
@enduml

```
diagram
<img src ="https://github.com/primmyybaa/OOAD-WEEK09/blob/master/Homework/class9.png?raw=true">

###5
```
@startuml
skinparam class {
BackgroundColor Pale
ArrowColor black
BorderColor yellow
}
skinparam stereotypeCBackgroundColor pink
papayapokpok "0..*" -- "1..*" papaya
papayapokpok  "0..*" -- "1..*" chilli 
papayapokpok  "0..*" -- "1..*" pickledfish
papayapokpok  "0..*" -- "1..*" lentils
@enduml
```
diagram
<img src ="https://github.com/primmyybaa/OOAD-WEEK09/blob/master/Homework/class10.png?raw=true">
