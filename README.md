# Template for Web App with Authentication

## Introduction
- Industry template for authentication with login, register, validation and the secrect (home) page. 
- Project is designed by Dr.Angela from [100 days of code](https://100daysofpython.dev/)
- Please note this is a single page login (which is all the user share the same resources)
- Take a look at [User-Banking-and-Expense-Analyst](https://github.com/jackyhuynh/User_Banking_and_Expense_Analyst) for multiple user with multiple database structure

### Encryption Level
```code
# | Level 1 : Server
# | Level 2 : Encryption (Password + Key) -> Cipher methods -> Ciphertext
# | Level 3 : Hasing (Password) -> HashFunction -> Hash
# | Level 4 : Salting (password + random_unique_salt) -> HashFunction -> Hash -> salt_round( x Round) x times -> New_Hash
```

## Structure:

#### Diagram:
<img src="https://github.com/jackyhuynh/web_app_with_authentication_template/blob/main/images/diagram.JPG">

#### Index Page:
- The home page allow user to login or register for a new user
<img src="https://github.com/jackyhuynh/web_app_with_authentication_template/blob/main/images/index.JPG">

#### Login Page:
- Login page allow user login the Home page.
<img src="https://github.com/jackyhuynh/web_app_with_authentication_template/blob/main/images/login.JPG">

#### Register Page:
- Register page allow user register for a new account and login the Home Page.
<img src="https://github.com/jackyhuynh/web_app_with_authentication_template/blob/main/images/register.JPG">

#### Home Page:
- Home page is where you store the information that you want to hide.
<img src="<img src="https://github.com/jackyhuynh/web_app_with_authentication_template/blob/main/images/home.JPG">">

## How password is hack:
- Compare the hash value with the hash table (self create)
- Hacking 101: Day 68 on [100 days of code](https://www.udemy.com/course/100-days-of-code)

## Technology
List of technology
- Python 
- Web App
- PyCharm IDE

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
What things you need to install the software and how to install them
- PyCharm Community IDE: Be More Productive: Save time while PyCharm takes care of the routine. Focus on the bigger things and embrace the keyboard-centric approach to get the most of PyCharm's many productivity features. Get Smart Assistance: PyCharm knows everything about your code. Rely on it for intelligent code completion, on-the-fly error checking and quick-fixes, easy project navigation, and much more.
- PLease download all the necessary packages before run the application. If you use PyCharm, it will take care of your missing package or
```
pip install missing-package
```

### Installing
A step by step series of examples that tell you how to get a development enviroment running:
* Install [PyCharm](https://www.jetbrains.com/help/pycharm/installation-guide.html) Community Edition.


## Running the tests


## Deployment
All the notebook can be used for research and academic basic function for Python. 

## Built With
* [PyCharm Community IDE](https://www.jetbrains.com/pycharm/download/#section=windows) 

## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](). 

## Authors

* **Truc Huynh** - *Initial work* - [TrucDev](https://github.com/jackyhuynh)

## Format
my README.md format was retrieved from
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* Any acknowledgments go here
