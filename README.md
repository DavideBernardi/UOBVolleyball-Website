# Web-Tech-UOBVolleyball

## Usage 
```
$ npm start
```
Visit http(s)://localhost:8081/ to view the website.

Admin login details:

```
email: davide@gmail.com
password: davide
```

## Built With 
[Bootsrap](https://github.com/topics/bootstrap) | [Handlebars](https://github.com/handlebars-lang/handlebars.js)  | [Express](https://github.com/topics/express)  | [SQLite](https://www.sqlite.org/index.html)

## Additional Info
Signup/Login system uses a SQLite3 database to store and look-up user data, flash messages are used to notify
a user of whether they have registered, have logged in, have logged out or some mistake occured during the process
such as a password mismatch or the email not being in our database. Password is securely hashed using bcrypt.
