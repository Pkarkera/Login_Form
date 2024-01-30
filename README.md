# Login Form using PHP and Symfony

## Prerequisites
Before you get started with Login Form, make sure you have the following dependencies installed on your system:

# 1. Symfony installer:
In order to use the Symfony installer, we got to make sure that we create a Binary. Therefore, we need to install the following depending on your OS from:

`https://symfony.com/doc/current/setup.html`

If you’re not sure if you got that installed, you can run the following command to see if your local machine meets the requirements.

`symfony check:requirements`

If you have your environment setup correctly, you will be hit with the following message:

`[OK] Your system is ready to run Symfony projects`

Symfony’s CLI comes with a web server that is very easy to use. In order to use it, you need to run the following command inside the project directory:

`symfony server:start `

This will return back a message which says that your web server is indeed listening, and it can be accessed through your localhost.



# 2. Visual Studio Code:

Download Visual Studio Code from the following link:

`https://code.visualstudio.com/download`

# 3. Dependencies:

You could download composer and install it in your local with the following command in the VS code.

`composer install`

## Steps to follow while creating a login form:
 
  1. First we need to create a new project with the following command:
  ` symfony new Login Form`

  2. We need to check if composer is installed properly by using the command:
  `composer status`

  3. Next we need to create a security in the form by using the following commands:
  `composer require security`

  4. We need to create a user for the authentication using following commands:
  `symfony console make:user`

  5. Next we create a form-login for the app with the following commands:
  `symfony console make:security:form-login`

  6. We then make changes in `config/packages/security.yaml` , `src/Controller/LoginController.php` , `templates/login/login.html.twig`.

  7. We start the server:
  `symfony server:start`

  8. We can check the server on port number 8002.



