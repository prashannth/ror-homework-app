# Homework management app

A rails and angular based homework management app for students and teacher.

Rails for back end and Angular for front end.


## Implemented user stories

1. Homework contains a title, a question and a due date.
2. Teacher can assign a homework to multiple students.
3. Student can see all assigned homework.
4. Student can submit a homework multiple times before the due date.
5. Teacher can see a list of latest submissions for a homework.
6. Teacher can see all submission versions for a student for a homework


## Running application

Make sure you have Ruby (2.2 or above) and Bundler installed.

To set up the database, run

```console```
bundle install
rake db:reset
```

This will set up the database and it also create 2 users: 'teacher' and 'student'.

To start the web server, run

```console```
bundle exec rails server
```

Open your web browser and go to http://localhost:3000

You can log in as a teacher by using 'teacher' as the username and log in as a student by using 'student' as the username.

Have fun!
