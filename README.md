# Simple Notes App
This is a simple notes app built with React and Django.

## Flow Chart

![Flowchart](https://github.com/Amanlath1/django-notes-app-test-project/blob/main/flowchart1.png)

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/Amanlath1/django-notes-app-test-project
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`

## Website

[Project Live website](http://20.244.106.200:8000/)

