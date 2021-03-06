## Project structure

In the end, your project folder will look like:

```
|- bin/
|- controllers/
    |- auth.controller.js
    |- message.controller.js
    |- user.controller.js
|- helpers/
    |- utils.helper.js
|- middlewares/
    |- authentication.js
|- models/
    |- User.js
    |- Message.js
|- routes/
    |- index.js
    |- auth.api.js
    |- message.api.js
    |- user.api.js
|- .env
|- .gitignore
|- app.js
|- package.json
```

- `routes/` stores `.api` files that determine routes end point which is a URI and a specific HTTP request method (GET, POST, and so on). Each route have a handler function which is defined in `.controller` file.
- `models/` stores the schemas that map with the collections in your MongoDB.
- `middlewares/` stores Express middleware like Authentication or Validators.

Good job! [Back to instructions](/README.md)
