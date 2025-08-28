# Simple Storage

## Project Description

Simple Storage is a Solidity smart contract that demonstrates fundamental blockchain storage capabilities. This contract allows users to store and retrieve different data types including strings, numbers (uint256), and boolean values on the Ethereum blockchain. Each user can store their own set of data, creating a personalized storage space that is immutable and transparent.

## Project Vision

Our vision is to provide a foundational understanding of blockchain storage mechanisms while showcasing how smart contracts can handle multiple data types efficiently. This project serves as a stepping stone for developers learning Solidity and demonstrates the core principles of decentralized data storage.

## Key Features

- **Multi-Type Storage**: Store strings, numbers, and boolean values in a single transaction
- **User-Specific Data**: Each Ethereum address maintains its own storage space
- **Data Retrieval**: Retrieve your own data or query other users' stored information
- **Event Logging**: All storage operations emit events for transparency and tracking
- **Gas Optimized**: Efficient storage patterns to minimize transaction costs
- **Security**: Built-in access controls and safe data handling practices

## Future Scope

### Phase 1 - Enhanced Data Types
- Support for arrays and structs
- Complex data structure storage (mappings within structs)
- Date/timestamp storage capabilities

### Phase 2 - Advanced Features
- Data encryption and privacy features
- Access control mechanisms (private vs public data)
- Data sharing permissions between users
- Data versioning and history tracking

### Phase 3 - Integration & Scaling
- Integration with IPFS for large data storage
- Layer 2 solutions for reduced gas costs
- Cross-chain compatibility
- RESTful API for easy integration

### Phase 4 - Enterprise Features
- Multi-signature data management
- Role-based access control
- Data backup and recovery mechanisms
- Analytics and reporting dashboard

## Installation & Usage

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Hardhat framework

### Setup
1. Clone the repository
2. Install dependencies: `npm install`
3. Compile contracts: `npx hardhat compile`
4. Deploy to local network: `npx hardhat run scripts/deploy.js --network localhost`

### Contract Functions

#### `storeData(string, uint256, bool)`
Stores three different data types for the caller's address.

#### `retrieveData()`
Returns all stored data for the caller's address.

#### `retrieveUserData(address)`
Returns stored data for a specific user address.

## Contributing

We welcome contributions! Please feel free to submit issues, feature requests, or pull requests to help improve this project.

## License

This project is licensed under the MIT License.<img width="1814" height="1063" alt="Screenshot 2025-08-28 123756" src="https://github.com/user-attachments/assets/220cde27-5d94-4b61-b9a6-530507f0e02c" />

