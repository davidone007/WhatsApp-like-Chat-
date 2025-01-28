
# WhatsApp-like Chat with WebSockets, React, and Spring Boot

This is a real-time chat application, similar to WhatsApp, using WebSockets for bidirectional communication between the client (React) and the server (Spring Boot). Messages are not persisted and are lost when the app is closed.

## Features

- **Real-time messaging:** Instant message updates via WebSockets.
- **User authentication:** Users can sign up and log in to use the chat.
- **Session-based:** Messages are lost after the session ends (app is closed).
  
## Technologies

- **Frontend:** React, WebSocket, Axios
- **Backend:** Spring Boot, WebSocket
- **Database:** No persistence (messages are not stored)

## Setup

### Backend (Spring Boot)

1. Clone the backend repository:

   ```bash
   git clone https://github.com/your_user/whatsapp-chat-backend.git
   cd whatsapp-chat-backend
   ```

2. Run the project with Maven:

   ```bash
   mvn spring-boot:run
   ```

   The backend will be available at `http://localhost:8080`.

### Frontend (React)

1. Clone the frontend repository:

   ```bash
   git clone https://github.com/your_user/whatsapp-chat-frontend.git
   cd whatsapp-chat-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the frontend:

   ```bash
   npm start
   ```

   The frontend will be available at `http://localhost:3000`.

## Usage

- Users can register and log in with a username.
- Messages are sent in real-time via WebSockets.
- Messages are lost after the session ends.

## Contributing

Feel free to open issues or submit pull requests!

