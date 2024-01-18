# Polling System API Using Nodejs

## Features
- Create a questions (you can add as many questions as you want)
- Add Options to the questions
- Delete the questions
- View questions along with its options
- Delete Options
- Add Votes to the options

## Important endpoints of the API
- Create your own questions(post): http://localhost:5000/questions/create
- Delete the questions(delete): http://localhost:5000/questions/id/delete
- Add Options to the questions(post): http://localhost:5000/questions/id/options/create
- View questions along with its options(get): http://localhost:5000/allquestions
- Delete Options(delete):  http://localhost:5000/option/id/delete
- Add Votes to the options(post): http://localhost:5000/options/id/add_vote
