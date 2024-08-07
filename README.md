These assignments will be set up in parts for a Car Inventory API. 

Using these steps should help with structured practice for making your own Flask app. 

You'll be making a Car inventory - ultimately, it should be able to display data about cars in Insomnia. 

You'll eventually make authentication and API routes as well, but this part of the document will be graded only on the site folder. 

You can also do the whole project and then submit that as a whole after you're all the way done, since these assignments don't strictly adhere to the same order we made our phonebook apps in. 

Using the steps we covered in class, create the following pages for your Car collection API.

You will need to create the following files/folders:
  - [x] Virtual Environment
  - [x] Main Package Folder (eg phonebook)
  At min 2 blueprint folders with
    - [x] templates_folder (ie auth_templates)
    - [x] routes.py
  - [x] static
  - [x] main_templates_folder (ie templates)
  - [x] __ init __.py
  - [x] config.py

- [ ] You will also need to create the flask environment variables we mentioned at the start of class today. You can find instructions on that inside of the reference repo

NOTE/HINT: It may be a good idea to 
- [x] create a .gitignore file and place your Virtual Environment inside of that
- [ ] along with .vscode ??
- [x] and __pycache__ folders.

A sample is linked below. If you're on a Mac, add the .DS_Store file as well. 

- [ ] Feel free to style your landing page in whatever suits your personal style. However, you may use our class project as a model/reference if you would like to.

In continuation with this module's homework, your task is to build a form for a user to input data and persist that data into a Car-Collection Database Table Called "user".

You will need to create the following:
Inside of the blueprint folder for "authentication" (assuming the name is "authentication"):
  - [ ] One routes: One for "signup"
  - [ ] One User Model with the basic infomation listed:
      - [ ]  ID
      - [ ]  First_name
      - [ ]  Last_name
      - [ ]  email
      - [ ]  password
      - [ ]  token
      - [ ]  date_created
  - [ ] One Form with the following information:
      - [ ] email
      - [ ] password
      - [ ] submit_buttom

  - [ ] One .env file: to add your DATABASE_URL

Note: You may add more to your Form/Model if you would like, but the min is listed above.

So by the end of the homework for tonight you should have:
- [ ] A Database Called "car-collection" (Create this inside of Elephant SQL)
- [ ] A Database Table called "user"
- [ ] A form that can be placed on your HTML for signup
- [ ] Data in the user table given to your database by the user form

HINT: You will need to add the following dependencies to your virtual environment
- [ ] pip install Flask-WTF
- [ ] pip install Flask-Migrate
- [ ] pip install psycopg2
- [ ] pip install psycopg2-binary -- For those on mac machines
- [ ] pip install email-validator -- Verification of emails inside of forms
- [ ] pip install python-dotenv
