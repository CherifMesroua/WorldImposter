# Word Imposter Game

A multiplayer word game where players try to identify the imposter who doesn't know the secret word.

## Project Structure

The project is divided into two main parts:

- **Client**: React-based front-end
- **Server**: Node.js/Express back-end with Socket.io for real-time communication

## How to Play

1. One player creates a game room
2. Other players join using the room code
3. Each player submits 5 related words
4. One player is secretly assigned as the imposter
5. Players take turns asking questions about the secret word
6. After the question rounds, everyone votes on who they think is the imposter
7. The game reveals the imposter and the secret word

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository
2. Install dependencies for both client and server:

```bash
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
