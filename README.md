# Money Tracker

Money Tracker is a simple and intuitive application designed to help you track your income and expenses. Built with Node.js, Express, and MongoDB, this application allows users to add and manage transactions through a web interface.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- Add income and expense transactions.
- View a list of all transactions.
- Delete transactions.

## Technologies

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [EJS](https://ejs.co/)
- [Body-Parser](https://github.com/expressjs/body-parser)
- [Method-Override](https://github.com/expressjs/method-override)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/money-tracker.git
   cd money-tracker
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up your MongoDB connection:**
   - Create a `.env` file in the root directory and add your MongoDB connection string:
     ```
     MONGODB_URI=mongodb+srv://your-username:your-password@your-cluster.mongodb.net/database-name
     ```

4. **Run the application:**
   ```bash
   npm start
   ```

   The server will start on `http://localhost:3000`.

## Usage

- Visit `http://localhost:3000` in your web browser.
- Add your transactions by providing a description, amount, and type (income or expense).
- View the list of all transactions on the main page.
- Delete a transaction by clicking the "Delete" button next to it.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.
