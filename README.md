# FlaskTutorialCRUD
A simple CRUD example of Flask (A web Python framework)
# Tutorial from (Learn Flask for Python - Full Tutorial)
https://www.youtube.com/watch?v=Z1RJmh_OqeA
# Link deployed (Heroku)
https://flaskpracticecarlos.herokuapp.com/

# Preparing enviroment
	$ pip3 install virtualenv
	$ virtualenv myenv
	$ source myvenv/bin/activate #activate enviroment
# Comando para instalar flask
	$ pip3 install flask flask-sqlalchemy

# Create main file app.py and run it with
	$ python3 app.py
# For create a database
	$ python3
	$ from app import db
	$ db.create_all()
	$ exit()
	
# Generar lista de requerimientos
	$ pip3 freeze > requirements.txt

# Install CLI HEROKU
https://devcenter.heroku.com/articles/heroku-cli

FOR LINUX IS:	
	$ sudo snap install --classic heroku
	
# Crear proyecto en Heroku
	$ heroku login # usa tus credenciales
	$ pip3 install gunicorn
	$ touch Procfile # para inicializar el servidor 
	$ git init # inicializa repositorio
	$ git add .
	$ git commit -m "init app"
	$ heroku create flaskpracticecarlos
	$ git remote -v
	$ git push heroku master
	
