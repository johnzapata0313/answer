# Message Board Demo

A simple message board application built with Node.js, Express, and MongoDB featuring thumbs up/down voting functionality.

## Features

- Create and view messages
- Thumbs up/down voting system
- Real-time vote tracking
- MongoDB database integration

## Technologies Used

- **Node.js** - JavaScript runtime
- **Express** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling

## Prerequisites

Before running this application, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (running locally or MongoDB Atlas account)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/johnzapata0313/answer-SaveageDemo.git
cd answer-SaveageDemo
```

2. Checkout the answer branch:
```bash
git checkout answer
```

3. Install dependencies:
```bash
npm install
```

4. Create a `.env` file in the root directory and add your MongoDB connection string:
```
MONGODB_URI=mongodb://localhost:27017/messageboard
PORT=3000
```

## Usage

1. Start the application:
```bash
npm start
```

2. Open your browser and navigate to:
```
http://localhost:3000
```

3. Start posting messages and voting!

## API Endpoints

- `GET /` - View all messages
- `POST /messages` - Create a new message
- `PUT /messages/:id/upvote` - Add thumbs up to a message
- `PUT /messages/:id/downvote` - Add thumbs down to a message

## Project Structure

```
answer-SaveageDemo/
├── models/          # Database models
├── routes/          # API routes
├── public/          # Static files
├── views/           # View templates
├── server.js        # Main application file
└── package.json     # Project dependencies
```

## Contributing

Feel free to fork this project and submit pull requests with improvements!

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

John Zapata - [GitHub](https://github.com/johnzapata0313)
