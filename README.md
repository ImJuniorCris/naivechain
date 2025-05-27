# Naive-Chain

A simple, educational blockchain implementation for learning and experimentation.

## About

Naive-Chain is a basic blockchain project designed to help users understand core blockchain concepts through a minimal and readable codebase.

## Features

- Minimal blockchain implementation in JavaScript
- Block creation and validation
- Simple peer-to-peer network using WebSockets
- Educational code with clear comments

## Getting Started

### Prerequisites

- Node.js (v12 or above)
- npm

### Installation

Clone the repository:

```bash
git clone https://github.com/TartarusDevtech/Naive-Chain.git
cd Naive-Chain
```

Install dependencies:

```bash
npm install
```

### Usage

Start the blockchain node:

```bash
node main.js
```

You can run multiple instances on different ports to simulate a network:

```bash
PORT=3001 node main.js
PORT=3002 node main.js
```

## Configuration

You can set the `PORT` environment variable to run multiple nodes:

```bash
PORT=3001 node main.js
```

## API Endpoints

- `GET /blocks` - Returns the blockchain
- `POST /mineBlock` - Mines a new block with posted data
- `GET /peers` - Lists connected peers
- `POST /addPeer` - Connects to a new peer

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or new features.

## License

This project is licensed under the MIT License.
