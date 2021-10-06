# NFT-drop-bulk
WIP => NFT bulk drop

This script assumes all NFTs have decimal 0 

To run:

- yarn install
- yarn start
- Login with sollet
- Select a token (it must be a token other than SOL for this to work) 
- Select Send
- Upload a csv( comma separated) file with each row as: destination_address,amount,associated_token_address,token_mint_address
- If a transaction(tx) fails the receiver address will be logged in the error box (This bit is still in development and is being fixed) 

# Potential Upgrades

- For this bulk-distributor version  tx errors still need to dealt with 

- Get all associated token account addresses and mint addresses for the logged in account and allow for export to csv, speeding up user's ability to bulk send

