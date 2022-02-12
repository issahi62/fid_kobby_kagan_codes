# fid_kobby_kagan_codes
## Installation
run commands to install required libraries and to run app:  
Install python3 first if not in the machine.  
Install Django in addition to its requirements.txt


then run:  
Get working on code:
```
git clone https://github.com/issahi62/fid_kobby_kagan_codes.git  
```

### Using `virtualenv`
Setup python 3 virtual environment

```
sudo apt-get install python-pip
pip install virtualenv
virtualenv -p python3 env 
source env/bin/activate
pip install -r requirements.txt  
```
autopep8==1.4.4
certifi==2019.3.9
chardet==3.0.4
defusedxml==0.6.0
Django==2.2.20
django-allauth==0.39.1
django-countries==5.3.3
django-crispy-forms==1.7.2
django-debug-toolbar==1.10.1
idna==2.8
oauthlib==3.0.1
pep8==1.7.1
Pillow==8.1.1
pycodestyle==2.5.0
python-decouple==3.1
python3-openid==3.1.0
pytz==2018.5
requests==2.21.0
requests-oauthlib==1.2.0
sqlparse==0.2.4
stripe==2.27.0
urllib3==1.24.2


## Run
Setup environment variables
```
export SECRET_KEY=something
python3 manage.py runserver  
```

## Contribute

Follow the following branching convention for easy identification of change

1. fix/fix-name
2. feat/feature-name

To add/push changes to github:  
run from console/terminal:

### Create Merge Request

```
git checkout -b feat/your-feature
git add .  
git commit -m "change message here"  
git push --set-upstream origin fix/your-feature
```

### DATABASE 
```
python3 manage.py makemigrations 
python3 manage.py migrate 
python3 createsuperuser
```
Create Merge Request using GitHub.

## TODOLIST  
- what features to add?
- created a form to add items to the data_base. 
