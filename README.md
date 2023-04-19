# License

The source code is distributed under the GPL-3.0 license. See LICENSE.md for more information.

# About Bar Chat

This chatroom is a real time webapplication. This means that there's a continues stream of connection between multiple computers.

## Functionalities

This application has the following functionalities:

User:

- [] The user can use a username
- [] The user is able to choose a profile picture
- [] The user can see when someone is typing
- [] The user can choose to listen to a radio

Hosting:

- [] The user can create a chatroom and make themselves an "host" of that chatroom
- [] The host is able to kick users
- [] The host is able to lock the chatroom with a password
- [] The host is able to decide how many players can join a chatroom
- [] The host can change the background of the chat

Chat:

- [] You can send one image with a max. amount of kb in the chat to make sure the application is able to handle the traffix
- [] There's a max. amount of input characters to make sure the application is able to handle the traffic
- [] There's a timestamp
- [] When a chatroom is empty with no users, the chatroom will disappear
- [] When you are offline, the app will say that the chat cannot be updated due to a loss of connection

History:

- [] A chat history
- [] A max. amount of messages being shows to save memory
- [] A part of the history messages are saved in the database to save memory

Bartender:

- [] The user is able to play a bartender game in the chatroom
- [] Each drink that's been mixed, gets a score, the goal is to beat the highscore within the room
- [] The highscore disappears once the room is empty and the room itself will dissolve

# Live demo

This is the link to the live demo of this application: https://basic-chatroom-production-6d2c.up.railway.app/

# Installation

To install the application locally you can follow these next steps:

1. Clone the repository with `git clone [LINK]`
2. Go into the folder that you cloned and open the project in your code editor
3. Install the dependencies with `npm i` in the terminal

# Process

In this section I'll be talking more about the process. This is more relevant for teachers who will be grading this project.

## Ideas

In week 1 I came up with 3 ideas as listed below:

1. Create an application in which users can make chat rooms for game-related content. In the chat, users can show different covers of games and even browse through a library of pictures related to the game. The chat room will be named after the game that is shown in the chatroom, so that people can join a room depending on their interests.

2. Create a chatroom in which people can make their own chat rooms. People who create the chat room will be hosts and will have special functionalities unlike other users, such as being able to change the background of the room or kick someone out of the room. Additionally, the host can choose a radio station to which people will listen. Other users will only be able to adjust the volume of the radio, but not the channel.

3. People can create a chatroom, and other users can join a certain chatroom based on the code that the chatroom has. If you don't have the code, you're not able to join the chatroom as a user.

4. Create an application in which users can guess in chat who the speaker is of a quote from the show "The Office (US)". Once the correct name has been found, the correct user will be given coins, which they can use to customize their chat (such as chat bubble color, text color, and choosing their own background color).

5. Create a chatroom with a bar theme. There's a jukebox: each user can choose their own radio channel to listen to. They also play a small bartender game and mix drinks that gets a certain score. The score depends on certain recipes.
