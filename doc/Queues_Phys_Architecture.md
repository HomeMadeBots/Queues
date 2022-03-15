# Queues architecture

The physical architecture is designed following
[this meta-model](https://github.com/HomeMadeBots/Embedded_Software_Meta_Model).

## Abstract class **Queue**

The queues are designed based on an abstract class **Queue** able to process any
type of data.  
The data are physically stored in an array named **Container**.  
The class **Queue** defines 2 virtuals methods _Add_To_Container_ and
_Remove_From_Container_ allowing to add or remove item to or from the array.  

![physical architecture](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Physical_Architecture.puml)

## Actual queue example : **Uint8_Queue**

Actual queues shall be derived from **Queues** and realize the 2 virtual methods
allowing to manage data with the array **Container**.  

![Uint8_Queue class example](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Uint8_Queue_Architecture_Class_Example.puml)

To define a queue, its necessary to define an array and to associate the object
instanciated from the derived class with it.

![Uint8_Queue object example](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/Queues/master/doc/Uint8_Queue_Architecture_Object_Example.puml)

