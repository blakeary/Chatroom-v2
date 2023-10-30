# RealtimeChat

RealtimeChat is a chat application that enables users to communicate in real-time. It is built with Node.js and uses Express for the web server framework, Socket.io for WebSocket communication, and Redis for efficient message broadcasting.

## Features

- Real-time two-way communication between clients and server
- Use of Redis for scalable WebSocket communication
- Environmental variables for secure configuration
- Timestamps for messages using Moment.js

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- npm (Node Package Manager)
- Redis server running on the default port (6379)

### Installing

First, clone the repository to your local machine:

```bash
# Install dependencies
npm install

# Start the application
npm start
