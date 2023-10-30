# Task

### 1. What do we mean by **coupling** and **cohesion** when discussing structured design?
**Coupling** in structured design can be used as way to measure quality when evaluating how closely connected and depedenet modules are on each other within applications. The connection of couplings can be described as loose, weak, tight or strong.

- **Tight coupling:** 
Tight coupling uses modules close to each other within an application for specific uses, interfaces or frontend functions. The benefits of tighly coupling make applications easier to maintain and are often quicker to develop. However, it reduces flexibility, scalability  and the reusability of code as adding new features into an application may need large changes, or updates to other parts of an application.

- **Loose coupling:**
Loose coupling sets out to reduce the dependencies of modules on each other within an application. This can be achieved by using interfaces by allowing parts of an app to have its own behaviours. Loose couplings helps components to be more easily swapped as they are not as dependent on each othe compared to tight coupling.

**Cohesion** in structured design can refer to the relationship between modules within an app, and how well they work together to complete their designed purpose. High cohesion is used when components within an app are closely related, whereas low cohesion means that components are loosely related and serve several purposes.

It is important to have cohesion when developing to preserve the scalability and reliablity of an application.

### 2. What is the difference between **top-down** and **bottom-up** design? Which best describes a function oriented design?
A **top-down** design starts with creating a high-level, overall view of a system, and then breaking this into smaller parts. This can be described as a function oriented design, as 

A **bottom-up** design instead considers to the requirements of users issues, and then continues to move upwards. This method is to evaluate what features will resolve user issues.
   
### 3. In which design methodology would a **class diagram** be most useful?
A **class diagram** would be the most useful for a **top-down** design, as it would allow developers to ensure they address all elements of the system and architecture needed which has been mapped out at a high-level. It will also be beneficial as a class diagram will display smaller components, and how their relationship functions within the application as a whole.

### 4. What are the **four pillars of object oriented programming**? Give a single-sentence description of each?
-  **Abstraction:** Hides the implementation of objects in an OOP language, i.e. a interacting with a coffee machine app at user level will not include setting the water temperature, or the amount of ground coffee needed to brew.
- **Encapsulation:** Restricts the access to the data of an object.
- **Inheritance:** Used as a method to implement superclasses, allowing child classes to 'inherit' / share certain properties and behaviours, i.e. a zoo has animals that all eat different foods.
- **Polymorphism:** Allows an object to use and take on several variables / methods of different types at different times. 

### 5. What is the **strategy pattern**? How would its implementation differ between a functional and object oriented system?
The **strategy pattern** is a design that allows objects to pick from multiple algorithms and behaviours, encapsuating each one, then making them interchangeable. It enables algorithms to be separated from the main object, therefore, allowing the object to assign the behavior of the chosen algorithm.

### 6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
I propose that an Agile methodology would be the most suitable to use when creating a new online payment system. The Agile approach would allow for continous developement and deployment with sprints, which would enable a developer team to release regular updates, as well as ensure that the appliction is functioning at an optimum level for different sectors, such as takeaways and clothes stores in this case.

The Agile way of working will also help teams address any new problems that arise during the development process, as well as the opportunity to work closely with clients on new technical landscapes and other budget related matters.


