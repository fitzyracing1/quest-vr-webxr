# Quest VR WebXR

GitHub-ready WebXR starter for Meta Quest and browser VR with A-Frame, Express, and Socket.IO.

## Features

- Immersive WebXR scene using A-Frame
- Real-time multiplayer state with Socket.IO
- Procedural chunk generation + easter eggs
- In-world internet portals and web dock
- Local LAN hosting for Quest headset testing

## Tech Stack

- Node.js
- Express
- Socket.IO
- A-Frame

## Quick Start

### 1) Install dependencies

```bash
npm install
```

### 2) Start in development mode

```bash
npm run dev
```

### 3) Or run production mode

```bash
npm start
```

Open:

- Local: http://localhost:3000
- Quest on same network: use the LAN URL printed in terminal

## Project Structure

```text
.
├── public/
│   ├── index.html
│   └── js/
│       └── app.js
├── server.js
├── package.json
└── README.md
```

## Scripts

- `npm run dev`: start with nodemon (auto-restart on file changes)
- `npm start`: start Node server

## Roadmap

- Add user-authenticated rooms
- Persist world edits to storage
- Add spawnable URL portals from a searchable catalog

## Contributing

See CONTRIBUTING.md for development and PR guidelines.

## License

MIT (see LICENSE)
