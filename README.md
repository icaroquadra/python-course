# python-course
Python labs with Olist and Cinq

Install the python 3.7
Verify the version with the command:

python --version
python3 --version
python3.7 --version

Run the command to create your .venv file
python3 -m venv .venv  

(if it dont run ubuntu)
apt install python3-pip python3-setuptools python3.7-venv

Verify the new folder .venv

Run command to active the source
source .venv/bin/activate 

Verify the pip version
pip --version

version 19.03

Run the interative mod with the command
python

(to run for the first time the project example Djano_Training) {
  pip install -r requirements.txt
  python manage.py makemigrations
  python manage.py migrate
  python manage.py runserver
}
