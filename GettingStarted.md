## Getting Started

To get started with Blynk, follow these instructions to set up the project on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) (v6 or later)
- [MongoDB](https://www.mongodb.com/) (for local development)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/arindal1/blynk-mern-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd blynk-mern-app
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Install frontend dependencies and build the frontend:

   ```bash
   npm run build
   ```

5. Set up your environment variables:

   Create a `.env` file in the root of the project and add the following:

   ```
   PORT=5000
   MONGO_DB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   MODE_ENV=development
   ```

### Running the Application

To start the development server, use:

```bash
npm run server
```

To build and start the production server:

```bash
npm run build
npm start
```

### Deployment

Blynk is deployed using [Render](https://render.com/). You can access the live application [here](www.example.com).

## Usage

After setting up and running the application, you can:

1. **Sign Up:** Create a new account.
2. **Log In:** Access your account with your credentials.
3. **Send Messages:** Start chatting with other users in real-time.
