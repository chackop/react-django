```shell
pip3 install virtualenv
virtualenv --python=python3 env
source env/bin/activate
pip install -r requirements.txt

# Django
cd demo
python manage.py migrate
python manage.py test
python manage.py runserver
```