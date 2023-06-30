A non logged user can register himself in the system

Necessary data are

- full name
- email
- password
- birth date

emails are unique, so if an existing email exists, there should be a response of "email already exists try to log in or go to forgot my password"

when an user is registered the system sends him an email with a code so he can verify his email. 

the verification code should last for 10 minutes

after his email is verified, the user can access the system

## Functionalities

- Register User
- List user's data
- Change password
- Change email - sends validation email again
- Inactive account