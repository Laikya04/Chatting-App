# Chatting-App

This project is a simple clone of WhatsApp's user interface built using Java Swing. It demonstrates basic chat functionality between a client and a server.

## Objective
The objective of the chatting app project is to develop a highly functional and user-friendly messaging application that enables seamless and secure communication among users. The project aims to achieve the following objectives:

**User Engagement :** Create an intuitive and visually appealing user interface that encourages users to engage actively in conversations and explore the app's features.

**Real-time Messaging :** Implement a robust messaging system that allows users to exchange text messages instantly, ensuring a smooth and responsive communication experience.

## Project Structure
The project consists of the following main classes :
- **Client.java:** Handles the client-side operations.
  - Creating the client-side GUI using Java Swing.
  - Establishing a connection with the server.
  - Sending messages to the server.
  - Displaying received messages in the chat area.
   
- **Server.java:** Manages the server-side operations.
  - Creating the server-side GUI using Java Swing.
  - Listening for incoming client connections.
  - Handling multiple clients (though this example shows a basic implementation for a single client).
  - Receiving and displaying messages from the client.
  - Sending messages to the client.
   
- **RoundedButton.java:** A custom JButton class for creating rounded buttons.
    - The `RoundedButton` class is a custom JButton class that creates rounded buttons for a more aesthetically pleasing GUI.
  
## Technologies Used
The following are some commonly used tools and technologies for developing a chatting app in Java:

1. **Programming Language :**  Java - Java provides a robust and platform-independent programming language for developing the backend logic and server-side components of the chatting app.

2. **Integrated Development Environment (IDE) :**  Visual Studio Code. These IDE offer a range of features and tools to facilitate Java development, including code editing, debugging, and project management capabilities.

3. **Java Development Kit (JDK) :**  The JDK includes the necessary tools, libraries, and runtime environment to develop and run Java applications. It includes the Java compiler, runtime environment (JRE), and other essential utilities.
4. **Java Swing :** A GUI widget toolkit for Java.

5. **AWT (Abstract Window Toolkit) :** Used for creating graphical user interfaces.

6. **JSON or XML :**  These formats are commonly used for data exchange between the server and client. They enable efficient serialization and deserialization of data.

7. **Graphical User Interface (GUI) :**  Develop an aesthetically pleasing and intuitive GUI using Java Swing components. Design and implement a layout that facilitates easy navigation, message input, and display of conversations.

## Screenshots
![image](https://github.com/user-attachments/assets/ab8817af-fbd2-4157-93d3-552dc4752b12)

## Future work possible

1. **User Authentication :** Incorporate user authentication functionality to ensure secure access to the app. Implement login and registration features to allow users to create accounts and authenticate themselves.

2. **Friend Management :** Enable users to add, remove, and manage their list of friends or contacts. Implement features for searching and adding new friends within the app.

3. **Multimedia Support :** Allow users to send and receive various media types, such as images, videos, and documents, within their conversations. Implement the necessary functionality to handle multimedia content.

4. **Notification System :** Implement a notification mechanism to alert users of new messages or activities. Display visual or auditory notifications to ensure users are promptly informed about incoming messages.

5. **Chat History :** Implement a feature to store and display chat history, enabling users to review past conversations and scroll through previous messages.
