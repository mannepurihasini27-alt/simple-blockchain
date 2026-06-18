# Simple Blockchain

A simple blockchain implementation in Python that demonstrates the core concepts of blockchain technology, including block creation, cryptographic hashing, Proof of Work (PoW), and chain validation.

## Features

- Create and store blocks in a blockchain
- SHA-256 hashing for secure block identification
- Proof of Work mining mechanism
- Chain integrity validation
- Genesis block creation
- Tamper detection

## Technologies Used

- Python 3
- hashlib
- json
- time

## Project Structure

```text
simple-blockchain/
│
├── blockchain.py
├── README.md
└── .gitignore
```

## How It Works

1. A Genesis Block is created.
2. New blocks are added with transaction data.
3. Each block stores:
   - Index
   - Timestamp
   - Data
   - Previous Hash
   - Current Hash
   - Nonce
4. Proof of Work is used to mine blocks.
5. The blockchain can be validated to ensure data integrity.

## Running the Project

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/simple-blockchain.git
```

Navigate to the project directory:

```bash
cd simple-blockchain
```

Run the program:

```bash
python blockchain.py
```

## Sample Output

```text
Block Mined!
Hash: 0000ab12cd34...

Blockchain Valid: True
```

## Learning Objectives

This project was developed to understand:

- Blockchain fundamentals
- Cryptographic hashing
- Proof of Work consensus
- Data integrity and security
- Distributed ledger concepts

## Author

Hasini Mannepuri
