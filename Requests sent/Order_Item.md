**Ordering an item**
  - I used the POST method as the API documentation prescribed.
  - then add the required request body as seen in the shot below
  - this particular request requires an authentication - which is the access token i got from [Register a user](Register_a_user.md)
  - I was able to successfully place an order
  - one thing i noticed is that with the same token, you can place order for different customer - this how the API is designed


<img width="1075" height="882" alt="image" src="https://github.com/user-attachments/assets/167d8856-dc47-43be-a2a1-4d36eac530c4" />


**Authentication placeholder**
  - where i added the access token i got previously

<img width="1076" height="477" alt="image" src="https://github.com/user-attachments/assets/18a09b1d-2b60-4379-badb-1ae9c57cd0ea" />

**Testing to see if i can order an item that is not available**
  - first, i check the list of available books to find a book that is set (available : false)

<img width="732" height="133" alt="image" src="https://github.com/user-attachments/assets/62c36ceb-3bf4-453d-a18f-369ae3174062" />

**Placing order on that unavailable book**
  - changed the "id" to 2

  <img width="1072" height="778" alt="image" src="https://github.com/user-attachments/assets/961f0523-9cf1-4db5-ad1d-c2620389e7de" />

  **From this result, this API is properly designed**
