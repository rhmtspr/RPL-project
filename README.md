# RPL-project

### How to run the program
1. create virtual environment.
2. open the virtual environment.
3. install all necessary packages.
```
pip install -r requirements.txt
```
3. create databases in phpmyadmin, the name should be the same as in the settings.py (car_rental).
4. run mysql and apache in xampp.
5. make migrations
```
py manage.py makemigrations
```
7. migrate
```
py manage.py migrate
```
