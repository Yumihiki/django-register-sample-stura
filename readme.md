mkdir register
cd register

python3 -m venv myvenv
source myvenv/bin/activate

python -m pip install --upgrade pip

touch requirements.txt
open requirements.txt
Django~=2.2.4 と記載

pip install -r requirements.txt

django-admin startproject project . 

python manage.py startapp register

書いてあることが終わったら

python manage.py makemigrations register

python manage.py runserver
