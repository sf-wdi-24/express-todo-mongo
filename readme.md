# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Express To Do App Continued

**Objective:** Add MongoDB and Mongoose to your To Do app.

## Getting Started

1. Make a new branch in your <a href="" target="_blank">express-todo-app</a> called `solution-mongo`.
2. Set up Mongoose in your To Do app. This includes installing the Mongoose module, creating a schema for your blog posts, and requiring the schema in your `server.js`.
3. Use Mongoose methods to perform all of your API's CRUD operations. Your app should have five API routes:
  * GET `/api/todos` should get all the todos from the database collection.
  * POST `/api/todos` should create a new todo in the database collection.
  * GET `/api/todos/:id` should get one todo document.
  * PUT `/api/todos/:id` should update a todo document.
  * DELETE `/api/todos/:id` should delete a todo document.
4. Test all your API routes with Postman before testing if the addition of Mongoose affected anything on your client-side. (It shouldn't have, but it's good to make sure.)

## Bonus

1. Read about <a href="http://mongoosejs.com/docs/validation" target="_blank">validations</a> and the built-in <a href="http://mongoosejs.com/docs/api.html#schematype_SchemaType-required" target="_blank">required validator</a> in Mongoose.
2. Add the required validator to all fields in your blog post schema.
3. In your API routes to create and update todos, respond with the error message if the required validation is not met.

## Submission

* As you make code changes, frequently commit and push to GitHub.
* Once you've finished the assignment and pushed your work to GitHub, make a pull request from **YOUR `solution-mongo` branch** to the original repo.
