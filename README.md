<div align="center">
  
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)\
![Known Vulnerabilities](https://snyk.io/test/github/Szymcode/ContactBook/badge.svg)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/SzymCode/ContactBook/issues)
<a href="https://codeclimate.com/github/SzymCode/ContactBook/maintainability"><img src="https://api.codeclimate.com/v1/badges/82bf96d0eed9ecd61446/maintainability" /></a>\
![License](https://img.shields.io/badge/license-BSD--3-important)

</div>

# ContactBook

This website helps to storage contacts data, share it with others and download contact lists to JSON or PDF file.
You can clone this repo and run it on your internal server. The project was created for educational purposes and to demonstrate my coding skills to my future recruiters.
<br>
**I highly encourage you to contributions!**


## 🎯 TODO:

• Restrict routes in App.js with is_authenticated from django registration

• Dragging, resizing, deleting columns and create custom ones

• Download contact data to PDF

• Settings page 

• User specific data + share data with other users

• Better UI design + theme selection

• Combine logging/registration with home page


## 🛠️ Installation

• Clone this repository.

• Install modules from requirements.txt in **contactbookapi** directory.

```bash
pip install -r requirements.txt
```

• Install modules using npm install in **contactbook** directory.

```bash
npm install
```


## 🚀 Run 

• First change SECRET_KEY in **contactbookapi** settings.


• **contactbookapi** directory:

```bash
python manage.py runserver
```

• **contactbook** directory:

```bash
npm start
```


## ❓ Usage

• **localhost:8000** - Django REST API

• **localhost:8000/accounts/login** & **/register** - Django login and registration

• **localhost:3000/home** - ContactBook main page
