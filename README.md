# Token Vesting DApp Frontend

A decentralized application (DApp) frontend for managing token vesting schedules. Built with Next.js, Tailwind CSS, and Web3.

## Features

- Connect wallet using MetaMask
- Register organizations and their tokens
- Add stakeholders with custom vesting schedules
- Claim tokens after vesting period
- User-friendly interface with real-time updates

## Tech Stack

- Next.js 13+ with App Router
- Tailwind CSS for styling
- shadcn/ui for UI components
- Web3.js for blockchain interactions
- TypeScript for type safety

## Prerequisites

- Node.js 16.8 or later
- MetaMask browser extension
- Access to an Ethereum network (local or testnet)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/walcruise/vesting-dapp-frontend.git
   cd vesting-dapp-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env.local
   ```
   Then edit `.env.local` with your contract addresses and network settings.

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
src/
├── app/                 # Next.js app directory
├── components/          # React components
│   └── token-vesting/   # Vesting-specific components
├── lib/                 # Utility functions and configurations
└── styles/             # Global styles
```

## Components

- `WalletConnect`: Handles wallet connection via MetaMask
- `OrganizationRegistration`: Form for registering new organizations
- `StakeholderManagement`: Interface for managing stakeholders and vesting schedules
- `TokenClaim`: Component for claiming vested tokens

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
