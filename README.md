Metacrafters in this challenge, I have created Degen_Gaming Smart Contract

Overview
The Degen_Gaming smart contract is designed to manage a gaming token called "Degen" (symbol: DGN). It includes functionalities for minting, transferring, burning tokens, checking balances, and redeeming rewards. Only the command center (contract deployer) can mint new tokens.

Features
Token Name and Symbol
Minting Tokens
Transferring Tokens
Burning Tokens
Checking Balance
Redeeming Rewards

Functions
constructor()
mint(uint amount, address receiver_address)
transfer(uint amount, address receiver_address)
burn(uint amount)
Check_Balance(address user_address)
redeem(uint reward_ID)
getRedeemedItems(address user)
