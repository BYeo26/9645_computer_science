## 0 Object Oriented Design Principles
### Association, Aggregation and Composition
- **Association** is when two classes loosely have a relationship (i.e. a teacher has a student and a student has a teacher)
	- theres no ownership
- **Aggregation** is when one class owns another, but the owned thing doesn't cease to exist when the owner is destroyed (i.e. a player is part of a team)
	- displayed using a hollow diamond shape between the two shapes
	- hollow diamond points towards the owner
- **Composition** is when is a stronger form of association when the owned thing would cease to exist when the owner is destroyed (room gets destroyed if hotel disappears)
	- displayed using a filled diamond shape

### Polymorphism
- Polymorphism is a programming language's ability to process objects differently depending on their class
- it also allows objects of different types to be treated as objects of a common type
- for example, objects have subclass, but can belong to a superclass (i.e. cat and rodent being subclasses, where mouse and beavers are objects, and animal is the superclass)

### Favour Composition over Inheritance
- Composition is a less rigid relationship than an inheritance relationship
- it allows for functionality to be implemented more easily
- it also just makes more logical sense in some instances
- i.e. a house (the class) having walls, windows, and a door

### Public, private and protected access modifiers
- information can be hidden
- access modifiers public, private and protected are included in a class definition to implement data hiding
	- Private: only code in the class can access it (written as `self.__variablename`)
	- Public: code in any class can access it (written as `self.variablename`)
	- Protected: varies between programming languages (written as `self._variablename`)

### Programming to an interface
- An **interface** is a collection of abstract methods that a group of unrelated classes may implement

### Advantages of the object oriented paradigm
- methodology forces designers to go through a large planning phase, which makes for a better design
- **Encapsulation**: source code for an object can be written tested and maintained independently
- once the object is made, a programmer doesn't need to know how it's methodologies work
- new objects can be created easily
- objects can be reused
- software is easier to maintain

