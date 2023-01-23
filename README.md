# TeamSoftwareProject

## Frontend
I got started on the frontend. I created some very basic authentication flow. I used reactJS because it's really the easiest thing ever. React is a javascript library from building web UIs. It's not complicated at all beacuse at it's core react is still only HTML and CSS
To run the react application you need to install 
Node 18 from here https://nodejs.org/en/
Then after that you cd into frontend and run "npm install"
after that you run "npm start" its very simple. It should open on it's own.
input can be removed or added it's just a basic implementation to get something working

## Backend
Activate the dev environment on mac with 
. venv/bin/activate
or on windows with
venv\Scripts\activate

I'm using Flask sqlalchemy to connect to mysql because I couldn't get flask and mysql working in any other way
feel free to try something else
I commented the best I could but you can ask me anything if you don't get it
I used here https://docs.sqlalchemy.org/en/14/orm/queryguide.html as a reference also you can ask me any question

### How it works
The user send a inputs like name emaill password and so on. The server checkes if the user exists if not it adds the usere to the database and creates a token for authentication and sends the response back i.e. user information plus the token

Same with login. It checks if the user exists the it checks if the password matches with that already stored in the database if so respond accordinly pretty simple stuff

to run the backend you have to cd into backend folder
pip install -r requirements.txt
flask --app app.py --debug run
so that the server refreshes when the file changes

If you install new modules with pip you can say pip freeze > requirements.txt to add it to the file

