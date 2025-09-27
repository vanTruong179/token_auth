Create five repositories then commiting all source code

Write read me on each repository to show the way you use to test POSTMAN

Using source code provided by lecturer. Read source code and test all
APIs with POSTMAN.

1.  simple_auth source code

    a.  node basic_auth.js.

Hint to add authorization field in request header

![](./images/media/image1.png){width="7.25in" height="4.53125in"}

- SUCCESS

  a.  node cookie_auth.js Hint to show cookie

-Login\
![](./images/media/image2.png){width="7.25in" height="4.53125in"}

-Profile\
![](./images/media/image3.png){width="7.25in" height="4.53125in"}

-Logout\
![](./images/media/image4.png){width="7.25in" height="4.53125in"}\
Show cookie in mongoDB

![](./images/media/image5.png){width="7.25in" height="4.53125in"}

2.  cookie_session_auth source code

    a.  node cookie_auth.js

![](./images/media/image6.png){width="7.25in" height="4.53125in"}

b.  register

![](./images/media/image7.png){width="7.25in" height="4.53125in"}

Check in database

![](./images/media/image8.png){width="7.25in" height="4.53125in"}

![](./images/media/image9.png){width="7.25in" height="4.53125in"}

c.  login

![](./images/media/image10.png){width="7.25in" height="4.53125in"}

Check in database

![](./images/media/image11.png){width="7.25in" height="4.53125in"}

d.  go to profile

![](./images/media/image12.png){width="7.25in" height="4.53125in"}

e.  go to logout and check cookie is deleted in database

![](./images/media/image13.png){width="7.25in" height="4.53125in"}

![](./images/media/image14.png){width="7.25in" height="4.53125in"}

3.  local_passport_auth_service

    a.  register

![](./images/media/image15.png){width="7.25in" height="4.53125in"}

![](./images/media/image16.png){width="7.25in" height="4.53125in"}

b.  login

![](./images/media/image17.png){width="7.25in" height="4.53125in"}

![](./images/media/image18.png){width="7.25in" height="4.53125in"}

![](./images/media/image19.png){width="7.25in" height="4.53125in"}

4.  local_passport_website: Run by yourself

-Register

![](./images/media/image20.png){width="7.25in" height="4.53125in"}

![](./images/media/image21.png){width="7.25in" height="4.53125in"}

5.  token_auth

    a.  go to profile

![](./images/media/image22.png){width="7.25in" height="4.53125in"}

b.  go to register

![](./images/media/image23.png){width="7.25in" height="4.53125in"}

![](./images/media/image24.png){width="7.25in" height="4.53125in"}

c.  login

![](./images/media/image25.png){width="7.25in" height="4.53125in"}

Copy token to acces resource later.

eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY4ZDc4NmE2ZWZlYzZjNmQ2ODQwYWY2YiIsImlhdCI6MTc1ODk1NTQ0MCwiZXhwIjoxNzU4OTU5MDQwfQ.IDt9tzVEPaEYvfu0kjzawYFxJgYZY7L0plaDeHgirvI

d.  Go to profile with token

![](./images/media/image26.png){width="7.25in" height="4.53125in"}

**Question**: Modify code to make token expried?

Chỉnh lại để token hết hiệu lực sau 10 giây

![](./images/media/image27.png){width="7.25in" height="4.53125in"}

6.  Fork NodeJS-Authentication-System from

[[https://github.com/mrhuynhnam/NodeJS-Authentication-System]{.underline}](https://github.com/mrhuynhnam/NodeJS-Authentication-System)
to your reporsitoy

a.  Modify code to complete the application correctly. Hint: use some
    instructions in github repository after fork

b.  Show your student ID and fullname in all pages

c.  Test all pages corresponding to their function.

d.  Capture screen all test results in some picture whose name is test
    function (Example: login.png or logout.jpg). Put all of them in
    public/results folder

e.  Commit your project to repository

**HOW TO SUBMIT**

Write six repositories link in file StudenID-Fullnam.txt (example:
20872461- NguyenVanAn.txt) then submitting to LMS.
