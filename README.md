# [Nativo Beans Store - Shop Coffee and Cacao from Peru](https://nativo-beans.herokuapp.com/)

View in Desktop
<img src="https://github.com/Julia-IO/nativo_beans/blob/master/media/nativo_beans_desktop_view.png" width="800">

View in Iphone
<img src="https://github.com/Julia-IO/nativo_beans/blob/master/media/nativo_beans_iPhone_view.jpg" width="800">

---

## Table of Contents
1. [**UX**](#ux)
    - [**User Stories**](#user-stories)
    - [**Design**](#design)
        - [**Framework**](#framework)
        - [**Color Scheme**](#color-scheme)
        - [**Icons**](#icons)
        - [**Typography**](#typography)
    - [**Wireframes**](#wireframes)

2. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Features Left to Implement**](#features-left-to-implement)

3. [**Technologies Used**](#technologies-used)
    - [**Front-End Technologies**](#front-end-technologies)
    - [**Back-End Technologies**](#back-end-technologies)

4. [**Testing**](#testing)
    - [**Validators**](#validators)
    - [**Compatibility**](#compatibility)
    - [**Known Issues**](#known-issues)

5. [**Deployment**](#deployment)
    - [**Local Deployment**](#local-deployment)
    - [**Remote Deployment**](#remote-deployment)

6. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Code**](#code)
    - [**Acknowledgements**](#acknowledgements)

---

## UX

This project is part of my [Code Institute](https://codeinstitute.net/) Full Stack Software Development studies, specifically the **Full Stack Frameworks With Django** module. 
In this project, I've built a full-stack site based around an e-commerce business logic used to control a centrally-owned dataset. 

Value Provided:

By authenticating on the site, users can advance their own goals (buy products).
Before authenticating, the site makes it clear how those goals would be furthered by the site.
The site owner is able to make money by providing this set of services to the users. There is no way for a regular user to bypass the site's mechanisms and derive all of the value available to paid users without paying.

I decided to build an e-commerce project so that I could follow step by step the course explanations.
I finally adapted it to my personal purpose, which was offering Coffee and Cacao products from Peru.



### User Stories

"**_As a user, I would like to_** _____________________________"

:white_check_mark: *denotes items that have been successfully implemented*

- :white_check_mark: *view the site* from **any device** *(mobile, tablet, desktop)*.
- :white_check_mark: *view a list of products* as a **Site User**.
- :white_check_mark: *view individual product details* as a **Site User**.
- :white_check_mark: *easily view the total of my purchases* at **anytime** as a **Site User**.
- :white_check_mark: *easily register for an account* as a **Site User**.
- :white_check_mark: *easily login or logout* as a **Site User**.
- :white_check_mark: *easily recover my password* as a **Site User**.
- :white_check_mark: *receive an email confirmation after registering* as a **Site User**.
- :white_check_mark: *have a personalised user profile* as a **Site User**.
- :white_check_mark: *sort the list of available products* as a **Site User**.
- :white_check_mark: *sort a specific category of a product* as a **Site User**.
- :white_check_mark: *search for a product by name or description* as a **Site User**.
- :white_check_mark: *easily select the quantity of a product* as a **Site User**.
- :white_check_mark: *easily and securely checkout* as a **Site User**.
- :white_check_mark: *easily add new products* as an **Admin User**.
- :white_check_mark: *easily update products* as an **Admin User**.
- :white_check_mark: *easily delete products* as an **Admin User**.

### Design

I've followed a simple design prioritizing simplicity and usability.

#### Framework

- [Bootstrap 4.4.1](https://getbootstrap.com/)
    - Front-end open source toolkit to help desing responsive mobile-first sites.
- [jQuery 3.5.1](https://code.jquery.com/jquery/)
    -To keep the JavaScript minimal, I have decided to use jQuery as foundation to my scripts framework.
- [Django 3.1.7](https://www.djangoproject.com/)
    - Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.

#### Color Scheme

I have opted for a clear background scheme lighten up with the following colours palette:

- ![#1d614c](https://placehold.it/15/1d614c/1d614c) `#1d614c` (hex #1d614c is composed of 11.4% red, 38% green and 29.8% blue. - *card panels and main action buttons*)
- ![#dd6643](https://placehold.it/15/dd6643/dd6643) `#dd6643` (hex #dd6643 is a shade of red orange - *footer background and some forms placeholders*)
- ![#252151](https://placehold.it/15/252151/252151) `#252151` (hex #252151 is a dark shade of blue-magenta - *Footer text colour and social icons*)
- ![#ed2137](https://placehold.it/15/ed2137/ed2137) `#ed2137` (hex #ed2137 is a shade of pink-red - *home background image*)

This colour palette has been thought taking as an inspiration the colours found in Peru landscapes.

#### Icons

- [Font Awesome 5.8.1](https://fontawesome.com/)
    - Although Materialize Icons have nearly 1,000 free-to-use icons, I prefer the look of Font Awesome's icons, and they have more to suit my specific needs for this project. 

#### Typography

- I have used [Google Fonts](https://fonts.google.com/). I have stick to one font: 
    - [Lato](https://fonts.google.com/specimen/Lato)


### Wireframes

For my wireframes, I have used sketches on a notebook. It's how I like it the best.

##### back to [top](#table-of-contents)

---


### Existing Features

**Register Account**
- I've created a superuser who can Add, Update and Delete Products. To check this funcionality, please use:
Username: julita10
Password: Nativo-julita10


**Sign up to the shop**
- Site Users can sign up to create an user and they will get a confirmation email to validate their accounts.


**Log In to Account**
- Once users have signed up, they can easily log in to their accounts.


**Log Out of Account**
- Users can easily log out of their account with the click of a button.

**Delete Products**
- Only Superuser can delete products.
- [CRU**D**] Delete or 'remove' products.

**Update Projectss**
- Only Superuser can delete products.
- [CR**U**D] Update or 'edit' products.

**Add New Products **
- Only Superuser can add new products.
[**C**RUD] Create or 'add' a new product to the shop offer.


### Features Left to Implement


- I'd like users to be able to change format (250g, 500g, 1 kg, etc) and that prices are updated automatically.

##### back to [top](#table-of-contents)

---

## Technologies Used

- [VS Code](https://code.visualstudio.com/) - Used as my primary IDE for coding.
- [GitHub](https://github.com/) - Used as remote storage of my code online.
- [Photoshop CS6](https://www.adobe.com/Photoshop) - Used for editing images.
- [TinyPNG](https://tinypng.com/) - Used to compress images for faster loading.

### Front-End Technologies

- [HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - Used as the base for markup text.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) - Used as the base for cascading styles.
- [jQuery 3.5.1](https://code.jquery.com/jquery/) - Used as the primary JavaScript functionality.
- [Materialize 1.0.0](https://materializecss.com/) - Used as the overall design framework.



### Back-End Technologies

- **Flask**
    - [Flask 1.1.2](http://flask.pocoo.org/) - Used as a microframework.
    - [Jinja 2.11](http://jinja.pocoo.org/docs/2.11/) - Used for templating with Flask.
    - [Werkzeug 1.0.1](https://werkzeug.palletsprojects.com/en/0.16.x/) - Used for password hashing, authentication, and authorization.
- **Heroku**
    - [Heroku](https://www.heroku.com) - Used for app hosting.
- **Python**    
    - [Python 3](https://www.python.org/) - Used as the back-end programming language.
    - [MongoDB Atlas](https://www.mongodb.com/) - Used to store my database in the 'cloud'.
    - [PyMongo 3.8.0](https://api.mongodb.com/python/current/) - Used as the Python API for MongoDB.

##### back to [top](#table-of-contents)

---

## Testing

**Creating an Account**

I've created1 admin account and 3 linguists accounts in order to confirm authentication and validation worked as expected.

**Add | Edit | Delete a Project**

I've created about 3 projects. These recipes were created the admin account, the only one with the necessary permissions.

**Pagination**

When implementing pagination, I had a lot of manual tests to undergo, in order to make pagination work for multiple scenarios. I needed to test that all aspects of pagination worked with and without the option for searching the database. These included:


**Profile**

As a **linguist user**, there are four profile buttons.

- *View your own assigned projects*:
    - You can check your assigned projects and get all the info you need to start working + contact info of the Project Lead.
- *View your profile*:
    - You can check if all your data is correct (including billing and paypal info) and contact the relevant email address in case you need to update your info.
- *Log out*:
    - You can easily log out from your account with a clear Log Out button in the navbar.


As the **Admin**, you can do the same as the linguists, but you can see ALL THE PROJECTS and also edit and/or delete them. Besides, you can:

- *Add New Project*:
    - You can create a new project providing all the relevant info linguists will need such as project lead, instructions, language pairs, specialization, CAT Tool or software to be used and due date.
- *Add New Linguist to the team*:
    - You can add new linguists to the team including contact, language pairs, billing and paypal info.
- *Manage Categories of services*:
    - You can easily create, edit and/or delete new categories / services offered.

### Validators

**HTML**
- [W3C HTML Validator](https://validator.w3.org) - Unfortunately the W3C Validator for HTML does not understand the Jinja templating syntax, so it therefore shows a lot of errors with regards to `{{ variables }}`, `{% for %} {% endfor %}`, etc. Aside from the Jinja warnings and errors, all of the remaining code is perfectly validating. Also due to the Jinja templating, certain elements cannot be 'beautified' across multiple lines, and must remain on a single line. An example of this is the `<select>` element, which is rather long with specific Materialize classes, and Jinja templating.

**CSS**
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - As I've mostly have used Materialize, my style.css is quite simple and it has been properly validated.

**JavaScript**
- [Beautify Tools](http://beautifytools.com/javascript-validator.php)
    - No syntax errors!

**Python**
- [PEP8 Online](http://pep8online.com/)
    - My `.py` file contains severak E501 errors (line too long (83 > 79 characters) and several 261 errors (at least two spaces before inline comment) that I need to research upon and try to get fixed.)

### Compatibility

To ensure a broad range of users can successfully use this site, I tested it across the 6 major browsers in both desktop and mobile configuration.

- Chrome *v.74*
- Edge *v.18*
- Firefox *v.67*
- Safari *v.12*
- Opera *v.56*
- Internet Explorer *v.11*

### Known Issues

During development, I discovered two issues after committing to GitHub. 

- When editing a project as an admin, I wanted the previous info to get displayed. For some reason, the Type of Project is not always displayed.
- When adding new projects, I want to include some mailto or website links. While I can do that if I edit directly through the DB, it does not work directly from the forms.


##### back to [top](#table-of-contents)

---

## Deployment

### Local Deployment

Please note - in order to run this project locally on your own system, you will need the following installed:
- [Python3](https://www.python.org/downloads) to run the application.
- [PIP](https://pip.pypa.io/en/stable/installing) to install all app requirements.
- Any IDE such as [Microsoft Visual Studio Code](https://code.visualstudio.com).
- [GIT](https://www.atlassian.com/git/tutorials/install-git) for cloning and version control.
- [MongoDB](https://www.mongodb.com) to develop your own database either locally or remotely on MongoDB Atlas.

Next, there's a series of steps to take in order to proceed with local deployment:

- Clone this GitHub repository by either clicking the green *Clone or download* button and downloading the project as a zip-file (remember to unzip it first).
- Navigate to the correct file location after unpacking the files.
    - `cd <path to folder>`
- Create a `.env` file with your credentials. Be sure to include your *MONGO_URI* and *SECRET_KEY* values.
- Create a `.flaskenv` file and add the following entries:
    - `FLASK_APP=run.py`
    - `FLASK_ENV=development`
- Install all requirements from the [requirements.txt](https://github.com/Julia-IO/Linguist_Portal/blob/master/requirements.txt) file using this command:
    - `sudo -H pip3 -r requirements.txt`
- Sign up for a free account on [MongoDB](https://www.mongodb.com) and create a new Database called **project_manager**. The *Collections* in that database should be as follows:

**CATEGORIES**
```
_id: <ObjectId>
category_name: <string>
```

**LEADS**
```
_id: <ObjectId>
project_lead: <string>
```

**PROJECTS**
```
_id: <ObjectId>
project_name: <string>
category_name: <string>
project_lead: <string>
assigned_toe: <string>
project_description: <string>
project_languages: <string>
project_specialization: <string>
project_software: <string>
project_due_date: <string>
project_status: <string>
project_is_overdue: <string>
created_by: <string>
```

**STATUS**
```
_id: <ObjectId>
project_status: <string>
```

**USERS**
```
_id: <ObjectId>
full_name: <string>
email_address: <string>
source_language: <string>
target_language: <string>
billing_info: <string>
paypal_account: <string>
username: <string>
password: <string>
is_admin: <string>
```

- You should now be able to launch your app using the following command in your terminal:
    - `flask run`
- The app should now be running on *localhost* on an address similar to `http://127.0.0.1:5000`. Simply copy/paste this into the browser of your choice!

### Remote Deployment

This site is currently deployed on [Heroku](https://www.heroku.com/) using the **master** branch on GitHub. To implement this project on Heroku, the following steps were taken:

1. Create a **requirements.txt** file so Heroku can install the required dependencies to run the app.
    - `sudo pip3 freeze --local > requirements.txt`
    - My file can be found [here](https://github.com/Julia-IO/Linguist_Portal/blob/master/requirements.txt).
2. Create a **Procfile** to tell Heroku what type of application is being deployed, and how to run it.
    - `echo web: python run.py > Procfile`
    - My file can be found [here](https://github.com/Julia-IO/Linguist_Portal/blob/master/Procfile).
3. Sign up for a free Heroku account, create your project app, and click the **Deploy** tab, at which point you can *Connect GitHub* as the Deployment Method, and select *Enable Automatic Deployment*.
4. In the Heroku **Settings** tab, click on the *Reveal Config Vars* button to configure environmental variables as follows:
    - **IP** : `0.0.0.0`
    - **PORT** : `5000`
    - **MONGO_URI** : `<link to your Mongo DB>`
    - **SECRET_KEY** : `<your own secret key>`
    - **MY_ADDRESS** : `<your own email address>`
    - **SEND_TO** : `<recipient email address>`
    - **PASSWORD** : `<you own email password>`
5. Your app should be successfully deployed to Heroku at this point. :tada:


##### back to [top](#table-of-contents)

---

## Credits

### Content

- [*"How to Write a Git Commit Message"*](https://chris.beams.io/posts/git-commit/) by **Chris Beams** (*as recommended by Code Institute assessors on previous projects*)
- [*"Primer on Jinja Templating"*](https://realpython.com/primer-on-jinja-templating/) (*as recommended by Code Institute assessors on this project*)
- [*"Jinja Templating Documentation"*](https://jinja.palletsprojects.com/en/2.11.x/)

### Media

Sources of the images used on this site:

- **Logo** : the Tobetranslated was designed for me by my friends of [*"Nueve Estudio"*](https://www.n-u-e-v-e.com/)

### Code

- I've followed the videos of the Mini Project and I have adapted the code provided to meet my own project requirements.

### Acknowledgements
- Aaron Synnott
    - My mentor. Thanks for e-meeting and give me your opinions and helpful insights.

- [Tim Nelson](https://github.com/TravelTimN)
    - My most recurrent code tutor. I have also used one of your Read Me files as a template of my own.
- Cormac Lawlor
    - Code Institute Tutor: Thanks for helping me with my last-minute deployment issue with Heroku.

##### back to [top](#table-of-contents)