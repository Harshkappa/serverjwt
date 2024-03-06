# serverjwt
A server-side code to generate kid and tokens
It conatins two methods namely a GET method /jwks and a POST method /auth
The server is to generate kids to be used and assign expiration duration to them. it also has to 
ensure there is generation of tokens.

Testing of the server was done through Postman and had the following:

1. For GET method /jwks
   ![Screenshot (5)](https://github.com/Harshkappa/serverjwt/assets/162372080/2ef75963-3e24-46ad-ba6c-8e4e27fb578f)

2. For POST method /auth
   ![Screenshot (6)](https://github.com/Harshkappa/serverjwt/assets/162372080/898fb04d-77ea-46c3-a8d6-048e96fffbed)

