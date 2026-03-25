Bug ID: API_BUG_001

Title:
Incorrect status code returned for invalid user ID

Steps:

Send GET request to:

https://reqres.in/api/users/999

Expected Result:

Status code 404 Not Found

Actual Result:

Status code 200 OK returned

Severity:

High


Bug ID: API_BUG_002

Title:
Missing email field in response

Steps:

Send GET request to:

https://reqres.in/api/users/2

Expected Result:

Response contains email field

Actual Result:

Email field missing

Severity:

Medium
