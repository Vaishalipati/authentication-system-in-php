# authentication-system-in-php
it is a session based login system having CURD operations.
***Workflow*** 
-when user register, their data get stored in user_details table and their creadential get stored in login_table.
-then session get created.
-when user login,they make a post request to the server with credentials(such as email,password).
-server verifies the credentials against the stored data in login_table
-if it is varified, then session get created.
-session data contains username, password, user_id etc.
-if session is valid then the user is authonticate to application
