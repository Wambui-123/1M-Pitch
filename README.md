# 1M-Pitch
## Author
#### Yvonne Muthui
## Description
#### A flask application that requires users to create an account and login before submiting a pitch or viewing other pitches posted by other users. You can also leave comments and vote on them as you wish.
## Installation / Setup instruction
## Cloning
* On your terminal, run the following commands:
* $ git clone https://github.com/Kisavi/One-Minute-Pitch.git
* $ cd One-Minute-Pitch
* Create a virtual environment $ pv -m venv --without-pip virtual
* Activate the virtual environment $ source virtual/bin/activate
* Install Dependancies $ pip install -r requirements.txt
* Inside your root directory create a new file ```start.sh``` and add the following:
* ```export MAIL_USERNAME=<your email address>```
* ```export MAIL_PASSWORD=<your password>```
* ```python(version) manage.py server```
* Run chmod a+x start.sh  
* Run the application $ ./start.sh