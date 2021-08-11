# Python_django_Web

 #### The backend of this website lies in python-django

 #### In order to run this site in your local machine, follow the steps below:

### a) Install python and add it to path
### b) Create a virtual environment (open cmd/ terminal and type the command below): 

       *  $ pip install virtualenv
    
### b)Test your installation:
   * $ virtualenv --version
  
### c) Create your own virtual environment
       * $ virtualenv <name of the environment>
  
### d) cd to the Virtual environment created above

       * cd Scripts
       * type activate, the press the tab key

### d) Press enter, the environment will be activated.
      * (myenv)> that will be the look of the activated virtual env

      * cd to the project directory i.e where the manage.py file is located then:
### e) Install all the dependancies in the requirements.txt
    * pip install -r requirements.txt 

   * That command will install all the modules contained in my project

### f) Finally: while in the root directory Run :
      *  python manage.py runserver
