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
- [Bootstrap 4.4.1](https://getbootstrap.com/) - Used as the overall design framework.



### Back-End Technologies

- **Django**
    - [Django 3.1.7](https://www.djangoproject.com/) - Used as the Python Web Framework
- **Heroku**
    - [Heroku](https://www.heroku.com) - Used for app hosting.
- **Python**    
    - [Python 3](https://www.python.org/) - Used as the back-end programming language.
    - [AWS](https://aws.amazon.com/) - Used to store my static and media files.
- **Stripe**
    - [Stripe] (https://stripe.com/) - Used as the payments infrastructure


##### back to [top](#table-of-contents)

---

## Testing

I've tested this project both as an Admin (Superuser) and as a Site User in a desktop computer and in a iPhone.

### Validators

**HTML**
- [W3C HTML Validator](https://validator.w3.org) 

**CSS**
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) 

**JavaScript**
- [Beautify Tools](http://beautifytools.com/javascript-validator.php)
    

**Python**
- [PEP8 Online](http://pep8online.com/)
    - My `.py` file contains severak E501 errors (line too long (83 > 79 characters) and several 261 errors (at least two spaces before inline comment) not affecting functionality.)

### Compatibility

To ensure a broad range of users can successfully use this site, I tested it across the 6 major browsers in both desktop and mobile configuration.

- Chrome *v.74*
- Edge *v.18*
- Firefox *v.67*
- Safari *v.12*
- Opera *v.56*
- Internet Explorer *v.11*

### Known Issues

White space under footer with certain pages + certain sizes of large screens.


##### back to [top](#table-of-contents)

---

## Deployment

### Local Deployment

In order to deply this project I've needed first to:

- Create an account to [*Heroku*](https://heroku.com) to host the project.
- Create and account to [*Amazon Web Services*] (https://aws.amazon.com/)to host my media and static files.

The exact step by step was:
- Create the Heroku app
- Deploy to Heroku
- Create the AWS Account
- Create AWS Groups, Policies and Users
- Connect Django to S3.
- Connect media files and Stripe.



##### back to [top](#table-of-contents)

---

## Credits

### Content

- [*"How to Write a Git Commit Message"*](https://chris.beams.io/posts/git-commit/) by **Chris Beams** (*as recommended by Code Institute assessors on previous projects*)


### Media
- I created the background image myself.

### Code

- I've followed the videos of the Boutique Ado Project and I have adapted the code provided to meet my own project requirements.

### Acknowledgements
- Aaron Synnott
    - My mentor. Thanks for e-meeting and give me your opinions and helpful insights.

- [Tim Nelson](https://github.com/TravelTimN)
    - My most recurrent code tutor. I have also used one of your Read Me files as a template of my own.

- All Code Institute Tutors: Thanks for helping me with all the issues I've encountered on the way.

##### back to [top](#table-of-contents)