# INTERACTIVE-QUIZ-APPLICATION

### A REAL-TIME CHATAPPLICATION USING WEBSOCKETS AND A FRONT-END FRAMEWORK REACT.JS.

COMPANY: CODTECH IT SOLUTIONS

NAME: MUGESH M

INTERN ID: CT04DH732

DOMAIN: FRONT END DEVELOPMENT

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION: This real-time chat application is designed as a simple and responsive communication platform using a WebSocket-based architecture. The backend of the application is built using Node.js, Express, and the ws WebSocket library, while the frontend is developed using React and Create React App. This project facilitates real-time message exchange between multiple clients connected to a central WebSocket server, enabling instant messaging with a persistent message history. When a user connects to the WebSocket server, all previous messages are retrieved and displayed, ensuring the new participant has the full chat context. The server listens on port 4000 and handles WebSocket connections by managing message parsing, broadcasting, and automated server responses based on specific keywords such as "hello" or "help". The backend is simple yet efficient, storing message history in memory and sending real-time replies to the client, including server-generated responses.

On the frontend, the application offers a user-friendly chat interface, allowing users to input text messages and view incoming ones in real time without page reloads. The chat interface updates instantly for all connected users whenever a message is sent or received. The React app is started using the command npm start, and it opens on http://localhost:3000. From a development standpoint, the frontend uses standard React packages such as react-dom, react-scripts, and web-vitals, and the backend dependencies include express and ws. No database is integrated at this stage, keeping the application lightweight and focused on showcasing real-time bi-directional communication. This project is especially useful for beginners interested in learning how WebSocket protocols work in tandem with front-end applications. It serves as a basic but solid example of how to implement real-time features without using complex tools like Socket.IO or external messaging queues.

To run the application, the user must first install all dependencies using npm install in both frontend and backend directories. The backend is then started via node server.js or node index.js depending on the implementation file chosen, and the frontend can be served using npm start. The .gitignore file is configured to avoid uploading sensitive or unnecessary files such as node_modules, log files, and environment-specific configurations. While this project does not currently support authentication, emojis, media messages, or persistent database storage, it can be extended with features like user management, message timestamp formatting, message encryption, and even database integration using MongoDB or Firebase. Its modular structure allows for easy feature additions in both the client and server components. By using a WebSocket connection instead of HTTP polling or long-polling methods, the app ensures lower latency and a smoother user experience. For deployment, the frontend can be bundled using npm run build, and the backend can be hosted on platforms such as Render, Heroku, or AWS. This chat application not only demonstrates a clean separation of frontend and backend concerns but also acts as a useful template for building more advanced collaborative tools such as live support systems, multiplayer games, or live coding environments.

## Output
