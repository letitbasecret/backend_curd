push the repository in your system and follow the folling steps for creating table in your db then seed 50 fake row for each column.
step-1 : run 'php artisan serve'
step-2 : modify .env file's db name ->project_1(*)
step-3 : run 'php artisan migrate:fresh --seed'
now check your db you will have table with person (name,email,password,phone,address,city,stste,country,remember_token) with 50 fake data
-> now open postman in your browser
# check for each api's
->to show all data in one run 'http://127.0.0.1:8000/api/show'
->to store new data in a row run  'http://127.0.0.1:8000/api/store'
              then choose body->row / json
              {
              "name":"......*",
              "email":".........*",
              "password":".......*",
              "phone":"........*",
              "address":".......*",
              "state":"........*",
              "city":".......*",
              "country":"......*",
              }
-> to show data by id for edit run 'http://127.0.0.1:8000/api/edit/3*'
-> to show list of all input data run 'http://127.0.0.1:8000/api/list'
->to update the edited data again in same field/row run 'http://127.0.0.1:8000/api/update/3*'
->to delete by id run 'http://127.0.0.1:8000/api/delete/3'
->to search by name run 'http://127.0.0.1:8000/api/search'


Note: please suggest your valuable knowledge for futher improvement 

THANK YOU 
priyanka singh
              
              }
