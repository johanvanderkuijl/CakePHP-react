=CakePHP-react=
Example how to use a CakePHP 3 application as backend together with a React frontend.

1. Create the CakePHP application
cd /cakephp-react

composer create-project --prefer-dist cakephp/app backend

2. create the following database and user/password:

'database' => 'my_app',
'username' => 'my_app',
           
'password' => 'secret',
           

3. run the migration. This will create the database tables

cd cakephp-react/backend
bin/cake migrations migrate

4. test the app in your browser. If the requests ends with .json, the reply is also json.

// json request
http://localhost/cakephp-react/backend/comments.json

// normal request
http://localhost/cakephp-react/backend/comments



