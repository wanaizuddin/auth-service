# auth-service

## Start Backend
- git clone https://github.com/wanaizuddin/auth-service.git
- run `npm install`
- run `node server/server.js` 

## Start MongoDB
- Start your MongoDB service

## API Spec
- POST /signup
- POST /login
- GET /user/:userId (Get Specific User)
- GET/users (Get List of Users)
- PUT /user/:userId (Update User)
- DELETE /user/:userId (Delete User)

## Examples
- Screenshot 1 (Sign up with "basic" role):
![image](https://user-images.githubusercontent.com/85466137/121219168-00536300-c8b6-11eb-8e38-69a92a73d0ef.png)

- Screenshot 2 (Authorization error and cannot get list of users with "basic" role):
![image](https://user-images.githubusercontent.com/85466137/121219438-44defe80-c8b6-11eb-8eb7-389dc0b745ca.png)

- Screenshot 3 (Sign up with "admin" role):
![image](https://user-images.githubusercontent.com/85466137/121219686-8b345d80-c8b6-11eb-9161-2df5dc491d85.png)

- Screenshot 4 (Authorization success and get list of users with "admin" role):
![image](https://user-images.githubusercontent.com/85466137/121219739-9a1b1000-c8b6-11eb-93e8-bb1388b9d847.png)

