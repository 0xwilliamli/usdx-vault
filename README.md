# Documentation

This is a vault system that leverages the USDT/USDC token to get high yield.

User deposits tokens to the vault. vault deposit or withdraw tokens to the strategy contract based on current assets and position of strategy.

Now the system consists of mainly 2 parts: vault token(share token) and strategy.

- Vault

Vault Token (eg xvUSDT)  is a share token that proves your contribution to the liquidity.

Vault contract manages the funds user deposited

The deposited assets are in the vault and when signaled, they are deposited to the strategy.

Vault has several functions that report the strategy status like position and get available assets and predict assets.
