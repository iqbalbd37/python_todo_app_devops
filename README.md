# python_todo_app_devops

python3 app.py


Python todo app for CICD Project
=============================================
docker build -t todo-app .

docker run -dit -p 5000:5000 --name python todo-app
