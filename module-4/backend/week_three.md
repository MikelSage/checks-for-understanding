## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. At a high level, what is Node?
  - Node is essentially a way to run JavaScript on the server side using Google's V8 JavaScript engine.
2. What is Express? What is Express similar to in the Ruby world?
  - Express is a web application framework for JavaScript. I would probably compare it to Sinatra in the way that it is structured.
3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
  - ```
    app.get('/', function(request, response) {
        response.send('Welcome home.')
      })
    ```
4. What do we use Knex for?
  - Knex is used for writing migrations and building SQL queries in express.
5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?
  - By kind of modeling the server.js file as a router, and then abstracting code dealing with retrieving information from the database into models, code dealing with requesting and passing that information to the controller level, and I'm not quite sure how the view fits here with Quantified Self since it was in a separate app and I've always envisioned the view layer as more a template that produces html rather than an actual html page with JS.
6. How do you execute raw SQL in node?
  - Using knex it would be `database.raw('SELECT * FROM good_doggos')`
7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
  - One advantage of having them separate might be that if you wanted to rewrite your back end in another language or framework, you wouldn't have to do much to the front end, whereas if you had a full stack Rails App and wanted to move to Django you might have to rewrite all your views. A disadvantage might be that you miss out on some of the conveniences of a framework like rails where you can manipulate data easier before it hits the frontend.

#### Review  

8. Describe DNS.
  - DNS stands for Domain Name Service. It allows users to type urls in plain text by taking that text and finding the actual IP address for that name.  
9. What does writing clean code mean to you?
  - It means writing code that is easy to change(DRY, SRP), easy to maintain(encapsulated, abstracted), and is easy to pick up when either seeing it for the first time or coming back after a long time(file organization, desriptive variable/method/class names).
10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?
  - For the not essay version, I would start out with a class for the Room, which would know about its status (booked, available), a Floor that would know about all its Rooms, and a Hotel which would know about all the floors and other information like occupancy, employees, profits. I would have a Person class that would have Customers and Employees inherit from it. 
