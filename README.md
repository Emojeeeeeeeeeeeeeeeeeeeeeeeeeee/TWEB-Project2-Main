# TWEB Project 2

# Happy😙😺👻  (HappyFaces)

Authors: Mathieu Jee, Olivier Kopp, Florent Piller, Romain Silvestri

Date: November 2018

 ## Description

The goal of this school project is to create a social network with different constraints:

- Users can follow/unfollow other users. 

- Each user should have a personal *wall* with messages/images/videos/... posted by users he followed. 



## What is Happy:kissing_smiling_eyes::smiley_cat::ghost: ? 

Happy😙😺👻 is a revolutionnary social network that allows you to share your funniest stories to the world using your favorite emojis ! :sunglasses::thumbsup:

You don't know how to speak EmojiLanguage ? :fearful: 

Don't worry ! We're taking care of translating your stories with an advanced technology called *EmojiTranslator*. Therefore, you'll be able to tell the world how you feel about anything whithout knowing the EmojiLanguage ! :scream:

## What tech are we using ?

DB: MongoDB 

back-end: Express with GraphQL

front-end: React

Emojilib:

https://github.com/muan/emojilib

https://github.com/notwaldorf/emoji-translate (not sure)

## Deployement of the app

We used Heroku to deploy the app. The two following addresses can be accessed : 

front-end : https://emojee-client.herokuapp.com

back-end : https://emojee-server.herokuapp.com

## How to use this app ?

Firstly, you have to register an account to be able to connect to the app. Once connected, you are redirected to your Home page, which is the place where you can see all your messages and the messages of peoples you are followings. You can access this page by clicking on 🏠 in the navbar.

You can write a new message by clicking the 💬 button and filling the form. You can delete one of you message at any moment by clicking on the red cross on the message card . 

If you click on 'My ✉️ ', you will have access to your personal message only. You can also access to all the message that you have liked by clicking on 'My ❤️'. 

You can access to your profile by clicking on your profile picture in the navbar. In the end, you can log out by clicking on the logout button.



The profile page allow you to change you profile picture depending on your mood.

You can like messages by clicking on the like button and unlike them by clicking again.

You can also follow/unfollow persons,

You can see the followers and the peoples followed by a user if you go to his profile (by clicking on his name).



In order to find friends, you can search people in the search bar with their usernames.



## Tests

Some tests have been written to make sure that the graphQL query are working. They can be executed by launching the client with `npm run test`

## Client Repo

https://github.com/Emojeeeeeeeeeeeeeeeeeeeeeeeeeee/TWEB-Project2-Client



## Server Repo

https://github.com/Emojeeeeeeeeeeeeeeeeeeeeeeeeeee/TWEB-Project2-Server



## Known issues

- For now, Happy😙😺👻 is optimized for `Google Chrome`. Some emojis may not display if you are using another browser.  
- If your screen height is too big, the infinite scroll bar may not work. It means that you probably won't be able to load more messages or users.