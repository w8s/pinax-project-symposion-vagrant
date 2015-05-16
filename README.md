pinax-project-symposion
=====================

a starter project demonstarting a minimal symposion instance


## Usage

    django-admin.py startproject --extension=py,json --template=https://github.com/w8s/pinax-project-symposion-vagrant/zipball/master <project_name>

## Getting Started

From the command line in the directory where you want to create your Django project run:

1. `django-admin.py startproject --extension=py,json --template=https://github.com/w8s/pinax-project-symposion-vagrant/zipball/master --name Vagrantfile <project_name>`
2. `cd project_name`
3. `vagrant up`
4. `vagrant ssh`
5. From within the vagrant box command line: `python manage.py runserver 0.0.0.0:8000`

## Dependencies

[Vagrant](https://www.vagrantup.com) and [Django](https://www.djangoproject.com/) must be installed on the host machine.
