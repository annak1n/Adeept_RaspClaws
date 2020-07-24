# Hexapod

o) Check python3 version

python3 -V
o) Install gpiozero

sudo apt install python3-gpiozero
o) Install pip and virtualenv

sudo apt install python3-pip
sudo pip3 install virtualenv
o) Create virtualenv

virtualenv -p python3 venv
o) Activate virtualenv

source venv/bin/activate
When the command completes, your current terminal program will be configured to use your virtual environment for activities related to Python 3. Given that, install the Python dependencies for your GPIO Zero project into your virtual environment:

pip install -r requirements.txt
or
python setup.py
