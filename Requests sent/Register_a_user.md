**Registering a new user**
  - this registration done to get back an access token for further and more complicated actions on the API
  - and as tested, it returns a successful message as well as the token

<img width="1073" height="892" alt="image" src="https://github.com/user-attachments/assets/bf90ea2b-2b1f-4c8d-a830-9a2a9eaaa5e8" />

**Testing - RE-registering an already existing user**
  - this test is to see whether API would accept a duplicate registration. (which should not be)


<img width="1061" height="816" alt="image" src="https://github.com/user-attachments/assets/1a365106-2680-45bb-b9d3-8a2110a32577" />


  - as expected, this returned an error message 409 - (conflict)
