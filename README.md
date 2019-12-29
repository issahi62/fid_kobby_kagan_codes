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

Create Merge Request using GitHub.

## TODOLIST  
- what features to add?
- created a form to add items to the data_base. 
