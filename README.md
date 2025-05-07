
## 🐍 Flask App: app.py
ready with the application 

## 🎨 HTML Template: templates/index.html
Create a folder named templates/ in the same directory as app.py, and inside it place index.html:
## 🐳 Dockerfile


## Demo

Link to the dockerfile

https://github.com/wasimm267/docker-demo/blob/main/dockerfile
## Installation

🚀 How to Build and Run
Save all the files in one directory.

Open terminal in that directory.

Build the Docker image:

```bash
  docker build -t flask-success-app .
docker run -d -p 8080:80 --name flask-app flask-success-app

```
Open your browser and go to:
👉 http://localhost:8080 (change it to your machine,s ip if required or running on any cloud )

You should see a styled message: "✅ Successfully Done!"

make sure to allow the port 8080

    