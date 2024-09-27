# hope
explain
---------------------------------------------------
1. people should be able to log in / sign up
2. they should be able to have a profile page, having a name, a bio, a date of birth, a userID and a profile photo
3. they should be able to see five main pages {their own profile page and settings, chats with others, new post, search and home}__
   a. in their own profile page they can see their profile photo with their name and info
   b. in their chat section they can see their chats with others
   c. in the new post they can simply post something
   d. in search they get suggestions
   e. in home they see posts from friends.


project structure

/twitter-clone
  ├── /public
  │   ├── index.html
  │   ├── style.css
  │   └── app.js
  ├── /server
  │   ├── server.js
  │   ├── models
  │   │   └── User.js
  │   │   └── Post.js
  │   └── routes
  │       └── auth.js
  │       └── posts.js
  ├── package.json
