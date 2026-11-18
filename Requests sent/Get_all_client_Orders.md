**getting all orders**
  - the GET - get all order endpoint requires authentication: this because it is getting all orders made using a particular token
  - this ensures that only the required user data is given as result
  - but then a single user could order with multiple names - which shouldn't be so
  - if another 'correct' token is used, the data for the bearer token will be the output
  - the authorization section is marked green because we are using an authentication token (access token)
   

<img width="1082" height="875" alt="image" src="https://github.com/user-attachments/assets/3e70f716-bfb9-45f8-bcc7-d8437e8b2778" />

  **- Test without passing an authorization key in the required field**

<img width="1075" height="931" alt="image" src="https://github.com/user-attachments/assets/d1e223df-6aaa-438d-a64f-bf09ae2eb11d" />
