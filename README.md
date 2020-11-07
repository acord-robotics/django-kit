# django kit

![](https://travis-ci.org/acord-robotics/django-kit.svg?branch=main)

 A kit for people who want to create sites with Django, with different starting templates & apps, by Signal Kinetics // Acord Software. If you have a new django project and want to get it set up quickly, with minimal fuss but all the benefits of AC0/RD's extensions, clone this repo. 

The following Python modules/libraries are (currently) used in this repo:

| Module                                                                                     | Publisher     |
| ------------------------------------------------------------------------------------------ |:-------------:|
| [Django](https://www.djangoproject.com/)                                                   | DjangoProject |
| [VENV](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) | Python        |

See the [Timeline](#timeline) to see what changes we've made to this repo, if you want to know what version of each library we're using, that's the place to go.



# Install Guide

## Requirements

* Python 3 

* Pip for Python

Download this repository. As an example, we'll download it to `users/user/django-kit` on a Windows device. Open the terminal of your choice (for example, the Windows Command Prompt - which by default opens in `users/user`) and enter the following commands:

`cd django-kit` - This **changes the directory** to be inside the folder that you've downloaded this repository to.

`pip install venv` - Installs the virtual environment extension to your device

`venv\Scripts\activate.bat` - for windows devices only. Activate your virtual environment. It will customize your setup for your folder.

`pip install django` - even if you've already installed Django on your device you'll want to install the library IN THIS virtual environment as well.

`python manage.py runserver` - run the `runserver` command from `manage.py` using Python to run the server. Go to `http://localhost:8000` to see your install.

Follow the above instructions to set up your first Django project as well. If you're using this folder, the blog is located at `http://localhost:8000/blog`



# Apps

Blog - `/blog/`

Projects - `/projects` 

# Timeline

## 7th November 2020

* Created repository

* Libraries:
  
  * Venv - latest version as of 7/11/2020
  
  * Django - latest version as of 7/11/2020
