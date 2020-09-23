
# Simple Chat App (Online Bidding System)

Simple Chat App is a play chat app that uses web sockets to demonstrate realtime communication

## Description
There is no authentication here. Anonymous users can join the chat group and subscribe to different 
chat events. Several topics are available for subscription, like:
1. guestnames: guests in the chat pool
2. guestchats: shows chats sent between users
3. guestupdates: guest update events like when someone is typing

## Getting Started

### Installing

1. Clone the project from github, into a desired source folder
2. Make sure Java 8 is installed on your machine
3. Make you you also have maven installed 
4. Run mvn install in the project root (where your pom file is) to download dependencies 


### Executing program

After the above setups, its time to run the program
### Run the app from an Executable jar
 1. Build an executable jar with maven by typing
    mvn package 
 2. Execute the jar by typing
    java -jar path/to/jar/file
    
###un the app from an IDE
  if you are using an IDE like IntelliJ, navigate to the ChatApplication.java file and run it