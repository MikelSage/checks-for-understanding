## Week One - Module 4 Recap

Fork this repository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's the most useful thing you learned from completing the intermission week work?
  - Exporting modules, testing with Mocha and Chai
2. What are some tools to help debug JavaScript code?
  - PryJS, debugger, javascript console
3. What are some tools you need in order to unit test your JavaScript?
  - Mocha testing framework, Chai assertion library
4. What is the syntax for invoking a function?
  - functionName();
5. What's `this` in JavaScript?
  - This can refer to either the global or window objects, or if called inside a method on an object it returns the object.
6. What is Webpack and why is it useful?
  - Webpack is a module bundler and allows us to bundle our CSS and JS into one file to reduce use of multiple script tags and the end user having to download so many files.
7. When/why do you want to use event delegation?
  - When we want to set listeners on elements that are not on the page yet. We do this to avoid setting multiple listeners and avoiding memory leaks.
8. What's `npm` and what do we use it for?
  - Node Package Manger. We use it to install and manage dependencies in our node projects.

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.
  - MVC stands for Model-View-Controller
    - The model layer handles interaction with the database
    - The view layer handles the creation of html dynamically using data from the models and controllers
    - The controller layer handles communication between the client, models, and views by passing information between them.

10. What are a few ways to optimize a Rails application?
  - Use of message queues and background workers, caching
11. What's a background worker? When would we want to use a background worker?
  - A background worker is something that handles jobs while the rest of the app continues operation as normal. An example is using a background worker to handle sending email once a person has signed up for a site so they don't have to wait for their email to be generated and sent( which might take a really long time depending how many people are getting emails generated).
