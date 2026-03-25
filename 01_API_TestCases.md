# API Test Cases – Users Endpoint

Test Case ID: API_TC_001

Title:
Get all users

Request Type:
GET

Endpoint:
https://reqres.in/api/users

Expected Result:

Status code 200 OK

Response contains users list


Test Case ID: API_TC_002

Title:
Get single user by ID

Request Type:
GET

Endpoint:
https://reqres.in/api/users/2

Expected Result:

Status code 200 OK

User object returned


Test Case ID: API_TC_003

Title:
Get non-existing user

Request Type:
GET

Endpoint:
https://reqres.in/api/users/999
Expected Result:

Status code 404 Not Found
