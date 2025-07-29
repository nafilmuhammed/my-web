<img src= "demo.png">

![Forks](https://img.shields.io/github/forks/Jock3r99/Joker-Portfolio)
![GitHub stars](https://img.shields.io/github/stars/Jock3r99/Joker-Portfolio)
![License](https://img.shields.io/github/license/Jock3r99/Joker-Portfolio)
![Size](https://img.shields.io/github/repo-size/Jock3r99/Joker-Portfolio)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/discord.py)

# Joker Portfolio
### [Demo](https://Jok3r.vercel.app/)
> A Joker theme portfolio to share your skills and projects around people!

## Features
  * Easy to run
  * Includes admin page
  * No external keys needed
  * portfolio.config.json File So You Dont Need To Edit The Code
  * Clean and smooth Design
  * The website is responsive for PC/Tablet and Mobile
  * More Updates In Future
### Requirements
  * Python +3.8V
  * Django
  * Virtualenv
### Setup
 1. Clone the repository:
 ```bash
git clone https://github.com/Jock3r99/Joker-Portfolio.git
 ```
 2. Navigate to the project directory:
```bash
 cd 'Joker-Portfolio'
```
 3. Create and activate a new virtual environment:
```bash
 python -m venv env
 source env/Scripts/activate
```
  4. Install the project dependencies:
 ```bash
  cd 'Joker-Portfolio'
  pip install -r requirements.txt
 ```

 5. Edit the portfolio config:
```json
  {
    "Config": {
      "name": "your name",
      "country": "your country",
      "avatar": "your avtar url",
      "introduction": "",
      "links": {
        "github": "https://github.com/",
        "reddit": "https://reddit.com/",
        "twitter": "https://twitter.com/",
        "discord": "https://discord.com/"
      },
      "contact": {
        "email": "example@gmail.com",
        "discord": "username",
        "webhook_url": "discord webhook url"
      }
    }
  }

```
 6. Collect static files:
```bash
python manage.py collectstatic
```
 7. Create the database tables:
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py migrate --run-syncdb
```
 8. Create admin super user:
```bash
python manage.py createsuperuser
```
 9. Running the project
```bash
python manage.py runserver
```
10. Access the admin panel:
```
Go to /admin. Write your super username and password and
you will be able to access the admin panel. You can add your projects and
jobs there.
```

## Deployment Tutorial:
* [Click Me](https://github.com/Jock3r99/Joker-Portfolio/tree/main/deployment)


## Important:
#### When using my work, you must accept the terms of use otherwise i will use legal actions.
- Selling this website or any of its elements is prohibited.
- Claiming ownership of this website is not permitted.
- Altering the credit notice ("Developed with ❤️ by Jok3R") in the footer is not allowed.

## Editing:
```
- This project (and the source code here) might not be easy to edit for inexperienced programmers.
The main purpose of having the source public is to show the capabilities of the libraries, to allow
others to understand how the code works, and to allow those knowledgeable about django development
to contribute. There are many requirements and dependencies required to edit and compile it, and
there will not be support provided for people looking to make changes on their own. If you choose
to make edits, please do so in accordance with the MIT License.
```

## Donation:
If you love the portfolio, feel free to support me:

<a href='https://ko-fi.com/jock3r9'><img src='https://ko-fi.com/img/githubbutton_sm.svg' height="27px"/></a>

