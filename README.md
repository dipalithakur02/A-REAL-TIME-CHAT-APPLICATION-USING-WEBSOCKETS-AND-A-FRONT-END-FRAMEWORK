# A-REAL-TIME-CHAT-APPLICATION-USING-WEBSOCKETS-AND-A-FRONT-END-FRAMEWORK

*COMPANY*: CODTECH IT SOLUTIONS 

*NAME*: DIPALI

*INTERN ID*: CT04DF1379

*DOMAIN*: FRONT END DEVELOPMENT

*DURATION*: 4 WEEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*: The Real-Time Chat Application is a dynamic and interactive web-based project designed to facilitate instant communication between users. Built using a combination of Node.js, Express, Socket.io, and React.js, this application demonstrates the power of real-time web technologies and modern front-end frameworks. The backend, powered by Node.js and Express, serves as the server that handles client connections and message broadcasting, while Socket.io enables real-time, bidirectional communication between the server and clients. The frontend, developed with React.js, provides a responsive and user-friendly interface for sending and receiving messages. The application allows multiple users to join a chat room, send messages, and see those messages appear instantly on their screens without the need for refreshing the page. This project is an excellent example of how modern web technologies can be combined to create seamless, real-time user experiences.

The backend of the application is built using Node.js, a runtime environment that allows JavaScript to be executed on the server side. Express.js, a popular web framework for Node.js, is used to create the server and handle HTTP requests. Socket.io, a library that enables real-time communication, is integrated into the backend to manage WebSocket connections. When a user sends a message, the frontend emits a send_message event to the server, which then broadcasts the message to all connected clients using the receive_message event. This ensures that all users in the chat room receive the message instantly. The backend also logs user connections and disconnections, providing insights into the active users in the chat room. The use of CORS (Cross-Origin Resource Sharing) ensures that the frontend, running on a different port, can securely communicate with the backend.

On the frontend, React.js is used to build a dynamic and responsive user interface. React's component-based architecture makes it easy to manage the state of the application and update the UI in real-time. The socket.io-client library is used to establish a connection between the frontend and the backend. When a user types a message and clicks the "Send" button, the message is emitted to the server using the send_message event. The server then broadcasts the message to all connected clients, and the frontend updates the chat window to display the new message. Messages sent by the user are displayed differently from messages received from other users, providing a clear visual distinction. The frontend also includes a scrolling message window, ensuring that users can always see the latest messages without manually scrolling.

This project is not only a practical demonstration of real-time communication but also a great learning tool for understanding how different technologies can be integrated to build a full-stack application. It covers key concepts such as WebSocket communication, event-driven programming, state management in React, and responsive design. The application can be extended with additional features such as user authentication, private messaging, typing indicators, and message persistence using a database. It can also be deployed to a cloud platform, making it accessible to users worldwide. Overall, the Real-Time Chat Application is a versatile and engaging project that showcases the potential of modern web development technologies.

## OUTPUT

<img width="1915" height="598" alt="Image" src="https://github.com/user-attachments/assets/43fb838e-4fa8-4158-b453-bd432b4146e0" />

