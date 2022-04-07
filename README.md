# AuthLogin
This is a Project repo for Technical interview at AVENUE SOUND.

![Banner](https://raw.githubusercontent.com/aadix420/AuthLogin/main/public/img/ss.png)

## Prerequisite
lampp

## How to install
1: Clone the repo (git clone https://github.com/aadix420/AuthLogin.git)
2: Install NPM (sudo apt install npm)
3: Install all the dependencies (npm install express path body-parser knex)
4: Setup postgres
```
psql -U postgres
\c databasename
CREATE TABLE users (id serial not null primary key, name varchar(255)) not null, email varchar(255) not null, password varchar(255) not null);
```
5: Start Npm from the source (npm start)
6: Vist (localhost:3000)

###### Technologies used: Javascript, HTML, CSS, NodeJS.
###### Working of the API was tested on Burpsuite.
