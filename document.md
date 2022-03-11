## Get All Users (GET):
    > localhost:3000/api/auth/users
   
## Register (POST):
    > localhost:3000/api/auth/register
    > {"name":"Kirti", "email":"kirti@gmail.com", "password":"12345678", "role":"User"}
   
## Login (POST): 
    > localhost:3000/api/auth/login
    > (Body) => {"email":"kirti@gmail.com", "password":"12345678"}
    > (response) => {"auth": true,"token": "token"}      

## UserInfo (GET): 
    > localhost:3000/api/auth/userInfo
    > (Header) => {'x-access-token':'token from login'}
