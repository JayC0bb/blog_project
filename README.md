## Blog Page Readme

## How to run
1. Create a virtualenv named venv using `python -m venv venv`
2. Connect to virtualenv using `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Linux)
3. From the project folder, install packages using `pip install -r requirements.txt`
4. Now environment is ready. Run it by `python .\blog_project\main.py`
5. Also pip install these: `flask` `flask_bcrypt` `flask_login` `flask_sqlalchemy`


## User Registration
The blog page provides a user registration feature, allowing new users to sign up for an account. To register, follow these steps:

1. Navigate to the registration page by clicking on the "Register" link.
2. Fill out the registration form, providing a unique username, email address, and password.
3. Click the "Register" button to create your account.
4. Upon successful registration, you will be redirected to the login page.


## User Login
Existing users can log in to their accounts using the following steps:

Access the login page by clicking on the "Login" link.
Enter your username and password in the respective fields.
Click the "Login" button to authenticate your credentials.
If the provided information is correct, you will be redirected to the main page.
