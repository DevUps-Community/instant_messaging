# Instant Messaging Mini Project

## Objective
Build an instant messaging system for users to communicate with each other.

## Features to Implement
1. **User Registration and Login:**
   - Create user accounts with registration and authentication.
2. **Real-time Messaging:**
   - Implement real-time messaging between users.
3. **Message History:**
   - Store and display message history.

## Description
This project aims to build an instant messaging system for users to communicate with each other.

**Aspects to Consider:**

- **Schema Design:**
  - Plan how to store user messages, chat histories, and real-time updates.
  - Consider how to handle large volumes of messages efficiently.

- **React App Design:**
  - Design components for real-time chat, message history, and notifications.
  - Use a real-time library like Socket.io for instant messaging functionality.

- **Best Practices:**
  - Ensure secure and private communication between users.
  - Implement robust error handling and reconnection logic for real-time communication.
  - Focus on performance optimisation to handle real-time data updates smoothly.

## Technical Requirements
- **Backend:** Node.js with Express and Socket.io
- **Database:** Supabase
- **Frontend:** React

## Steps to Build
1. **Set up the project:**
   - Initialise a new Node.js project.
   - Set up Supabase and connect it to the project.
2. **Authentication:**
   - Implement user registration and login with Supabase Auth.
3. **Messaging API:**
   - Use Socket.io for real-time communication.
   - Create endpoints to fetch message history.
4. **Frontend:**
   - Build React components for registration, login, and messaging.
   - Display real-time messages and message history.
