# Personal Expense Tracker

### Technologies
- Node.js
- Express.js
- SQLite

### Setup Instructions
1. Clone the repository: `git clone <repo-url>`
2. Install dependencies: `npm install`
3. Run the server: `node app.js` or `npx nodemon app.js`

### API Endpoints

#### POST /api/transactions
Create a new transaction.

#### GET /api/transactions
Get all transactions.

#### GET /api/transactions/:id
Get a transaction by ID.

#### PUT /api/transactions/:id
Update a transaction by ID.

#### DELETE /api/transactions/:id
Delete a transaction by ID.

#### GET /api/summary
Get summary of income, expenses, and balance.
