**Getting only a single book**
  - using the same GET method but this time around, i used a **path parameter** (i.e /:boodid)
  - this **bookid** is a path variable that stores a value that corresponds to the ' /2' of the books in the server
  - this simple means id = 1
  - using the path variable allowed me to retrieve only a specific book.
  - this result is a 200 request successful



**Below is a snapshot of this**

<img width="1067" height="906" alt="image" src="https://github.com/user-attachments/assets/9846cbe3-f090-4e14-b223-5cb8fae16f8d" />


**TEST - Using a value of 100 as id**
  - as seen below this gives me a 404 error - as in not found - as this exceeds the number(id) of books available


<img width="1077" height="886" alt="image" src="https://github.com/user-attachments/assets/2a151e85-9db5-4f8a-856a-6388e1460efc" />
