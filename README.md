# Web-Tech-UOBVolleyball

To run:
npm start from main folder
go to https://localhost:8081
Admin login details:
email: davide@gmail.com
password: davide
Signup/Login system uses a SQLite3 database to store and look-up user data, flash messages are used to notify
a user of whether they have registered, have logged in, have logged out or some mistake occured during the process
such as a password mismatch or the email not being in our database. Password is securely hashed using bcrypt.
