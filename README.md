# Project-Recommendation-System-for-Social-Network-Site

#### Goal ####
Emphasizes on chat system where the list of friends of the user is intelligently displayed based on two criteria
* suggestion of only friends close to user
* suggestion of friends based on the mood of the user

#### Implementation ####
* To determine which friends shared a closer bond with the user on the social network platform, we devised a metric called **closeness factor**. This factor was calculated based on following parameters
  * Tags on user's status : If the user tags any of his/her friends on his/her statuses
  * Tags on user's post : If the user tags any of his/her friends on his/her posts
  * Chat duration : Total duration of the chat that the user had with his/her friends. Here only chats most recent to a certain extent are considered.
  * Message count : Total number of messages that the user shared with his/her friends. Here only messages most recent to a certain extent are considered.
  * Comments on posts : Total comments that the user has commented on friend's post or has been commented on his/her posts by his/her friends
  * Likes count : Total number of times that the user has liked a friend's post or his/her friends have liked the user's posts

#### Technologies used ####
Database - MongoDB
Backend - Java
Frontend - HTML, CSS
