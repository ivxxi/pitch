#  Pitch

## Description
Pitch is an application allows users to submit their one minute pitches and other users will vote on them and leave comments to give their feedback. The pitches are organized by category.

## Author

* [**Crystal Alice**]

## Features

As a user of the web application you will be able to:

1. See all submitted pitches arranged in categories
2. Create an account
3. Log in
4. Add a pitch based on category
5. Upvote or downvote a pitch
6. Comment on a pitch
7. See comments posted on each individual pitch
8. Edit your profile i.e will be able to add a short bio about yourself and a profile picture

## Specifications
| Behavior            | Input                         | Output                        |
| ------------------- | ----------------------------- | ----------------------------- |
| View Product Pitches | Click on any category | Taken to the clicked category | Click on `Click Here To Post A Pitch` | Redirected to the login page | Signs In/ Signs Up |
| Click on `Click Here To Post A Pitch` | If logged in, display form to add a pitch | Redirected to the home page |
| Click upvote/ downvote button | Redirects to home page | Upvote/ downvote count changes | Click add comment button | Redirects to the comment page | Displays a comment form | Click on Sign Out | Redirects to the home page | Signs user out |
| Click on profile | Redirects to the profile page | User adds bio and profile picture |



## Getting started
### Prerequisites
* python3.6
* virtual environment
* pip

### Cloning
* In your terminal:

        $ git clone
        $ cd last-pitch

## Running the Application
* Install virtual environment using `$ python3.6 -m venv --without-pip virtual`
* Activate virtual environment using `$ source virtual/bin/activate`
* Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`
* Install all the dependencies from the requirements.txt file by running `pip3 install -r requirements.txt`
* Create a `start.sh` file in the root of the folder and add the following code:

        export MAIL_USERNAME=<your-email-address>
        export MAIL_PASSWORD=<your-email-password>
        export SECRET_KEY=<your-secret-key>

* To run the application, in your terminal:

        $ chmod a+x start.sh
        $ ./start.sh

## Testing the Application
* To run the tests for the class file:

        $ python3.6 manage.py server

## Technologies Used
* Python3.6
* Flask
* HTML
* Bootstrap

This application is developed using [Python3.6](https://www.python.org/doc/), [Flask](http://flask.palletsprojects.com/en/1.1.x/), [HTML](https://getbootstrap.com/) and [Bootstrap](https://getbootstrap.com/)


## Support and Team
Crystal Alice


### License

* LICENSED UNDER  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](license/MIT)
