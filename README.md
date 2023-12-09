# django_ecommerce

* Familar with models and admin
- Create folder and activate environment: py -m venv venv 
- Activate the virtual environment: venv\Scripts\activate
- Install Django: pip install django
- Start new project: django-admin startproject core .
 + manage.py allow to access django admin
- Build a new app: py manage.py startapp store
 + setting file in app store: declare the project that it depen on
- declare model in file models.py in app folder declare. -> run migrate
- config the media folder in core setting file:
- config the URL in core Url file
- Create super user
- Run server
* Testing -> Models
- Run python test: python manage.py test
- install coverage to management test: pip install coverage
- run command line:coverage run manage.py test
- Report:coverage report
- coverage run --omit='*/venv/*' manage.py test
- coverage html
* create url file in application
- config url in project file urls.py

====== Part 2 ===========
Ecommerce store session basket
1. Refactoring
2. Introducing session (optional)
3. Development (Add to basket, delete from basket, Update basket)
4. Testing