# ADASTRA
#### Description:
This project features a quiz centered around the fascinating world of astronomy, offering users the ability to register an account. Developed using the Flask framework as the foundation for the web application, this project reflects my passion for astronomy, particularly planets and their moons. I've meticulously integrated routes, forms, and models into the main app, creating a seamless experience for users.

User registration is a key feature of my project. By visiting the registration page, users are prompted to provide their information. It's important to note that all passwords are securely encrypted before being stored in the database. To achieve this, I've employed the bcrypt library for password encryption. Additionally, I've harnessed several Flask libraries, such as Flask-WTF, to construct the registration and login forms. SQLAlchemy is utilized to persist user data, with Flask-WTF's validators ensuring the accuracy of user inputs.

Routing plays a pivotal role in rendering HTML templates on the website. I've used the "render_template" function to dynamically display templates as users navigate the site.

For the quiz functionality, I've developed a JavaScript file that handles all the logic. This includes generating questions and identifying correct answers. To manage user authentication, I've incorporated the Flask-Login library and its "login_manager" feature.

In the registration route, I've implemented both "GET" and "POST" methods. Within this structure, I check if the form validates upon submission. If it does, the user is created by adding their information to the database using "db.session.add()" and then committing the changes with "db.session.commit()". Subsequently, users are redirected to the main_page, where they can access the quiz. It's important to note that registration and login are prerequisites for quiz participation. If a user attempts to access the quiz without registering, they are directed to the login page, where they can also find the option to register.

In summary, my journey in building this project began with an exploration of Flask and various forms beyond those covered in the CS50 course. I initiated the project by crafting HTML templates, establishing a base.html template for broader application. Next, I connected URLs using "url_for" and created routes within my application.py file. I developed Flask forms to seamlessly interact with the database, creating both login and registration forms. The registration form incorporates logic for secure password storage through password hashing. Subsequently, I implemented the login form and connected it to the respective route, ensuring that user input matches the information they previously provided during registration.

In closing, I'd like to express my gratitude to the CS50 team for their invaluable course and support in the realm of computer science. Farewell to the world of coding adventures!


### Pre-requirements 📋

Flask-Bcrypt==0.7.1
Flask-Login==0.5.0
Flask-Session==0.4.0
Flask-SQLAlchemy==2.5.1
Flask-WTF==0.15.1
WTForms==2.3.3

### Installation 🔧
you will need to install the requirements

for example

```
pip install flask_SQLAlchemy
```

```
## Built with 🛠️

Flask https://flask.palletsprojects.com/en/2.0.x/ - Web framework used


## Author ✒️

Camilo Arango - All project - CamiloArango](https://github.com/CamiloArango
```

Thanks again for everything.

This was CS50!
