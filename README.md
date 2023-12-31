# authentication-system-in-php
<h4>it is a session based login system having CURD operations.</h4>
<p>***Workflow*** <br>
-When user register, their data get stored in user_details table and their creadential get stored in login_table. <br>
-Then session get created. <br>
-When user login,they make a post request to the server with credentials(such as email,password). <br>
-Server verifies the credentials against the stored data in login_table. <br>
-If it is varified, then session get created. <br>
-Session data contains username, password, user_id etc. <br>
-If session is valid then the user is authonticate to application</p> <br>
