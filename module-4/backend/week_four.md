## Week Four - Module 4 Recap

Fork this repository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's your favorite project management tool?
  - Pivotal Tracker. I miss Waffle's integration with git issues, but  I think a lot more detail can go in to Pivotal cards.
2. Why do we create staging environments?
  - Because production apps are running on a different machine(a server) and sometimes assets are compiled differently(looking at you, Rails asset pipeline) we want to recreate that other environment as closely as possible to catch any errors that might occur on deploy.
3. What are the characteristics of a good README (in your opinion)?
  - A good readme contains notes about dependencies, set up instructions, and code samples.
4. What's one main improvement you're going to make to your code regarding accessibility issues?
  - Using semantic tags when writing HTML or React components, being conscious of color choices, and using best practices like alt tags for images.
5. What are some basic security concerns to be aware of when building applications?
  - Not exposing sensitive information(production keys, etc), sanitizing user inputs.
6. Why is continuous integration helpful/important?
  - Continuous Integration is important because it allows us to catch potential errors before they are introduced into the codebase through a PR.
7. What are some continuous integration tools?
 - TravisCI, CircleCI, HoundCI

#### Review  

8. What are some characteristics of "good" git workflow?
  - Atomic commits, use of branches and PRs, merging updated code into feature branches regularly.
9. What are the four fundamental concepts of object oriented programming?
  - Abstraction, Polymorphism, Inheritance, and Encapsulation
10. What's a module in Ruby and what's the difference between a class and a module?
 - A module is a piece of code that contains constants and behavior, but does not contain state like a class does. 
