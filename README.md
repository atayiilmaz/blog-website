
# Blog Website App

Blog website app is a basic app that you can create your own posts and view them.
## Tech Stack

**Client:** ejs, html, css

**Server:** Node.js, Express, MongoDB, Mongoose, lodash


## Installation

Clone the project

```bash
  git clone https://github.com/atayiilmaz/blog-website
```

Go to the project directory

```bash
  cd blog-website
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  nodemon app.js
```

Also make sure that you have started the mongoDB server on localhost.
## Usage/Examples

GET http://localhost:3000/ --> Home page, you can view all posts.

GET http://localhost:3000/posts/{postId} --> view a post by postId

GET http://localhost:3000/about --> About page

GET http://localhost:3000/contact --> Contact page

GET http://localhost:3000/compose --> add a new post

POST http://localhost:3000/compose --> post a new post

## Screenshots

![App Screenshot](https://github.com/atayiilmaz/blog-website/blob/main/public/img/Screenshot%202023-04-09%20151710.png)
![App Screenshot](https://github.com/atayiilmaz/blog-website/blob/main/public/img/Screenshot%202023-04-09%20152113.png)
![App Screenshot](https://github.com/atayiilmaz/blog-website/blob/main/public/img/Screenshot%202023-04-09%20152137.png)

