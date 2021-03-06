<p align="center">
  <a href="https://github.com/monsij/ho1/blob/master/pro1/badge.png">
    <img src="https://github.com/monsij/ho1/blob/master/pro1/badge.png"
         alt="Gitter">
  </a>
  <h4 align="center">An Django based web-app exclusively for NIT Durgapur</h4>
</p>
<p align="center">
  •
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#contribution">Contribution</a> •
  <a href="#contributors">Contributors</a> •
  <a href="#communication">Communication</a> •
  <a href="#license">License</a> •
  <a href="#credits">Credits</a> •
  <a href="#KWoC">KWoC</a> •
</p>

[![Build Status](https://travis-ci.com/monsij/StudentPortal.svg?branch=master)](https://travis-ci.com/monsij/StudentPortal)
[![CodeFactor](https://www.codefactor.io/repository/github/monsij/studentportal/badge)](https://www.codefactor.io/repository/github/monsij/studentportal)
[![codecov](https://codecov.io/gh/monsij/StudentPortal/branch/master/graph/badge.svg)](https://codecov.io/gh/monsij/StudentPortal)
[![Report](https://img.shields.io/badge/status-pre--release-green.svg)]
[![License](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/monsij/StudentPortal/)
[![django1.10](https://img.shields.io/badge/django-2.0-brightgreen.svg)](https://www.djangoproject.com)
[![Maintainability](https://api.codeclimate.com/v1/badges/dc8e2c31895c72594f4c/maintainability)](https://codeclimate.com/github/monsij/StudentPortal/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/dc8e2c31895c72594f4c/test_coverage)](https://codeclimate.com/github/monsij/StudentPortal/test_coverage)
[![Heroku](https://heroku-badge.herokuapp.com/?app=heroku-badge)]
[![Gitter](https://img.shields.io/gitter/room/NIT-DGPortal/Lobby.svg?style=flat-square)](https://gitter.im/NIT-DGPortal-main/Lobby)
[![HitCount](http://hits.dwyl.com/monsij/StudentPortal.svg)](http://hits.dwyl.com/monsij/StudentPortal)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/monsij)
## KWoC
![KWoC](https://i.ibb.co/CwBBGYv/kwoc1.png)
We are more than excited to be a part of [Kharagpur Winter of Code](https://kwoc.kossiitkgp.org/). If you're contributing as a part of this program, we will be having a special mention of such contributors in the repo. Once again, Happy Coding
## Key Features
<ul>
  <li> Based on Python</li>
  <li> Powered by Django</li>
  <li> Access secured only to registered students </li>
  <li> Study materials, placement/internship news, contacts all in here</li>
  <li> Open to contribution :v:</li>
</ul>
  
## How to Use

* Start off by forking this repository and cloning it to get your local copy.

  ```bash
  > git clone https://github.com/NIT-DGPortal/portal-main.git 
  ```

* If you prefer a virtual-environment ([pipenv](https://pipenv.readthedocs.io/) suggested) you should have pip and pipenv installed.

  ```bash
  > sudo apt install python3-pip python3-dev
    pip3 install --user pipenv 
  ```
  
  Add pipenv to PATH
  
  ```bash
  echo "PATH=$HOME/.local/bin:$PATH" >> ~/.bashrc
  source ~/.bashrc
  ```

* Navigate to your local directory and initiate a python 3 environment.
  
  ```bash
  > pipenv --three 
  ```
  
  
* Activate your virtual environment.
  
  ```bash
  > pipenv shell
  ```

  Now install all requisites in requirements.txt .

  ```bash
  cd pro1
  pip install -r requirements.txt
  ```
  where x is everything inside requirements.txt

  Here is what your Pipfile will appear when you're ready to go

  ```bash
  django = "*"
  gunicorn = "*" 
  django-heroku = "*"
  django-crispy-forms = "*"
  django-registration = "*"
  requests = "*"
  ```
  

* Configure environment variable using **python-decople**

* Navigate to pro1 and rename .env.example to .env

* Run the following command in your terminal.

  ```bash
  > python manage.py runserver
  ```
  
* Navigate to http://localhost:8000 to see it in action.


## Contribution

Head to [contribution guidelines](https://github.com/monsij/StudentPortal/wiki/Contribution-Guidelines) to know more about how you can help us to improve.

## Contributors

# ✨ Recognising all people who not only pushed code ✨
| [<img src="https://avatars2.githubusercontent.com/u/23289387?s=400&v=4" width="100px;"/><br /><sub><b>Monsij Biswal</b></sub>](https://github.com/monsij)<br />[👀](# "Reviewed Pull Requests") [📢](# "Talks") [💻](# "Code")| [<img src="https://avatars0.githubusercontent.com/u/25405293?s=400&v=4" width="100px;"/><br /><sub><b>Satyajit Das</b></sub>](https://github.com/r3trd)<br />[👀](# "Reviewed Pull Requests") [📢](# "Talks") [💻](# "Code")| [<img src="https://avatars3.githubusercontent.com/u/20069594?s=400&v=4" width="100px;"/><br /><sub><b>Vivek Modi</b></sub>](https://github.com/modihere)<br />[💡](# "Ideas")| [<img src="https://avatars2.githubusercontent.com/u/37576387?s=400&v=4" width="100px;"/><br /><sub><b>Hariom Verma</b></sub>](https://github.com/harry-hov)<br />[👀](# "Reviewed Pull Requests") [💻](# "Code") [📢](# "Talks")| [<img src="https://avatars2.githubusercontent.com/u/22504975?s=400&v=4" width="100px;"/><br /><sub><b>Nikhil Gupta</b></sub>](https://github.com/nguptaa)<br />[💻](# "Code") [📢](# "Talks")| [<img src="https://avatars0.githubusercontent.com/u/35505246?s=400&v=4" width="100px;"/><br /><sub><b>Tiyas Dey</b></sub>](https://github.com/Tiyas-13)<br />[💻](# "Code") [📢](# "Talks")| [<img src="https://avatars2.githubusercontent.com/u/30266744?s=400&v=4" width="100px;"/><br /><sub><b>Gopa Vasanth</b></sub>](https://github.com/gopavasanth)<br />[💻](# "Code") [📢](# "Talks")
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [<img src="https://avatars1.githubusercontent.com/u/31796326?s=400&v=4" width="100px;"/><br /><sub><b>Prashant Sharma</b></sub>](https://github.com/gutsytechster)<br />[💻](# "Code") [📢](# "Talks")| [<img src="https://avatars2.githubusercontent.com/u/32306847?s=400&v=4" width="100px;"/><br /><sub><b>Yashvi Patel</b></sub>](https://github.com/YashviP)<br />[💻](# "Code") [📢](# "Talks")| [<img src="https://avatars2.githubusercontent.com/u/45662739?s=400&v=4" width="100px;"/><br /><sub><b>Aman Singh Kushwah</b></sub>](https://github.com/Aman8817)<br />[💻](# "Code") [📢](# "Talks")| [<img src="https://avatars1.githubusercontent.com/u/32234113?s=400&v=4" width="100px;"/><br /><sub><b>Bhanu Prakash Poluparthi</b></sub>](https://github.com/BhanuPrakashNani)<br />[💻](# "Code") [📢](# "Talks")| [<img src="https://avatars0.githubusercontent.com/u/33262874?s=400&v=4" width="100px;"/><br /><sub><b>Arpit Agrawal</b></sub>](https://github.com/arpit3018)<br />[💻](# "Code") [📢](# "Talks")| [<img src="https://avatars2.githubusercontent.com/u/30580217?s=400&v=4" width="100px;"/><br /><sub><b>Akash Giri</b></sub>](https://github.com/akashgiricse)<br />[💻](# "Code") [📢](# "Talks")| [<img src="https://avatars0.githubusercontent.com/u/36023503?s=400&v=4" width="100px;"/><br /><sub><b>Rahul Otwani</b></sub>](https://github.com/rahulotwani)<br />[💻](# "Code") [📢](# "Talks")
| [<img src="https://avatars3.githubusercontent.com/u/34571079?s=400&v=4" width="100px;"/><br /><sub><b>Nishi Chauhan</b></sub>](https://github.com/chauhannishh)<br />[💻](# "Code")[📢](# "Talks")| [<img src="https://avatars3.githubusercontent.com/u/42097982?s=400&v=44" width="100px;"/><br /><sub><b>Uday Mewada</b></sub>](https://github.com/udaymewada)<br />[💻](# "Code")[📢](# "Talks")




## Communication

All related communications take place [here](https://gitter.im/NIT-DGPortal-main/Lobby)
## License

Exactly putting we want it to be simple are permissive. Interested contributors are heartedly welcomed. :blush: 
## Credits

* The initial version was made in just a span of 27 hours, yes it was that short :sparkles:
* Authentication and Profile credits to [Satyajit Das](https://github.com/r3trd)
* CSS, Bootstrap Rendering realized by [Anoop Kumar](https://github.com/anoop1311)
* General codebase and framework by [Monsij Biswal](https://github.com/monsij)

For more info head to [Wiki](https://github.com/monsij/StudentPortal/wiki) for more information

Cheers :fun:
