# Popula Overview
Popula is the infrastructure devoted to the Web3 Community Economy, leading a new paradigm for the Creator Economy powered by open-source protocols.

[testnet.popula.io](https://testnet.popula.io)

# Team Bio: 
27 Squad (27s), a team made up entirely of Web3 believers and builders, including crypto entrepreneur, senior researcher, Tech Geeks, marketing experts, creative designer, and of course, community contributors.

# Components:
### Main contract (https://github.com/popula-io/popula-contract)

The main protocol of Popula, which can be recogonized to a unique community, and contains verifiable social functions and data.
### Community (https://github.com/popula-io/community)

Template code for community, it can be deployed by community genesis. Contains basic functions for a content community.
### Drip (https://github.com/beepopula/Drip-contract)
Records every account's drips for diferrent communities. Using NTT(Non-Transferable-Token) along with drip generation functions.


### Community genesis (https://github.com/popula-io/community-genesis)

A community contract factory, records every community, upgrades codes, re-deploy communities, migrate community's states.


### Frontend (https://github.com/popula-io/popula_frontend)

Receives sorted messages from backend and send transactions to contracts.

### Backend (https://github.com/popula-io/popula_server)

Filter, sort and response frontend's requests. 

### Indexer (https://github.com/popula-io/popula_indexer)

Index and store Popula related transactions and receipts for every blocks received from rpc. near-lake-framework integrated.


# Crates
### near-non-transferrable-token (https://crates.io/crates/near-non-transferrable-token)
The core traits of NTT. Removes transfering functions, add on reputation usage functions like ft_deposit.

### near-fixed-bit-tree (https://crates.io/crates/near-fixed-bit-tree)
An implementation of alternative binary tree with fixed length
