![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# 'Hello Django'-Walkthrough Project

`path('hello/', say_hello, name="hello")` - Django function located in the urls.py, 'hello/' is a '/hello' after the html that triggers the 'say_hello' function, name is the name of the url where function is executed
`python3 manage.py runserver` - cmd to run the app on the server
`HttpResponse`- A Django dfunction that takes a http request and prints a string as a response

### Templates
`render` -  a Django function that takes two arguments (request, 'directory'), where 'request' is the http request that triggers the file in the folder directory.
`path('', get_todo_list, name="get_todo_list")` - Django function located in the urls.py, '' is where the url that triggers the function goes, central value is the function it calls, and the last parameter is the name of the url.

### Migrations and Admin

`python3 manage.py makemigrations --dry-run` - Command with 'dry-run' will check if there is any new data added on the sequel lite database created for our use
`python3 manage.py showmigrations` - shows migrations that need to be applied, in the beginning there are some that the Django makes wehn initially installed
`python3 manage.py migrate` - migrates all changes, run with a tag/flag before to see what migrations are in question
`python3 manage.py createsuperuser` - Create a superuser to access the database and make changes

### Models Part 1



## Codeanywhere Reminders

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere, in the terminal, type:

`python3 -m http.server`

A button should appear to click: _Open Preview_ or _Open Browser_.

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere with no-cache, you can use this alias for `python3 -m http.server`.

`http_server`

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A button should appear to click: _Open Preview_ or _Open Browser_.

In Codeanywhere you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to _Account Settings_ in the menu under your avatar.
2. Scroll down to the _API Key_ and click _Reveal_
3. Copy the key
4. In Codeanywhere, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

---

Happy coding!
