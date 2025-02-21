# zkzyraStealthDEX  
![GitHub](https://img.shields.io/github/license/Zyra-V23/zkzyraStealthDEX)
**Private trading protocol with hybrid ZK proofs**  
✨ *"Trade like a ghost, settle like a hurricane"* ✨

## Features ✨
- 🕵️ **Stealth Orders**: Encrypted orders via LIT Protocol
- ⚡ **Hybrid ZK Engine**: Choose between STARKs (privacy) or SNARKs (speed)
- 🛡️ **MEV Blocker**: Batch settlements with fair ordering

## Tech Stack 🛠️
- **Core**: Solidity 0.8.22, Circom 2.1.9
- **Infra**: Foundry, Hardhat, IPFS
- **Security**: Certora, Echidna, Halmos

## Quickstart 🚀
#```bash
# 1. Clone repo
git clone https://github.com/zyra-v23/zkzyraStealthDEX.git

# 2. Install dependencies
npm install && forge install

# 3. Run testnet node
anvil --silent & 

# 4. Deploy contracts
forge script DeployZkzyra --broadcast
