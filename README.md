# 1M-Pitch
## Author
#### Yvonne Muthui
## Description
#### A flask application that requires users to create an account and login before submiting a pitch or viewing other pitches posted by other users. You can also leave comments and vote on them as you wish.
## [Demo](https://pitchminute123456.herokuapp.com/login?next=%2F) click to view
## Installation / Setup instruction
## Cloning
* On your terminal, run the following commands:
* $ git clone git@github.com:Wambui-123/1M-Pitch.git
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
## Development
#### Want to make a contribution to enhance an existing module or fix a bug? Great!
* Fork the repo
* Create a new branch (git checkout -b improve-feature)
* Make the appropriate changes in the files
* Add changes to reflect the changes made
* Commit your changes (git commit -am 'Improve feature')
* Push to the branch (git push origin improve-feature)
* Create a Pull Request
## Technology Used
* python3.8
* flask
* Sqlite
## Known Bugs
#### 
If you find a bug on the website or its not working as expected, please feel free so send me an email @yvonnewambui28@gmail.com
## Contact Information
* For any inqueries feel free to write to me yvonnewambui28@gmail.com
## Licence
* MIT License
* Copyright (c) 2022 Yvonne Muthui
