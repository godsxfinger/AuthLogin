# AuthLogin
This is a Project repo for Technical interview.

![Banner](https://raw.githubusercontent.com/aadix420/AuthLogin/main/public/img/ss.png)

## Prerequisite
lampp

## How to install
- Clone the repo (git clone https://github.com/aadix420/AuthLogin.git)
- Install NPM (sudo apt install npm)
- Install all the dependencies (npm install express path body-parser knex)
- Setup postgres
```
psql -U postgres
\c databasename
CREATE TABLE users (id serial not null primary key, name varchar(255)) not null, email varchar(255) not null, password varchar(255) not null);
```
- Start Npm from the source (npm start)
- Vist (localhost:3000)

###### Technologies used: Javascript, HTML, CSS, NodeJS.
###### Working of the API was tested on Burpsuite.
