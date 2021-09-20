# Swaggy (easy)

Challenge's desecription: This API documentation has all the swag 

# Introduction to Challenge 
This is a easy challenge. This challenge based on  Swagger UI. There is a (/flag) path with the (GET) request. And there is two server. But only one server can use it. 

# Solution
So i change the challenge server to (http://staging-api.congon4tro.com:7777). and In (Authorize), i put the admin:admin as the user and password.

and i Execute it and got flag in json part. 

# 2nd solution
We can solve it with curl too.

curl -X GET 'http://staging-api.congon4tor.com:7777/flag' -H 'accept: application/json' -H 'Authorization: Basic YWRtaW46YWRtaW4='

# Flag
flag{e04f962d0529a4289a685112bf1dcdd3}
