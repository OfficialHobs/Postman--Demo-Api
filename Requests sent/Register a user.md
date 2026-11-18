**Registering a new user**
  - this registration done to get back an access token for further and more complicated actions on the API
  - and as tested, it returns a successful message as well as the token

<img width="1073" height="892" alt="image" src="https://github.com/user-attachments/assets/bf90ea2b-2b1f-4c8d-a830-9a2a9eaaa5e8" />

**Testing - RE-registering an already existing user**
  - this test is to see whether API would accept a duplicate registration. (which should not be)


<img width="1062" height="890" alt="image" src="https://github.com/user-attachments/assets/0b582ca0-22d6-4602-9b15-77da72692bfa" />

  - as expected, this returned an error message 409 - (conflict)
