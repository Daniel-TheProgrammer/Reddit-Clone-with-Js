### Daniel theProgrammer,The features can be seen below!
### Features:
* Frontpage
* Subreddits
* Submitting comments / posts / links
* Voting on posts / comments
* Saving posts / comments
* Editing posts / comments
* Deleting posts / comments
* Subscribing
* Searching
* Sorting
* Profile pages
* Karma system
* Relative time
* Validation
* Login / Register
* Hash / salted passwords
* Change password / delete account
* API

# API:
URL | Method | Details | Body
---- | ---- | ---- | ----
/api/frontpage | GET | Retrieves all posts from frontpage
/api/r/```subreddit``` | GET | Retrieves all posts from ```subreddit```
/api/post/```id``` | GET | Retrieves post by ```id```
/api/post/```id```/comments | GET | Retrieves all comments for post by ```id```
/api/u/```user``` | GET | Retrieves profile information about ```user```
/api/u/```user```/posts | GET | Retrieves all posts by ```user```
/api/u/```user```/comments | GET | Retrieves all comments by ```user```
/api/register | POST | Registers an account | ```username```, ```password```

# Screenshots:
![Image](https://i.imgur.com/QWmcJG7.png)

