# Universal Account Tutorial

This tutorial demonstrates how to integrate Particle Network's Universal Accounts into your dApp.

## Features

1. **Wallet Connection**
   - Connect with MetaMask
   - Handle wallet state and events

2. **Universal Account Creation**
   - Initialize Universal Account with user's EOA
   - Configure account settings

3. **Account Information**
   - View EVM address
   - View Solana address
   - Check account unified balance

4. **Cross-Chain Transactions**
   - Execute a simple BNB purchase
   - Handle transaction states and errors
   - View transaction details

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   # or
   yarn
   ```

2. Configure environment variables:
   Create a `.env.local` file:
   ```
   NEXT_PUBLIC_UA_PROJECT_ID=your_project_id
   ```

3. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

## Learning Steps

1. **Connect Wallet**
   - The app starts by requesting MetaMask connection
   - User's EOA address is captured and displayed

2. **Initialize Universal Account**
   - A Universal Account instance is created using the connected wallet
   - Account configuration is set up

3. **View Account Information**
   - The app fetches and displays both EVM and Solana account addresses
   - Account balances are retrieved and shown

4. **Execute Transactions**
   - Users can initiate a simple BNB purchase
   - Transaction progress and results are clearly displayed

Check the guide on the [Particle Docs](https://docs.particle.network/overview/universal-accounts).