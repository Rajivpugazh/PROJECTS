'''Always activate the VE before working in the project which involves the VE file / also to install new packages etc'''



# to install venv(virtual environment)
1.open the folder path in cmd and use command (python -m venv venv)
#this code creates a new directory called venv in the folder

# to activate venv(virtual environment)
2.(venv\Scripts\activate)
#this code activates the virtual environment so now we can installs the required packages / VE is used because it isolates the files we installed in VE file from other folders so it does'nt mix/affect other projects.

# installing packages;
3. (pip install Flask Flask-Bcrypt pymongo)
# this code installs the required packages like:

 FLASK# a python framework used in website creation to connect frontend and backend [Main uses:Creating web pages,Handling web requests (like when you submit a form),Managing routes (URLs) in your web application,
Rendering templates (displaying HTML)] ,FLASK-BCRYPT an extension of flask used to Securely hashing passwords before storing them in a database # secure hashing- means trabsforming password into unreadable,fixedlength codes before storing in database.

# to deactivate VE:
4.(deactivate)
#use this line in VE running cmd to stop VE.

#creating a requirements.txt file
5.(pip freeze > requirements.txt) 
#stores the information about the requirments in a txt file used for installing the already installed packages in another folder [moving or copy pasting it in another folder]

#To install from a requirements.txt file (useful when setting up the project on a new machine):
6.(pip install -r requirements.txt)
#this code used to install the files from the requirments.txt file .

