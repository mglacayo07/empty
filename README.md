# Create your TurboGears 2.3 project 

Download this project and change the name, this way you could have your own project in TurboGears 
# Technologires
* TurboGears 2.3
* Virtualenv
* Python
# Quick Guide 

1. Clone project
2. Create new virtualenv with the requirements.txt 
3. Create new database empty
4. Edit `developer.ini` and `production.ini` files and change  ```sqlalchemy.url = mysql://user:password@127.0.0.1/dbname``` with your user and password
5. Install dependences from the project into virtualenv ```pip install -e .```
6. Inicialize database ```gearbox setup-app -c development.ini```
7. Run your project ```gearbox setup-app -c development.ini --reload```

### Test User

User: manager
Password: managepass

# Preview
![https://github.com/mglacayo07/empty/blob/main/empty.png](https://github.com/mglacayo07/empty/blob/main/empty.png)
