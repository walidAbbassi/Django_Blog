# Django blog boostrap.
===================
## With Django 2.1.7
Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It’s free and open source.

## Quick start
```
Step 1: clone project
$ git clone https://github.com/walidAbbassi/Django_Blog.git
$ cd Django_Blog
Step 2: Create and enable virtual environment
$ virtualenv virtual_env
$ virtual_env\Scripts\activate
$ pip install -r requirements.txt
Step 3: collect
$ python manage.py collectstatic
Step 4: migrate
$ python manage.py makemigrations
$ python manage.py migrate
Step 5: run
$ ./manage.py runserver
```
```
default superuser name : admin
default superuser password : admin
```
```
Django_Blog
    ├───blog_Application 						==> Blog Application
    │   ├───migrations
    │   ├───static 							==> Static Directory Blog Application
    │   │   └───blog
    │   └───templates 							==> Templates Directory Blog Application
    │       ├───blog
    │       └───blog_Application
    ├───Django_Blog 							==> Blog Project
    ├───media 								==> Media Directory
    │   └───profile_pics
    ├───Screenshot
    ├───static 								==> Static Directory Project
    │   ├───admin
    │   ├───blog
    │   └───ckeditor
    └───users 								==> Users Application
        ├───migrations
        └───templates 							==> Templates Directory Users Application
            └───users
```
### References
* [Django documentation]
* [Django Tutorial]
* [template]

Screenshot site:
-------------
![Main blog1](https://github.com/walidAbbassi/Django_Blog/blob/master/Screenshot/Django_blog_1.PNG)

![Main blog2](https://github.com/walidAbbassi/Django_Blog/blob/master/Screenshot/Django_blog_2.PNG)

![Main blog3](https://github.com/walidAbbassi/Django_Blog/blob/master/Screenshot/Django_blog_3.PNG)

[Django documentation]:https://www.djangoproject.com
[Django Tutorial]:https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p
[template]:https://blackrockdigital.github.io/startbootstrap-clean-blog
