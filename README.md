Django project to GUI/Web-app sftp service running on the same Linux box (Fedora/RedHat for now).

$ mkdir sftp_project
$ cd sftp_project
$ pipenv shell
$ pipenv install django
$ django-admin startproject config .      <-- Make sure to end the line with a dot
$ python manage.py startapp sftp
