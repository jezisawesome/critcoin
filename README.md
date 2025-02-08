# CritCoin 🎲  
**CritCoin** is a memecoin built on Solana, designed to release tokens based on periodic dice rolls using a 5d20 mechanism. With a community-driven approach and transparency baked into its code, CritCoin provides trust and engagement through its tiered token unlock mechanism.  

## Unlock Mechanism  
- **2 natural 20s** → Unlock 1% of the locked dev wallet  
- **3 natural 20s** → Unlock 3% of the locked dev wallet  
- **4 natural 20s** → Unlock 5% of the locked dev wallet  
- **5 natural 20s** → Unlock 100% of the remaining dev wallet (jackpot!)  

Dice rolls occur automatically every **30 seconds**, and results are logged on-chain for transparency.  

## Project Details  
- **Network:** Solana  
- **Smart Contract Language:** Rust  
- **License:** MIT  

## How It Works  
1. Tokens are initially locked in the dev wallet (40% of total supply).  
2. The smart contract rolls 5 d20 dice every 30 seconds using Solana’s blockhash as the seed.  
3. Depending on the number of natural 20s rolled, a percentage of the locked tokens unlocks and is transferred to a designated wallet.  
4. Unlocked tokens are manually managed to ensure no sudden price impact, fostering trust.  

## Development  
See the [docs](./docs/overview.md) folder for a full explanation of the dice-roll mechanics, tokenomics, and contract design.  

