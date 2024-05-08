# Financial Advisor



## 🛠 Technologies

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [axios](https://axios-http.com/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Plaid API](https://plaid.com/)
- [Jest](https://jestjs.io/)

## Getting started

To get started with this application, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/kad31057/financial-advisor.git
cd financial-advisor
```

2. Install backend dependencies:

```bash
cd server
npm install # or 'yarn install'
```

3. Install frontend dependencies:

```bash
cd ../client
npm install # or 'yarn install'
```

4. Set up your environment variables in a `.env` file located in the `server` directory (refer to `.env.sample` for additional information):

```plaintext
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=
MONGODB_CLUSTER_URL=
```

**All user information will be stored in the specified MongoDB cluster. If you do not have a MongoDB cluster URL, you can use this app in demo mode, which will utilize mock data.**

5. Run the backend:

```bash
npm run start # or 'yarn start'
# to run in demo mode, which uses a mock database, use 'npm run start:demo' or 'yarn start:demo'
```

6. In a new terminal, start the frontend:

```bash
cd client
npm run start # or 'yarn start'
```

7. Open [http://localhost:3000](http://localhost:3000) in your browser.

Here you can link your bank accounts and start tracking your financial transactions and account balances. The dashboard provides a comprehensive overview of your finances, including detailed visualizations of your cash flows and transactions.

## :memo: License

This project is under the [MIT License](https://github.com/karamvirr/personal-financial-management/blob/main/LICENSE).
