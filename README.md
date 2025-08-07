# python-for-computational-genetics
Python learning for genomic data science

Install python
Install VS Code Editor
Insatll Git
Open Vs code or terminal then clone the repository on the specific folder by opening the terminal/command prompt and paste the path of repoistory like >>>git clone path name
go to that folder by using the command >>>cd name-of-folder
Setup up python environment for organizing python pakages for the projects. It is created by running this on terminal >>>python -m venv venv
The above command will create venv folder for your virtual environment.
For activating this virtual enviornment run command on terminal of windows >>venv\Scripts\activatein 
Then install some important pakages there by runing command >>>pip install numpy pandas matplotlib biopython jupyter

Then run there a command that will create a list of all installed libraries in your virtual python environment into a file called requirements.txt >>>pip freeze > requirements.txt
In future, whenever you install the any library or pakage in your virtual environment of python just run the previous command then it will record that library and their version used in a project for a record and later use. In later when you installed all these libraries again just run this command >>pip install -r requirements.txt 
