# Rumbl

Rumbl is a phoniex project from the book Programming Phoenix book

To clone this repo: `git clone https://github.com/ghraka/rumbl.git`

To start this Phoenix app:

  * Change into the cloned directory `cd rumbl`
  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`
  * Navigate to `localhost:4000`


Defined Routes:

`page_path     GET     /              Rumbl.PageController :index`
`user_path     GET     /users         Rumbl.UserController :index`
`user_path     GET     /users/new     Rumbl.UserController :new`
`user_path     GET     /users/:id     Rumbl.UserController :show`
`user_path     POST    /users         Rumbl.UserController :create`
`session_path  GET     /sessions/new  Rumbl.SessionController :new`
`session_path  POST    /sessions      Rumbl.SessionController :create`
`session_path  DELETE  /sessions/:id  Rumbl.SessionController :delete`