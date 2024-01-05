# blog

## Setup
### setup venv
```shell
python3 -m venv venv
```
### active venv
Windows
```powershell
.\venv\Scripts\activate
```
Linux or MacOS
```shell
source venv/bin/activate
```
### install django
```shell
pip install django
```
### Apply migrations
```shell
python manage.py migrate
```
### Create admin account
```shell
python manage.py createsuperuser
```
input all admin info
### Run server
```shell
python manage.py runserver
```