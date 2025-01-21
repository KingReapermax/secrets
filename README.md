## requirements:
  - browser
  - node js set up
  - postgresql server
## to run:
 - create a database and a table named users containing id, email, password, and secret columns.
 - you can use ```
                   create table users(
                     id serial primary key,
                     email text unique not null,
                     password text,
                     secret text);
               ```
  - fork and set up environment
  - create an .env file and set the credentials of postgresql and others.
  - run ```nodemon index.js```
  - open http://localhost:3000/ and try it
