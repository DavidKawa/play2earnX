# Play2EarnX Project Documentation

LINE ID: davidkawa1991
Mail:    kawasaki19910113@gmail.com

<!-- Read the full tutorial here: **[>> How to build a Decentralized Game Platform with Next.js, TypeScript, Tailwind CSS, and Solidity](https://daltonic.github.io)** -->

The project revolves around `Play2EarnX.sol`, a Solidity-written Ethereum smart contract. It leverages the OpenZeppelin library to ensure secure and standardized development of the contract.

The core of the contract is defined by four primary structures: `GameStruct`, `PlayerStruct`, `InvitationStruct`, and `ScoreStruct`, representing a game, a player, an invitation, and a score, respectively.

## Key Features

- `createGame`: Allows a user to create a new game.
- `deleteGame`: Allows the game owner to delete a game.
- `invitePlayer`: Allows a user to invite another player to a game.
- `acceptInvitation`: Allows a user to accept an invitation to a game.
- `rejectInvitation`: Allows a user to reject an invitation to a game.
- `payout`: Distributes payouts to the winners of a game.
- `saveScore`: Records a player's score in a game.

## Running the Application

Supply the following keys in your `.env` variable:

```sh
NEXT_PUBLIC_RPC_URL=http://127.0.0.1:8545
NEXT_PUBLIC_ALCHEMY_ID=<YOUR_ALCHEMY_PROJECT_ID>
NEXT_PUBLIC_PROJECT_ID=<WALLET_CONNECT_PROJECT_ID>
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=somereallysecretsecret
```

`YOUR_ALCHEMY_PROJECT_ID`: [Get Key Here](https://dashboard.alchemy.com/)
`WALLET_CONNECT_PROJECT_ID`: [Get Key Here](https://cloud.walletconnect.com/sign-in)

Follow these steps to run the application:

1. Install the package modules by running the command: 
```bash
 yarn install
```
2. Spin up the Next.js development server: 
```bash
yarn dev
```


Now, your application should be up and running.

## 📚 Key Technologies

- 🌐 Next.js: A React framework for building server-side rendered and static websites.
- 📘 TypeScript: A statically typed superset of JavaScript.
- 📦 Hardhat: A development environment for Ethereum smart contracts.
- 🌐 EthersJs: A library for interacting with Ethereum and Ethereum-like blockchains.
- 📚 Redux-Toolkit: A library for managing application state.
- 🎨 Tailwind CSS: A utility-first CSS framework.

## Useful links

- 🏠 [Website](https://dappmentors.org/)
- ⚽ [Metamask](https://metamask.io/)
- 💡 [Hardhat](https://hardhat.org/)
- 📈 [Alchemy](https://dashboard.alchemy.com/)
- 🔥 [NextJs](https://nextjs.org/)
- 🎅 [TypeScript](https://www.typescriptlang.org/)
- 🐻 [Solidity](https://soliditylang.org/)
- 👀 [EthersJs](https://docs.ethers.io/v5/)

