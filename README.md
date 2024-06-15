<p>push the repository in your system and follow the folling steps for creating table in your db then seed 50 fake row for each column.</p>
<p>step-1 : run 'php artisan serve'</p>
<p>step-2 : modify .env file's db name ->project_1(*)</p>
<p>step-3 : run 'php artisan migrate:fresh --seed'</p>
<p>now check your db you will have table with person (name,email,password,phone,address,city,stste,country,remember_token) with 50 fake data</p>
<p>-> now open postman in your browser</p>
<p># check for each api's</p>
<p>->to show all data in one run 'http://127.0.0.1:8000/api/show'</p>
<p>->to store new data in a row run  'http://127.0.0.1:8000/api/store'</p>
<p>              then choose body->row / json</p>
<p>              {</p>
<p>              "name":"......*",</p>
<p>              "email":".........*",</p>
<p>              "password":".......*",</p>
 <p>             "phone":"........*",</p>
 <p>             "address":".......*",</p>
 <p>             "state":"........*",</p>
 <p>             "city":".......*",</p>
 <p>             "country":"......*",</p>
 <p>             }</p>
<p>-> to show data by id for edit run 'http://127.0.0.1:8000/api/edit/3*'</p>
<p>-> to show list of all input data run 'http://127.0.0.1:8000/api/list'</p>
<p>->to update the edited data again in same field/row run 'http://127.0.0.1:8000/api/update/3*'</p>
<p>->to delete by id run 'http://127.0.0.1:8000/api/delete/3'</p>
<p>->to search by name run 'http://127.0.0.1:8000/api/search'</p>
<p></p>
<p></p>
<p>Note: please suggest your valuable knowledge for futher improvement </p>
<p></p>
<p>THANK YOU </p>
<p>priyanka singh</p>
<p></p>
<p>              
<p>              
<p>              
              }
