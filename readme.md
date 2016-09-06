# CakePHP-react example

Example how to use a CakePHP 3.x application as backend together with a React frontend as found on <https://facebook.github.io/react/docs/tutorial.html>

## Installation

Make sure you have [Composer](http://getcomposer.org/doc/00-intro.md) installed and configured.

1. Check out this source code to cakephp-react and open a shell in the backend directory.

2. Run `composer install`.

3. Create a database with the following settings:
    ```
     'database' => 'my_app',
     'username' => 'my_app',
     'password' => 'secret',
    ```  
4. Read and edit `config/app.php` and setup the 'Datasources' and any other
configuration relevant for your application.

5. run the migration. This will create the database table.
    ```   
       bin/cake migrations migrate
    ```

## Backend
Test the backend with the CakePHP interface:
<http://localhost/cakephp-react/backend/comments>  

## Frontend
Test the frontend with the React interface
<http://localhost/cakephp-react/react/public>



