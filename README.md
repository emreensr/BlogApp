# Node.js-Blog-App-REST-API-with-MongoDB



For this project you need to have the following setups:

- Node.js → Server-Side JavaScript
- Express.js → Node Web Framework
- MongoDB → Database
- Mongoose → Database Structuring System
- Postman → used to test API with requests

I created a "models" folder in the repository. This will set how our database structure will be like.

### ROUTES
- POST /register - used to register.
- POST /login - used to login.
- PUT /user/:id - to update specific a user with unique Id
- DELETE /user/:id - to delete a specific user with unique Id
- GET /user/:id - to view a specific user with id.

- GET /posts - to view all the posts.
- POST /posts/ - to add a new post.
- GET /posts/:id - to get a post with specific id
- PUT /posts/:id - to update specific post with unique Id
- DELETE /posts/:id - to delete specific post with unique Id

- POST /category/ - to add a new category.
- GET /category - to view all the categories.

It was used **multer** to upload file. 

# Mongodb
> List of users
<img width="650" alt="Screen Shot 2022-09-09 at 17 53 31" src="https://user-images.githubusercontent.com/70320254/189391887-9661e81b-ceca-4ceb-9697-b62532c1cc88.png">

> List of posts
<img width="650" alt="Screen Shot 2022-09-09 at 17 51 28" src="https://user-images.githubusercontent.com/70320254/189391905-e08f96b6-6b79-4f54-ad0b-85da1dc8157d.png">




