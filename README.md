# JavaScript Blockchain Implementation

A simple blockchain implementation in JavaScript that demonstrates the core concepts of blockchain technology.

## Overview

This project implements a basic blockchain with the following features:
- Block creation with timestamp, data, and hash
- Genesis block initialization
- Chain validation
- Proof of work (mining) functionality
- Secure hashing using SHA-256

## Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd js-blockchain
```

2. Install dependencies:
```bash
npm install
```

## Usage

Run the blockchain implementation:
```bash
node main.js
```

This will:
1. Create a new blockchain
2. Add two sample blocks with transaction data
3. Display the blockchain structure
4. Validate the blockchain

## Project Structure

- `main.js` - Contains the core blockchain implementation including:
  - `Block` class - Represents individual blocks in the chain
  - `Blockchain` class - Manages the chain of blocks
  - Block validation and mining functionality

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. 