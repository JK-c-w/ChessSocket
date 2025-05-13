# ♟️ Real-Time Chess Game

A real-time multiplayer chess game built with **Node.js**, **Express**, **Socket.IO**, and **Chess.js**. Two players can compete as White and Black, while others can spectate the game live.

---

## 🚀 Features

- ⚡ **Real-Time Multiplayer Gameplay**
- 🎭 **Automatic Role Assignment** — First two users become players; others spectate
- ✅ **Legal Move Validation** — Powered by `chess.js`
- ♟️ **Drag & Drop Chess Interface**
- 🔄 **Live Updates for All Clients**
- 🏁 **Check, Checkmate, and Draw Detection**
- 👀 **Spectator Mode**

---

## 📁 Project Structure

index.js
package.json
public/
  Script/
    socket.js
  Style/
    chess.css
  views/
    index.ejs


### 📄 File Descriptions

- `index.js`: Server setup with Express, Socket.IO, and game logic
- `views/index.ejs`: Main game UI template (EJS)
- `public/Script/socket.js`: Handles client-side socket events and drag-and-drop logic
- `public/Style/chess.css`: Styles for the board, pieces, and animations
- `package.json`: Project dependencies and scripts

---

## 🧠 How It Works

1. ✅ **Server Setup**: Uses Express and Socket.IO for handling connections.
2. 🎮 **Player Assignment**: First two users are players, others are spectators.
3. 🧠 **Move Validation**: Server uses `Chess.js` to check if moves are legal.
4. 🔁 **Board Updates**: All moves are broadcast to keep the game synchronized.
5. 🏁 **End Game Logic**: Detects checkmate, stalemate, and draws.

---

## 🛠️ Installation
1. **Clone the repository:**
   git clone <repository-url>
   cd ChessGame
2. **Install Dependencies:** git install
3. **Start the server:** npx nodemon
4. **Visit Browser:** http://localhost:3000

## 📦 Dependencies

🧱 Express — Server framework.

🔌 Socket.IO — WebSocket-based communication.

♟️ Chess.js — Library for chess move validation and game state management.

🖼️ EJS — Server-side rendering.

## 🌱 Future Improvements

⏱️ Add timer and blitz mode.

🧾 Save game history to a database.

🔐 Add user login, player profiles, and ELO rating.

🎨 Add themes, sounds, and animated effects.

## 📄 License
Licensed under the ISC License. Feel free to use, modify, and contribute! 🙌

