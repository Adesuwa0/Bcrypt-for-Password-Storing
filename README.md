# Bcrypt-for-Password-Storing
This project demonstrates secure password storage using Flask and bcrypt, including hashing, salting, peppering, and rate limiting.


## Setup Instructions

1. Open terminal and navigate to the project folder:
   cd password_project

2. Create a virtual environment:
   python -m venv venv

3. Activate the environment:
   Mac/Linux:
   source venv/bin/activate

   Windows:
   venv\Scripts\activate

4. Install dependencies:
   pip install -r requirements.txt

5. Run the application:
   python app.py

6. Open browser:
   http://127.0.0.1:5000/register



## How to Use

* Register a new user
* Login with correct credentials
* Try incorrect password to see failure

## Security Features

* bcrypt hashing
* Automatic salting
* Pepper (extra secret)
* Rate limiting
* Password policy enforcement


## Notes

* Passwords are never stored in plaintext
* Hashes are stored in users.db
