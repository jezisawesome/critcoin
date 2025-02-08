# CritCoin Overview 🎲  

## Unlock Mechanism Details  
- **5 d20 dice:** Each dice roll has a 1/20 chance of hitting a natural 20.  
- **Randomness Source:** Solana’s blockhash is used as the seed for generating pseudo-random dice rolls.  

### Unlock Tiers  
| Success Condition | % of Locked Dev Wallet Unlocked | Tokens Unlocked (Assuming 400M Locked) |  
|-------------------|----------------------------------|---------------------------------------|  
| 2 natural 20s      | 1%                              | 4M tokens                             |  
| 3 natural 20s      | 3%                              | 12M tokens                            |  
| 4 natural 20s      | 5%                              | 20M tokens                            |  
| 5 natural 20s      | 100%                            | Remaining balance unlocked           |  

## Security Considerations  
- **Transparency:** All dice rolls are logged on-chain, and token unlocks are auditable.  
- **Manual Controls:** The unlocked tokens are transferred to a designated wallet, allowing manual management to avoid large sell-offs.

## License  
CritCoin is released under the **MIT License**, allowing open-source usage and contributions.  
