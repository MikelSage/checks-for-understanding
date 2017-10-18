## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's one difference between ES5 and ES6?
  - ES6 introduces the template literal, which allow for embedded expressions.
2. What's the difference between asynchronous and synchronous JavaScript?
  - Asynchronous JavaScript allows some operations to be evaluated separately from the main stack and then reinserted into the stack by the event loop, while synchronous JavaScript requires one operation to complete before it can move on the next.
3. What are the four pillars of Object Oriented programming?
  - Abstraction: Logic is hidden from layers that do not need to understand it, ex: An average driver doesn't need to know the exact mechanics of his car's brake system, just that they should press the brake pedal to make it happen.
  - Polymorphism: Different objects can receive the same message, ex: 'Run' and perform behavior unique to the object, ex: Dog runs with four legs, Human runs with 2 legs, Fish stares at you confused
  - Inheritance: Objects can receive attributes and behavior from ancestor objects and use or modify them. ex: A poodle can inherit attributes and behavior from a Dog class, and modify some attributes like fur length and temperament
  - Encapsulation: The process of keeping related data and logic in a single unit. ex: Keeping attributes and behaviors related to a human in a Human class.
4. What are some tools available in JavaScript to help you write object oriented code?
  - There is the object literal notation `{}`, constructor functions, and in ES6 there is the new `class` keyword.
5. What are some key concepts to be aware of when refactoring your JavaScript?
  - Organization, repeated code (WET)
6. What's a callback function and what are some reasons when we use/need callback functions?
  - A callback function is a function that is passed to another function as a parameter, and is then executed by the first function.
7. What's the scope of variables in Javascript?
  - Variables can exist in the global scope (available everywhere), or the local scope (available within functions)
8. What's the difference between `==` and `===` in JavaScript?
  - The `===` refers to the strict comparison, which compares variable type first then equivalence, while the `==` checks only the equivalence of the values.
9. Why do front end frameworks exist?
  - To help structure code in a way that is maintainable and easy for developers and others to work with.

#### Review  

10. Why do people say "HTTP is stateless"?
  - Because no information about the transaction is retained once the request is completed.
11. Describe a RESTful API.
  - A RESTful API is one that follows the conventions of REST in that it makes use of the verbs GET to retrieve information, POST to create records, PUT/PATCH to update records, and DELETE to remove records.
12. What are some main characteristics of a team following an agile workflow?
  - Breaking up of work into sprints/iterations, delivering code/features on a regular basis, open communication with product owner.
13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?
  - Advantages
    - Usually uses a database maintained by a company with a higher security budget
    - Can streamline process for some users
    - Can gain access to lots of data about the user
  - Disadvantages
    - Narrows user pool
    - Adds another dependency to the project
