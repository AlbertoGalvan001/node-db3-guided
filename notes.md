#Joins

A `foreign key` is a column on a table that references the primary key on another table.

A way to link a record (or row) in one table to a record in another table.

A foreign key is a key which pairs toa tables primary key showing relationship between the rows.

A foreign key is a column or group of columns in a relational database table that provides a link between data in two tables. It acts as a cross-reference between tables because it references the primary key of another table, thereby establishing a link between them.

## Application Architecture
Opinion(luis hernandez)
 For an API we normally have (at least) 3 layers
    - Routing (this is the `express` stuff, the endpoints, middleware) -> routers, middleware.
    - Data Access (the knex + SQLite || Postgress code) -> we can call it models.
    - Business Logic (this makes your application unique) -> regular functions packed into a module.