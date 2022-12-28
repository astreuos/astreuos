
# Astreuos Whitepaper

### A Next Generation Blockchain that adjusts Transaction Fees, Block Limits and Storage Fees to Maintain Network Sustainability & Maximize Network Utilization.

# History

## Blockchain

## Bitcoin

## Ethereum

## Web 3.0

# Astreuos

## Blocks

Structure:
1. Data
    - Number
    - Previous Block Hash
    - Timestamp
    - Solar Limit
    - Solar Used
    - Solar Price
    - Solar Fees
    - Accounts Root Hash
    - Transactions Root Hash
    - Receipts Root Hash
    - Storage Root Hash
    - Reward
2. Validator Signature

## Accounts

Types:
1. User
2. Application

Structure:
1. Counter
2. Balance
3. Code ID
4. Storage ID

#### Special Accounts

| Account | Address |
|---|---|
| Nova | 0x0000nova |
| Nebula | 0x0000nebula |
| Burn | 0x0000burn |


#### Balance

The standard unit of value is a Quanta while the smallest unit is a Quark.

Value magnitudes:-

- 10^24: Yottaquark / Quanta
- 10^21: Zettaquark
- 10^18: Exaquark
- 10^15: Petaquark
- 10^12: Teraquark
- 10^9: Gigaquark
- 10^6: Megaquark
- 10^3: Kiloquark
- 10^0: Quark

## Transactions

Types:
1. Standard
2. App Creation
3. App Call

Structure:
1. Data
    - Type
    - Recipient
    - Value
    - Counter
    - Solar Price
    - Solar Limit
    - Data
2. Sender Signature

## Receipts

Structure:
1. Transaction Hash
2. Status
3. Solar Used

## Pulsar - Peer to Peer Messaging Protocol

### Access Port
UDP PORT 7577

## Fusion - Blockchain Application Platform

Main Components:-
1. Fusion Language, Functional Programming Language.
2. Reactor, Virtual Stack Machine.
3. Plasma, Fusion Language to Reactor Code Compiler.
4. Helium, Code Manager.

### Fusion Language

Types :-
1. Integer
2. Floating Point
3. Boolean
4. String
5. List
6. Tuple
7. Record

Control Flow :-
1. Conditional
    - If
    - Case
2. Loop
    - While
    - For

Standard Library (std) :-
1. Mathematics (math)
    - Addition -> add(10, 8)
    - Subtraction -> sub(10, 8)
    - Multiplication -> mul(2, 2)
    - Division -> div(10, 2)
    - Remainder -> rem(10, 2)
    - Modulo -> mod(-21, 4)
    - Exponentiation -> pow(2, 8)

2. String (str) :-

3. List (list) :-
    - Dedup

4. Accounts (acc) :-
    - Create -> create(0xFFFF)
    - Balance -> balance(0xFFFF)
    - Storage (storage)
        - Put -> put(0xFFFF, "key", "value")
        - Get -> get(0xFFFF, "key")
        - Delete -> delete(0xFFFF, "key")

### Reactor - Virtual Stack Machine

Op Codes :-
1. General
    - Stop
2. Memory
    - Put
    - Get
3. Account
    - Create
    - Balance
    - Storage Put
    - Storage Get
    - Storage Delete
4. Arithmetic
    - Addition
    - Subtraction
    - Multiplication
    - Division
    - Remainder
    - Modulo
    - Exponentiation
    - Modular Inverse
5. Comparison
    - Less Than
    - Greater Than
    - Equal To
6. Bitwise
    - Not
    - And
    - Or
    - Xor

## Nova - Proof of Stake Consensus Protocol

### Block Time
1 second.

### Slot Allocation

### Validator Selection

### Block Reward
1 quanta for every billion solar limit on the block.

## Nebula - Storage Platform

### Storage Fee
The initial storage fee is 130 yottaquarks for 3 months per 256Kb chunk of data.

### Standard Storage Contract
3 month period storage contract.

### Retrieval Fee 
The initial retrieval fee is 21.6 yottaquarks per 256Kb chunk of data.

# Applications

## Smart Contracts

## Digital Tokens (Virtual Currencies & NFTs)

## Oracles

## DAOs

## Distributed Storage

# Roadmap
| Project | Description | Delivery |
|---|---|---|
| [Stellar Notation](https://github.com/seg-software/rust-stellar-notation) | Data Encoding | ✅ |
| [NeutronDB](https://github.com/seg-software/rust-neutrondb) | Key Value Store | ✅ |
| [Opis](https://github.com/seg-software/rust-opis) | Integer Arithmetic | ✅ |
| [Fides](https://github.com/seg-software/rust-fides) | Digital Signature Library | 🚧 |
| Pulsar Network | Messaging System |  TBD |
| Fusion | Decentralized Applications | TBD |
| Nova Protocol| Proof of Stake | TBD |
| Nebula | Storage Protocol | TBD |
| [Terminal](https://github.com/astreuos/astreuos-terminal) | Network Interface | TBD |
| Testnet Launch | | Q4 2021 |
| Mainnet Launch | | Q1 2022 |

2021-11-30