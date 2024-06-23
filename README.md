# CPP - Chat Prompt Platform

This project is a command-line chat application built in C++. It allows users to sign up, sign in, add friends, send messages, manage their friend list, and perform group chats. The application runs entirely in the command prompt/console environment.

## Functionality

### User Management
- **Sign Up**: Users can choose a unique username and password to create their account.
- **Sign In**: Existing users can log in with their username and password credentials.

### Messaging Features
- **Inbox**: Users can view all messages received in their inbox.
- **Chat**: Users can send one-on-one messages to their friends.
- **Group Chat**: Users can create group chats by adding multiple recipients and sending messages to the group.

### Friend Management
- **Friend List**: Users can view their list of friends.
- **Add Friend**: Users can add other users to their friend list.
- **Remove Friend**: Users can unfriend existing friends.

## Technical Skills Used

- **Language**: C++
- **Data Structures**: 
  - `map` and `vector` are used for storing user information, friend lists, and messages.
- **Object-Oriented Programming (OOP)**:
  - Classes (`hierarchy`, `author`, `frnd`) are used for encapsulating data and behavior related to users, friends, and messaging.
  - Inheritance (`author`, `frnd` inherit from `hierarchy`) is utilized to reuse code and establish relationships between classes.
- **File Handling**:
  - Users' data (username and password) are stored in a `map`.
- **String Manipulation**:
  - Various string operations (`strcpy`, `strcat`, `getline`) are used for message handling and user interaction.
- **Control Structures**:
  - Loops (`for`, `while`) and conditional statements (`if`, `switch`) are used to control the flow of the application based on user input.
  - Unconditional statements, like `goto`, are used to skip some part of the code based on user input.

## Running the Application

To run the application:
1. Compile the source code (`main.cpp`) using a C++ compiler.
2. Execute the compiled executable in your command prompt/console.

## Here's a small video, showing the features of CPP:-

https://github.com/adroit-anuj/Chat_App-CPP-/assets/134070793/c44436a8-c5b7-4cd2-aa40-9840a76b14db



## Future Improvements

- **Enhanced User Interface**: Implementing a graphical user interface (GUI) for better user interaction.
- **Encryption**: Adding encryption for storing passwords securely.
- **File Persistence**: Implementing file storage for user data to maintain user accounts across sessions.

This command-line chat application serves as a basic implementation of a messaging system and can be expanded further with additional features and optimizations.
