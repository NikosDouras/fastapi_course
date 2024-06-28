I built a social-media-like platform where users can register, log in and 
create-edit-delete-like posts. The app is dockerized and also running 
on render and an Ubuntu Server on Digital Ocean. You can test it using 
postman but I STRONGLY suggest using the "Swagger UI" tool. Since the 
app is running on render you don't even need to run the Docker to test it.

---Using Swagger UI---

- Simply paste this link: https://fastapi-fx0v.onrender.com/docs
  (or this if you want to access the Ubuntu Server: http://138.197.185.78:8000/docs)
  on your Browser.(refresh your first click if you chose render, it takes 30s to come back to life)
- First create a user in the section "users". Click on "try it out" and
  follow the example to send your request.
- On the top right of the page where it says "Authorize" insert your email
  and password.
- Now you can create/view/update or delete posts. You can create many
  users and posts (and also likes) to test the API.

  If you prefer to run it with Docker and/or want to test the API  using
  Postman check out the "Run_it_with_Docker" and "End-points-Postman" files.
