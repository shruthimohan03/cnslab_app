# cnslab_app
Assessment app: Login app + Firebase Real-Time Database storage using Kotlin

Setup-Instructions:
Ensure that you have Java compatibility set to jdk11

First Layout: Login Page:
- DESIGN: 2 input fields: username and password; 1 login button
- Validation for username and password is done as well
    -for username: minimum length must be 4 and no spaces are allowed
    -for password: minimum length must be 8 and use of alphanumerics, uppercases, and special characters are mandatory
- If validation is not satisfied, an error message is given below the username(and/or)password after clicking the login button. The input is cleared and waits for the correct pattern of username and password.
- If username and password are of proper pattern but are not correct credentials then the message 'Login Unsuccessful' pops up below.
- If the pattern and credentials are satisfied, the message 'Login Successful' pops up below and is rendered to the Home Screen

Second Layout: Information Page:
- DESIGN: 3 input fields: first name, last name, and email; 1 submit button
- The given details are sent to the Firebase's Real-Time Database and stored.
- If the details are stored successfully, a success message is shown. Else an unsuccessful message is shown.
  
