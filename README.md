
# ⛳ Django-Video Conferencing Web App

The main purpose of video conferencing is to enable face-to-face communication between two or more people in different locations.




## 🎥 Demo

Youtube Video Link with Explanation [Click here...](https://youtu.be/6dKbLnG0Or4) 

![Logo](https://media.giphy.com/media/l1WR5hEkNhESWpY6td/giphy-downsized-large.gif)

## 👨 Author

- [@saikumarreddykorsapati-source](https://github.com/saikumarreddykorsapati-source)



## 💻 Tech Stack

**Frontend -** Html, Css, Js, Bootstrap

**Backend -** Python, Django

**Database -** Sqlite-3

**Version Control -** GitHub

**Deployment -** Heroku

## 📚 Documentation

(HLD) High Level Design : [Link - Click here...](https://github.com/saikumarreddykorsapati-source/DSM_Challenge_4/blob/main/Documents/Django_VC_HLD_1.0v.pdf)

(LLD) Low Level Design : [Link - Click here...](https://github.com/saikumarreddykorsapati-source/DSM_Challenge_4/blob/main/Documents/Django_VC_LLD_V01.pdf)

Wireframe : [Link - Click here...](https://github.com/saikumarreddykorsapati-source/DSM_Challenge_4/blob/main/Documents/Wireframe_Doc_DjangoVideoConderenceWebApp_v01.pdf)

Architecture : [Link - Click here...](https://github.com/saikumarreddykorsapati-source/DSM_Challenge_4/blob/main/Documents/Django_VC_Architecture.pdf)

(DPR) Detailed Project Report : [Link - Click here...](https://docs.google.com/presentation/d/1bszo3bBnD2KpTYfb9tTakYQ0zl4LTLKLl3qWMoJZ224/edit?usp=sharing)

Deployed App Demo : [Link - Click here...](https://django-video-conference-app.herokuapp.com)

[Linked in Post](https://www.linkedin.com/posts/sai-kumar-reddy-korsapati_django-python-challenge4-activity-6900547642061934592-VTjA)

## 📎 Features

- Video
- Audio
- Screen Share
- Start / Stop Controls


## 📌 Installation

Install my-project in following way :

Download Zip File, then 

```bash 
cd <filename>
```
\# creating a virtual environment
```bash 
python -m venv venv 
```
\# activating virtual environment
```bash
venv\Scripts\activate.bat

```
\# upgrading pip command
```bash
python -m pip install --upgrade pip

```
\# command to install everything mentioned in requirements file
```bash  
pip install -r requirements.txt
```
OR

\# installing django latest version
```bash  
pip install Django==4.0.2
```
\# command to check version of Django
```bash 
python -m django --version
```

\# to run our app
```bash 
python manage.py runserver
```
Note : click on Ctrl+C to quit server


\# if you get some migration issues warning run this
```bash 
python manage.py migrate
```
\# create a super user to access admin portal
```bash 
python manage.py createsuperuser
```
\# command to change password for superuser
```bash 
python manage.py changepassword <user_name>
```
command to create a fresh project

\# creaing django project using django admin
```bash 
django-admin startproject myapp
```
\# to start app
```bash 
python manage.py startapp chat
```
 

 
 
 






## 💾 Deployment

To deploy this project in heroku refer [link...](https://studygyaan.com/django/django-everywhere-host-your-django-app-for-free-on-heroku)



## ⌛ FAQ

#### 1) How users can join the room?

Once host publish the room, using that room name users can join.

#### 2) Which framework is used to build this app?

Django Framework is used.

#### 3) How users are managed?
Using Django Admin we can manage the users.

#### 4) Is this app secured ?
Yes, Django provides Cross site scripting (XSS) protection, Cross site request forgery (CSRF) protection, SQL injection protection, Clickjacking protection, SSL/HTTPS, Host header validation etc.,

