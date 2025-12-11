# Impostor Game

A multiplayer web game similar to Among Us, built with React and Tailwind CSS.

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

### Development

Run the development server:
```bash
npm run dev
```

Open your browser and navigate to `http://localhost:5173` (or the URL shown in the terminal).

### Build

Build for production:
```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

## How to Play

1. **Setup**: Enter names for 3-7 players and select a category
2. **Reveal Roles**: Players take turns holding the reveal button to see their word
   - **Civilians** see the specific word (e.g., "Lion")
   - **The Impostor** sees a vague hint (e.g., "Wild Beast")
3. **Describe**: Players take turns giving 1-sentence clues about their word
4. **Vote**: After 3 rounds, vote on who is the Impostor
5. **Results**: See if the Impostor was caught or escaped!

## Features

- 🎮 Multiplayer gameplay (3-7 players)
- 🎯 4 themed categories: Animals, Places, Food, Objects
- ⏱️ 20-second turn timer
- 🔐 Secret word assignment for civilians and deceptive hints for the impostor
- 🎨 Beautiful dark-themed UI with smooth animations
- 📱 Mobile-friendly design

## Game Rules

- One random player is secretly chosen as the Impostor
- Civilians see the real secret word
- The Impostor sees only a vague hint
- Each player takes a turn describing the word without being too obvious
- After 3 rounds, everyone votes on who they think is the Impostor
- If the Impostor is voted out, the Civilians win!
- If the Impostor survives the vote, they win!