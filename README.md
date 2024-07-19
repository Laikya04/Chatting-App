# Chatting-App

This project is a simple clone of WhatsApp's user interface built using Java Swing. It demonstrates basic chat functionality between a client and a server.

## Objective
The objective of the chatting app project is to develop a highly functional and user-friendly messaging application that enables seamless and secure communication among users. The project aims to achieve the following objectives:

**User Engagement :** Create an intuitive and visually appealing user interface that encourages users to engage actively in conversations and explore the app's features.

**Real-time Messaging :** Implement a robust messaging system that allows users to exchange text messages instantly, ensuring a smooth and responsive communication experience.

## Features
**Real-time Chat :**
  1. Clients can send and receive messages in real-time.
  2. Messages are displayed with timestamps.
     
**Graphical User Interface (GUI) :**
  1. The application uses Java Swing for creating a user-friendly interface.
  2. Customizable background, fonts, and colors to mimic WhatsApp's interface.
     
**Message Formatting :**
  Messages are formatted with a sender's name, timestamp, and are color-coded.
  
**Send and Receive Media :**
  Supports sending and receiving media like images (e.g., smiley icons).

**Socket Programming :**
  1. Utilizes sockets for client-server communication.
  2. Handles multiple clients through socket connections.

**Custom Buttons :**
  1. Rounded buttons for sending messages and media.
  2. Custom icons for various actions like send, call, video call, and more.

**Responsive UI :**
  The user interface adapts to different screen sizes and resolutions.

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

## Usage
**Setup :**
  - Ensure you have Java Development Kit (JDK) installed.
  - Clone the repository to your local machine.

**Running the Server :**
  - Navigate to the project directory.
  - Compile the Server.java file : 
    - javac Server.java
  - Run the server :
    - java Server
  - The server will start listening for client connections on port 1234.
    
**Running the Client :**
  - Open another terminal or command prompt.
  - Navigate to the project directory.
  - Compile the Client.java file :
    - javac Client.java
  - Run the client:
    - java Client
  - The client will attempt to connect to the server. Ensure the server is running and accessible.

**Using the Application :**
  - Once the client connects to the server, the chat interface will appear.
  - Type messages in the text field at the bottom and press the send button (paper plane icon) to send messages.
  - Messages will appear in the chat area with the sender's name and timestamp.
  - Use the call and video call buttons for additional functionalities (implementation required).
  - To close the client, click the back arrow icon at the top left.

**Customization :**
  - Background images and icons can be changed by replacing the corresponding files in the project directory.
  - Modify the Color, Font, and layout settings in the Client.java and Server.java files to customize the appearance.

## Screenshots
![image](https://github.com/user-attachments/assets/ab8817af-fbd2-4157-93d3-552dc4752b12)

## Future work possible

1. **User Authentication :** Incorporate user authentication functionality to ensure secure access to the app. Implement login and registration features to allow users to create accounts and authenticate themselves.

2. **Friend Management :** Enable users to add, remove, and manage their list of friends or contacts. Implement features for searching and adding new friends within the app.

3. **Multimedia Support :** Allow users to send and receive various media types, such as images, videos, and documents, within their conversations. Implement the necessary functionality to handle multimedia content.

4. **Notification System :** Implement a notification mechanism to alert users of new messages or activities. Display visual or auditory notifications to ensure users are promptly informed about incoming messages.

5. **Chat History :** Implement a feature to store and display chat history, enabling users to review past conversations and scroll through previous messages.
