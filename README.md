# Parstagram 

This is an Instagram clone iOS application with a custom Parse backend that allows a user to post photos, view a global photos feed, and add comments!


## User Stories
- [X] User sees app icon in home screen and styled launch screen.
- [X] User can sign up to create a new account.
- [X] User can log in.
- [X] User can take a photo, add a caption, and post it to the server.
- [x] User stays logged in across restarts.
- [x] User can log out. 
- [x] User can view comments on a post.
- [x] User can add a new comment.

## Languages & Tools
Swift, Xcode, Alamofire, Parse

## What I Learned
Moving along my journey in learning Swift, I wanted to take a step further and move away from APIs. For the most part, I have been utilizing APIs, such as Twitter, to build client applications. For Parstagram, I wanted to set up my own database and have users that are unique to my app only. I discovered the Parse framework is a common and easy resource to prototype iOS applications with a cloud backend. While developing this application, I learned how to use this framework to handle user creation and authentication and saving users' posts and comments to posts in a database. 

When I created this application, I had no prior knowledge on databases or schema design. While developing, I realized I needed to research a bit on database design and determine what relations I needed to have in my database and what kind of data would be stored in each. I realized it is quite difficult to draft a good schema because there shouldn't be too much repetition across tables. I also realized that dependencies across tables need to be accounted for because if an update is made to one table, it might cause a chain effect to other tables. Although my application only utilized a few relations, it made me think about how applications, like Instagram, have massive databases and how a good database design is necessary to optimize performance and searching.


## Video Walkthrough
Here's a walkthrough of implemented user stories:

<img src='http://g.recordit.co/mt9DOyY9qg.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />
<img src='http://g.recordit.co/9ubhXjYxbR.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />
