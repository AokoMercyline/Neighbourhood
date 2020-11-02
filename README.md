# Neighbourhood

## Author
* By Aoko Mercyline

## Description
This is web application(neighbourhood) that allows user to be in the loop about everything happening in their neighborhood. From contact information of different handyman to meeting announcements or even alerts. User is able to sign up and be able to view different neighbourhoods,join,leave and view details for their neighbourhood.


## Feature
* User is able to sign up and login the application
* User is able to view different neighbourhoods and join
* User can create or upload post
* User is able to edit their profile
* User is able to fInd list of different bussiness in their neighbour
* Create posts that will be visible to everyone in their neighbourhood
* User is able to chnage their neighbourhood

## Behaviour Driven Development
| Input | Output|
|-------| ------|
| User sign up to for them see the available hoods | Users sees the posted neighbourhoods |
| Click Join Neighbourhood | Close neighbourhood or Explore |
| User explores | Sees the bussiness site with |
| User add bussines | Available site |
| User add new post | New post

## Setup and Installations

* Get the project
- Clone this repository
    https://github.com/AokoMercyline/Neighbourhood

* Install and activate Virtual
- python3 -m venv virtual
- source virtual/bin/activate

* Navigate into the folder
- cd Hoods

* Install Dependencies
- pip install -r requirements.txt

* Setup Database
    - SetUp your database User,Password, Host then make migrations:
    - python manage.py makemigrations
    - python manage.py migrate

* Run application
    - python manage.py runserver

* Testing the application
    - python manage.py test

## Technology Used

* Python3.8
* Django 3.2.1
* Heroku

## KNown Bugs
* There are no known bugs at the moment

## Contact Information

Any question or contributions,please mail at aokomercyline34@gmail.com

## Copyright and License

The project is under[MIT license](/blob/master/LICENSE)
Copyright &copy; 2020.All rigths reserved

