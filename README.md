# beldex-wallet-generator
Beldex/Monero/Aeon/Townforge offline wallet generator

This page generates a new Beldex, Monero, Aeon or Townforge address. It is self contained and does all the necessary calculations locally, so is suitable for generating a new wallet on a machine that is not connected to the network, and may even never be. This way, you can create a wallet without risking the keys.

You can also create same wallet seed and recreate same later by using own long phrase in the `Custom entropy for deterministic wallet` field.
The phrase used as `Custom entropy` you must have stored safely and never share with anyone. You can generate multiple deterministic wallets with the use of suffix like   
{phrase}bdx1  
{phrase}bdx2  

But Beldex like Monero support multiple accounts and addresses in the single wallet so this is not recommended unless you really need/want to have a separate wallet file 100% isolated from other accounts.
