# informations
install django project
## local
mkdir Desktop/education && cd Desktop/education/
git init
python3 -m virtualenv .
git status
git add .
git commit -m "installed virtual enviroment"
source bin/activate
pip install django
pip freeze
git status
git add .
git commit -m "Django version 2 installed"
mkdir src && cd src
django-admin startproject mysite .
ls
python manage.py startapp user
python manage.py startapp exam
ls
cd ..
git add .
git commit -m "New Project and two apps created"
## git Hub
#### New repo name : school-project

git remote add origin https://github.com/sweetlearn/school-project.git
git remote -v
git push -u origin master

> refrshe github repo

