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

# Install CLI HEROKU
https://devcenter.heroku.com/articles/heroku-cli

FOR LINUX IS:
	
	$ sudo snap install --classic heroku
	
# Comando para instalar flask

	$ pip3 install flask flask-sqlalchemy
  
# Generar lista de requerimientos
	$ pip3 freeze > requirements.txt

# Crear proyecto en Heroku 
	$ heroku create flaskpracticecarlos
	$ git remote -v
	$ git push heroku master
