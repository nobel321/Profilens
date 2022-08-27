# TKS-Web-Profile
This is an open source TKS web dev project for sharing profiles.

# First Timers

ensure you have git installed in your terminal.

run the following command to clone the project

```
git clone https://github.com/nobel321/TKS-Web-Dev.git
```

if your not already in the project once it is cloned, enter into it and open it in your preffered development environment


# Project Setup
python version: 3.7 (any version above 3 should be okay)
node version: 14 (16 should be okay too)




## Backend Setup

set up a new terminal and make sure your currently in the TKS-WEB-DEV/backend folder

### create a virtual environment (FIRST TIMERS ONLY):

```
pip3 install pipenv
```
```
pipenv shell
```

install django:

```
pipenv install django
```
```
pipenv install djangorestframework django-cors-headers
```


run the server with:

```
python manage.py runserver
```

recommended:

run ``` python manage.py migrate ``` before running the backend server if there are any pending migrations

## Frontend Setup

in another terminal, navigate to the frontend folder

### install packages (FIRST TIMERS ONLY -- unless new packages have been added by the frontend team):

```
npm i
```

run the server:

```
npm start
```

# Git help sheet

## making a branch

### creating a new branch
make sure your on the main branch first for creating a new branch
```
git checkout -b branchname
```

### switching to a branch
```
git checkout branchname
```

### pulling from main/a branch
```
git fetch origin branchname
```




