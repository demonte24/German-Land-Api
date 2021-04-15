# German Land

### Important Links
-	Front-End-Repo: https://github.com/demonte24/German-Land-client/tree/master

-	Deployed API: https://warm-thicket-76411.herokuapp.com/

-	Deployed Client:https://demonte24.github.io/German-Land-client/

### German Land
  Is a webpage where users can add their female dogs to match with my male German shepherd.
### User Stories  
-	As a user I would like to sign-up.
- As a user I would like to sign-in.
- As a user i would like to change my password.
- As a user i would like to add my female dog information.
- As a user I would like to view my dog list
- As a user i would like to update my dogs
- As a user i would like to delete my dogs
- As a user i would like to [sign-out]
-	As a signed in user, I would like to see the following meta-data for any

### Technologies Used
-	Express
-	Mongoose
-	MongoDB
-	JavaScript
- JSON
### Resources
###### Users
| Verb   | URI Pattern  |Body    |Headers  |  Status | Body |
|--------|--------------|------  |-----  |-------------------|------------|
| POST   | `/sign-up`   |credentials | empty | 201, Created| user
| POST   | `/sign-in`   |credentials | empty | 200 Ok | user w/token
| PATCH  | `/change-password/`|password |token| 204 No Content| user w/token
| DELETE | `/sign-out/`       | empty|token |   201 Created | empty

###### dogs
| Verb   | URI   |Body    |Headers  |  Status | Body |
|--------|--------------|------  |-----  |-------------------|------------|
| POST   | `/dogs`   |{} | token | 201, Created| Dog Obj
| GET   | `/dogs`   |n/a | empty | 200 Ok | Dog Obj
| DELETE | `/dogs/:id` |n/a |token | 200 Ok | n/a
| PATCH | `/dogs/:id` |Dog data | token | 200, Ok | Dog Obj

### Unsolved Problems

#### Images
<img width="1136" alt="Screen Shot 2021-04-15 at 10 25 24 AM" src="https://media.git.generalassemb.ly/user/33721/files/26d4b080-9dd5-11eb-8624-09a492cb6f21">

<img width="1279" alt="Screen Shot 2021-04-15 at 10 26 46 AM" src="https://media.git.generalassemb.ly/user/33721/files/23d9c000-9dd5-11eb-9b7d-4cd7b75251bc">

#### Wireframe
<img width="578" alt="Screen Shot 2021-04-14 at 12 39 19 PM" src="https://media.git.generalassemb.ly/user/33721/files/b2d7d100-9d1e-11eb-8dc1-982741da60eb">


#### ERD
<img width="348" alt="Screen Shot 2021-04-14 at 12 38 32 PM" src="https://media.git.generalassemb.ly/user/33721/files/92a81200-9d1e-11eb-8a1e-71a3b5994523">
