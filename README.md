# biquadris-game
A tetris-like game built with C++, where players take turns dropping blocks. Unlike tetris where players have a time constraint, Biquadris gives players an unlimited amount of time to decide where to drop their blocks. 

Every move that a player makes will drop their block by one position until the player either chooses to set their block, or the block is moved to a position that cannot be further changed. Scores are increased upon clearing a row or more and the player that scores the highest score wins the game. 

Players are also able to interact with their opponents by performing “special actions” (blinding opponent, forcing opponent's block, toggling heaviness of opponent's block) that affect different aspects of the game. 

## Core Design
<p align="center">
<img src="/core-design.png" alt="Core Design" width=50%/>
</p>

## Design Patterns
- [Template Method](https://refactoring.guru/design-patterns/template-method)
- [Factory Method](https://refactoring.guru/design-patterns/factory-method)
- [Observer](https://refactoring.guru/design-patterns/observer)
- [Abstract Factory](https://refactoring.guru/design-patterns/abstract-factory)

## Performance Measures
- free from memory leaks with the use of [smart pointers](https://en.cppreference.com/book/intro/smart_pointers), reducing memory tracing issues
- able to handle multiple commands with [Trie](https://en.wikipedia.org/wiki/Trie) data structure
- minimum recompilation for adding new levels with the use of template method design pattern
- migrated to classes-usage than methods-usage to simplify extensibility
- simplified user-interface with [Model view controller](https://en.wikipedia.org/wiki/Model-view-controller)

## Screenshots
<p align="center">
<img src="/screenshots/image1.png" alt="Image1" width=65%/>
<img src="/screenshots/image2.png" alt="Image2" width=65%/>
<img src="/screenshots/image3.png" alt="Image1" width=65%/>
<img src="/screenshots/image4.png" alt="Image2" width=65%/>
<img src="/screenshots/image5.png" alt="Image1" width=65%/>
<img src="/screenshots/image6.png" alt="Image2" width=65%/>
<img src="/screenshots/image7.png" alt="Image1" width=65%/>
<img src="/screenshots/image8.png" alt="Image2" width=65%/>
</p>

## Project Details
Biquadris project serves as the final project for [CS 246: Object-Oriented Software Development](https://cs.uwaterloo.ca//current/courses/course_descriptions/cDescr/newCDescr/CS246) in the Winter 2020 term.
<br>Grade: 100%

## Copyright
Copyright (C) 2019 Jun Qing Lim<br>
Under [University of Waterloo's Policy 71](https://uwaterloo.ca/secretariat/policies-procedures-guidelines/policy-71), project's source code is not released. View of source code is available upon request, subject to terms and conditions.

