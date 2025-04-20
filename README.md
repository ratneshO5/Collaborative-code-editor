# Collaborative Code Editor

A real-time collaborative code editor that enables multiple users to write and edit code simultaneously. Built with a modern tech stack, it offers seamless code synchronization and a user-friendly interface.

## 🌟 Features

- 🔄 **Real-Time Collaboration** – Multiple users can edit the same code with instant updates.
- 🎨 **Syntax Highlighting** – Language-specific highlighting for better readability.
- 🧑‍🤝‍🧑 **Room-Based Sessions** – Create or join rooms for focused coding.

## 🛠 Tech Stack

- **Frontend**: React.js, Monaco Editor, HTML, CSS
- **Backend**: Node.js, Express.js, Socket.IO
- **Real-Time Communication**: WebSockets via Socket.IO
- **Version Control**: Git

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ratneshO5/Collaborative-code-editor.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Collaborative-code-editor
   ```

3. **Install dependencies**:

   - Backend:
     ```bash
     cd backend
     npm install
     ```

   - Frontend:
     ```bash
     cd ../frontend
     npm install
     ```

### Running the Application

Start both the frontend and backend in separate terminals from the root directory:

1. **Backend** (from root):
   ```bash
   npm run dev
   ```

2. **Frontend** (from root):
   ```bash
   cd ./frontend/
   npm run dev
   ```

## 🧪 Usage

- **Create Room**: Start a new collaborative session and share the room ID.
- **Join Room**: Enter an existing room ID to join a live coding session.
- **Edit Code**: Write and edit code with others in real time.

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repo
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add YourFeature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request 🎉

Made with ❤️ by [Ratnesh](https://github.com/ratneshO5)
