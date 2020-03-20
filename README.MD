## Building Complete Django Blog

#### 1. Create django project and app

#### 2. Create model

    > - (env) λ pip3 install pillow
    > - (env) λ pip3 install django-ckeditor

    > - (env) λ python manage.py makemigrations
    > - Migrations for 'base':
    > -   apps\base\migrations\0001_initial.py
    > -     - Create model Autor
    > -     - Create model Categoria
    > -     - Create model Contacto
    > -     - Create model RedesSociales
    > -     - Create model Suscriptor
    > -     - Create model Web
    > -     - Create model Post
    > - (env) λ python manage.py migrate
    > - (env) λ python manage.py createsuperuser

    > - new file:   README.MD
    > - modified:   _core/config/__pycache__/base.cpython-37.pyc
    > - modified:   _core/config/base.py
    > - modified:   _core/db.sqlite3
    > - modified:   apps/base/__pycache__/models.cpython-37.pyc
    > - new file:   apps/base/migrations/0001_initial.py
    > - new file:   apps/base/migrations/__pycache__/0001_initial.cpython-37.pyc
    > - modified:   apps/base/models.py

#### 2. Add model to admin

    > - modified:   apps/base/__pycache__/admin.cpython-37.pyc
    > - modified:   apps/base/admin.py

#### 3. Add images and posts

    > - modified:   _core/__pycache__/urls.cpython-37.pyc
    > - modified:   _core/config/__pycache__/development.cpython-37.pyc
    > - modified:   _core/config/development.py
    > - modified:   _core/db.sqlite3
    > - new file:   _core/media/categoria/game.jpg
    > - new file:   _core/media/categoria/technology.jpg
    > - new file:   _core/media/imagenes/10.JPG
    > - new file:   _core/media/imagenes/14.JPG
    > - new file:   _core/media/imagenes/sukardi_rai.JPG
    > - new file:   _core/media/imagenes/sukardi_rai8.JPG
    > - modified:   _core/urls.py
