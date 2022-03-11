## Get All Users (GET):
    > localhost:3000/api/auth/users
    > https://grocery-jwt.herokuapp.com/api/auth/users
   
## Register (POST):
    > localhost:3000/api/auth/register
    > https://grocery-jwt.herokuapp.com/api/auth/register
    > {"name":"Kirti", "email":"kirti@gmail.com", "password":"12345678", "role":"User"}
   
## Login (POST): 
    > localhost:3000/api/auth/login
    > https://netmedslogin.herokuapp.com/api/auth/login
    > (Body) => {"email":"kirti@gmail.com", "password":"12345678"}
    > (response) => {"auth": true,"token": "token"}      

## UserInfo (GET): 
    > localhost:3000/api/auth/userInfo
    > https://grocery-jwt.herokuapp.com/api/auth/userInfo
    > (Header) => {'x-access-token':'token from login'}
