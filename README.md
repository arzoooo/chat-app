# React Chat Application

This project is a front end for a chat application built with React. The application enables users to create conversations, search for contacts, send messages within conversations, and handle alerts. The project uses dummy data from a JSON file for demonstration purposes.


## Functionality

- chat with friends.
- add new users to chat
- Search a user by name






## Project Structure

      src/
          ├── components/
          │   ├── Conversations.js
          │   ├── MessageContainer.js
          │   ├── Conversation.js
          │   ├── NewConversation.js
          │   ├── ConversationCard.js
          │   └── NewMessageContainer.js
          │   └── index.js
          ├── styles/
          │   ├── Conversations.css
          │   ├── MessageContainer.css
          │   ├── Conversation.css
          │   ├── NewConversation.css
          │   ├── ConversationCard.css
          │   ├── NewMessageContainer.css
          │   ├── App.css
          ├── DummyData/
          │   ├── dummycontacts.json
          │   ├── dummyConversations.js
          ├── App.js
          ├── index.js




## Table of Contents

- [Components](#components)
- [Styles](#styles)
- [Dummy Data](#dummy-data)
- [App.js](#appjs)

## Components

- **`Conversations.js`**: Displays the list of conversations in the left sidebar.

- **`MessageContainer.js`**: Represents the message container for a conversation.

- **`Conversation.js`**: Represents an individual conversation, showing contact name and last message snippet.

- **`NewConversation.js`**: Displays a pop-up with a list of contacts to initiate a new conversation.

- **`ConversationCard.js`**: Renders an individual conversation card.

- **`NewMessageContainer.js`**: Provides a form to send messages within a conversation.

## Styles

The `styles` directory contains CSS files for styling individual components.

- **`Conversations.css`**
- **`MessageContainer.css`**
- **`Conversation.css`**
- **`NewConversation.css`**
- **`ConversationCard.css`**
- **`NewMessageContainer.css`**
- **`App.css`**

## Dummy Data

The `DummyData` directory contains JSON files with dummy data for contacts and conversations.

- **`dummycontacts.json`**
- **`dummyConversations.js`**

## App.js

- **`App.js`**: The main component that handles routing and state management using React hooks.

### Clone Project

1. Clone the repository to your local machine.

2. Navigate to the project folder using the terminal.

3. Install dependencies using `npm install`.

4. Start the development server using `npm start`.

5. The app will open in your default web browser at `http://localhost:3000`.

## Dependencies

The project uses the following dependencies:

- React: A JavaScript library for building user interfaces.
- React Router: A library for handling routing within a React application.

