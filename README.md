## 1. Repository Description

This repository provides the API for the "Pet Services E-commerce Website" project. On the back-end side, we use several technologies to support the project, including:

- **NodeJS**: JavaScript runtime for server-side development.
- **Mongoose**: ODM for MongoDB to manage database models.
- **ExpressJS**: Web framework for NodeJS to handle API routes and requests.
- **Redis**: In-memory data structure store for caching and session management.
- **Socket.io**: Real-time communication for messaging and notifications.
- **Nodemailer**: Email sending service for notifications and user communication.
- **Cloudinary**: Media management service for handling images and videos.
- **VNPAY**: Payment integration for online transactions.

## 2. Project Setup

### Installation

- Clone the repository or download the folder.
- Install dependencies:
  - Run `yarn install` if you are using Yarn.
  - Or run `npm install` if you are using npm.

### Running the Project

- To start the server, use:
  - Run `yarn start` if you are using Yarn.
  - Or run `npm run start` if you are using npm.

### Configuration

- Ensure to create and configure a `.env` file with necessary environment variables like MongoDB connection string, Redis settings, VNPAY credentials, Cloudinary API keys, etc.
