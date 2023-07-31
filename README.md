# Darwin Protocol Token list
 Token list for Darwin Protocol.

 ## HOW TO ADD YOUR TOKEN TO TOKENLIST
 
 #### Application
 Submit pull request by adding your token logo 120X120 PNG at "logos/*chainId*/*tokenAddress*.png", and the token info to "lists/*chainId*.json".
 - Logo
   - Needs to be named with the token address and to be in the respective chain folder (ETH: 1, BSC: 56, ARB: 42161).
   - If logo is not png or exceeds 120X120 it will be rejected.
 - Token Info
   - Needs to be added to the respective chain list (ETH: 1.json, BSC: 56.json, ARB: 42161.json).
   - Needs to respect the format at `example.json`.
 - Submissions with invalid chain address will be rejected.
 - Submissions with multiple tokens will be rejected. One PR per token.
 - Sumbissions that include a token logo but not the token info, or viceversa, will be rejected.
 - PRs will be processed every 3-5 days.


 ## Have more questions?
 Come visit us on discord at our Discord channel. 
 Link: https://discord.gg/darwinprotocol
