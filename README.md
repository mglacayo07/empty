# Create your TurboGears 2.3 project 

Download this project and change the name, this way you could have your own project in TurboGears 
# Technologires
* TurboGears 2.3
* Virtualenv
* Python 3.5
# Quick Guide 

1. Clone project 
2. Create new virtualenv with the requirements.txt <br>```mkvirtualenv --python=$p3 projectEnv```<br>``` sudo pip install -r requirements.txt```
3. Create new database empty
4. Edit `developer.ini` and `production.ini` files and change db connection with your user and password <br>```sqlalchemy.url = mysql://user:password@127.0.0.1/dbname``` 
5. Install dependences from the project into virtualenv <br>```pip install -e .```
6. Inicialize database <br>```gearbox setup-app -c development.ini```
7. Run your project <br>```gearbox serve -c development.ini --reload```

### Test User

User: manager
Password: managepass

# Preview
![https://github.com/mglacayo07/empty/blob/main/empty.png](https://github.com/mglacayo07/empty/blob/main/empty.png)
