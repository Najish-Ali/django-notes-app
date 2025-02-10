# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.

## Preview
![Notes App UI](https://raw.githubusercontent.com/Najish-Ali/django-notes-app/main/image_2025-02-04_163452050.png)  <!-- Replace with actual image URL -->

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
   ```sh
   git clone https://github.com/Najish-Ali/django-notes-app.git `

1.  Build the app

    sh

    CopyEdit

    `docker build -t notes-app .`

2.  Run the app

    sh

    CopyEdit

    `docker run -d -p 8000:8000 notes-app:latest`

Nginx
-----

Install Nginx reverse proxy to make this application available.

sh

CopyEdit

`sudo apt-get update
sudo apt install nginx`

yaml

CopyEdit

 `---
### **3. Commit and Push the Changes**
After modifying the README file, commit and push the changes:

```sh
git add README.md
git commit -m "Added app preview image to README"
git push origin main`
