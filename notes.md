`flask db init` : create the migration repository for microblog
`flask db migrate -m ""` : generates automatic migrations. The `-m` option adds a short descriptive text to the migration(like git). This command does not make any changes to the database, it just generates the migration script.
`flask db upgrade` : To apply the changes to the database.
snake case : User -> user, AddUser -> add_user.