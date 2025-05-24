💬 Real-time Chat App

This is a simple real-time chat application built with React on the frontend and Socket.IO on the backend. It allows multiple clients to communicate over different channels in real-time.

🚀 Features
	•	🔗 Real-time communication using WebSockets (Socket.IO)
	•	🧑‍🤝‍🧑 Multiple clients can join and chat simultaneously
	•	📡 Messages are grouped by channels/rooms
	•	💻 Simple React UI for interacting with the chat system

🛠️ Tech Stack
	•	Frontend: React, React Hooks, Tailwind (if applicable)
	•	Backend: Node.js, Express, Socket.IO

⚙️ How it Works
	•	Clients connect to the server via Socket.IO
	•	Each client can join specific channels
	•	Messages sent in a channel are instantly broadcasted to all clients in the same channel
	•	Socket events handle message transmission, user connection, and channel subscriptions
