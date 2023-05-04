#  :fire: InstagrameClone

the project is Instagram Clone with Most features and Design is inspired from Instagrame

## Features

:star: **Login / SignUp** : 
Design : the design is a clone to instagram completely.
functionality : I used firebase AUTH (email , password) method to sign up user in firebase realtime database , and email container.
this applied for both pages SignUp and Login.
if there is an error such the user already exists then Error message will appear in the bottom of the page (Errors Handling).



:star: **Home Page** :  this page starts with loading Data from firebase realtime databse (loading posts) and getting it and render posts in home page 
every post has functions such as : 
- post title or message (what user write on post)
- owner  profile and it's username
- like & post a comment
- see list of other users Comments

and eclipse button which has some list of functions also  : 
- copy post link
- report the post
- Go to post to see Details
- go to owner profile. (post owner).

there is more than 190 post in the home page whenever user reaches the bottom of the page the page automatically gets new post from database and render it to redux array and display it in Home page.
the post Card is not supporting the video element because of user experience problem.

:star: **Search Page** : I created this page just similar to instagrame search in design and in functionality .
the Search starts with keyword if user typed 'Muhammed' then the input value will be submited and return the list of results which contains list of users which contains word 'Muhammed'.
if the user found what he looking for he can click on user Card and it will redirect it to the user page e.c ('Muhammed' Profile).

 :star: **Reels** : this page is similart also to instagrame reels and titk tok videos style , the videos setted to auto played and muted , but user can Unmute and stop the video or play also.
 this reels Card contains following features : 
 - display list of the reels comments 
 - like the reel || unlike the reel
 - Save the reel to saved posts which is in profile page.
user can scroll down between reels , and watch them one by one like tik tok.
 
:star: **Messaging : ** this page has a little bit custome desing but also a clone from instagrame messaging page  , in this page you can see you list of users that you talked to before , and ability to creat new conversation with new firend .
the user can send and recive messages from other users , messages are encrypted because of firestore security.
every user you send a message to or recived a message from is save in the front page list and can talk again , old messages are saved also sender messages will be in the right and reciver messages will be in the left , similart to modern messages style.
in old messages you can also see how much unseen messages you have with red color (1,2,3 or maybe 5)
and the user card contains also the last messages send in the conversation.


:star: **Profile** : this page contains user infrormations such as username , profile picture , user posts.
this profile has following feartures  : 
- if user has no post he can creat one from profile page .
- the user can see his posts , as also other users can see his posts by accesing his profile.
- the user can only see his saved posts and view it's details such as who post it time posted and tile of the post etc....
- user can change his profile picture from his choise , just click on profile picture and a updater component will apear and choose a picture from you device.

:star:** Uploading Posts / Reel: ** all users can post new post from the nav bar button which will apear and it wil ask to set the file path (supports images/videos only) and it will ask also for post titl and user shold write something on the post and click on post button will post it in home page ,
untile it's not posted the loading effect will apear.

:star: **More button** :  this is the last button in the nav bar which has two options : 
- 1st : Logout
- 2st : Cancel

- More informations about user actions in the project : 
user can post and comment copy posts link and view posts details also in instagrame design style


the project pages are completley responsive in chrome dev tool in all screens and in my mobile too so it will work for most users.


## Installation

the project is a clone of instagrame so it should be easy to use.


## Contributing

if you find any bug please send it to me and i'll fix.

## License
this project is completley made by me from zero and it's completed.


## Contact

How users can get in touch with you, including email address, social media links, or other contact information.

## Acknowledgements

I used in this project many tools :

- HTML  & Vanilla Js & SCSS
- React Js 
- firebase (AUTH & firestore & realtime database & storage)
- Redux Toolkite to manage the app state because it's a bit large
- (framer Motions for animations) & (Uiid Generator) & ()
- Adobe Stock Icons (which is used in navbar)
- font-awsome (icons)

there is some other features that is not included in the app , also you will find there Notification Page Maybe it will work and maybe no , so I have no much time to fix it and add other features such as account details when it's created and etc....
those other features are really east but no time to add.
