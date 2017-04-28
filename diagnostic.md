# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
To put things simply, the backend adds function and supplies data to the client side server.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The model.
```

Which layer in the MVC pattern communicates with the model?

```md
The controller.
```

Why don't we use views in our interpretation of the MVC pattern?

```md

```

What does C.R.U.D stand for?

```md
Create
Read
Update
Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
The controller.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
// your response here
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
-client asks server to 'GET 'people/1''
-server asks
```

What is the command to generate a new rails-api app?

```bash
rails generate
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
- db:drop
- db:create
- db:migrate
- db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bin/rails generate scaffold pet name:string age:integer
```
