# object_oriented_concept

## What is it?
  - background and problems
  - goal
    - manipuate dep flow so that reduce impact
  - how oo can be used to achive the goal
    - program is a set of small components
    - tight coupling 
      - problems of tight coupling
        - one change on the lower level component affect the entire system
  - caveat : 
    1. some cases don't require you to use oo. it's ok. there is always a reason to use oo or decoupling. without the reason, the result is counter-productive (increase complexity and no benefits) => wasting your time
### OO-basics
  * Inheritance
  * Abstraction
  * Encapsulation 
  * Polymorphism
 (* Interface
  * Composition
### OO-principles 
  * program to interface, not an implementation
  * favor composition over inheritance
### Design Pattern
  * Decorator pattern: extend functionality of an object ( NOT add addtional functionality such as another behavior)
  * Strategy pattern
  * Observer pattern: need review.
  * Factory Pattern
  * Adapter/Facade pattern
  * Mediator Pattern: 
    - two variation: 
      - 1. using Observer Pattern
      - 2. composition
  * Command pattern
### SOLID principles
  * Single Responsibility principle
  * Open to extension, but close to modification
  * Liskov Substitution principle
  * Interface Segragation principle
  * Dependency Inversion principle: sound like this exist only for dependency rule?
