---
sidebar_position: 1
---

# Soarchain Explorer Staking Guide

**Please note:** All of this is still in the experimental stage and we do not endorse nor encourage staking/delegating just yet, so use it at your own risk.

## Important Precautions

- **Do NOT use your main Keplr keys for Soarchain.** We are still in the testnet stage, and not all security features for mainnet are deployed in production.
- Please only use your Soarchain-mobile-app generated 24 words.

## Setup Instructions

1. **Keplr Wallet Setup**
    - Go to Keplr browser extension and click **"Import an existing wallet"**.
    - Click **"Use recovery phrase or private key"**.
    - Copy and Paste your 24 words.
    - Complete the setup wallet stages on Keplr if you haven't done already.
    - Click **"Save"**. Note: You don't need to select any chains except for ATOM just yet; you won't find Soarchain there since the testnet is not yet in Keplr.
2. **Soarchain Explorer**
    - Navigate to [explorer.soarchain.com](https://explorer.soarchain.com/).
    - Ensure you see `https://api.devnet.soarchain.com (0.45.5)` below the search bar. **Caution**: Do not use `https://api.testnet.soarchain.com`. (Yes the testnet API is currently serving devnet and devnet API is currently serving testnet we will fix this issue soon)
    - Click **"Wallet"** on the top right-hand side > **"Import Address"** > Select **"Keplr"** > Click **"Enable Keplr"**.
    - Click **"Approve"** to add Soarchain testnet as a custom chain to your Keplr wallet extension.
    - Back on the explorer, Click **"Next"** > Name your account > Click **"Next"** > Click **"Save"** > You should see "Address Saved" popup notification.
3. **Staking Tokens**
    - Visit [Soarchain Staking](https://explorer.soarchain.com/soar/staking).
    - Pick a validator and click **"Delegate"**.
    - In the "Delegate Token" popup, enter an amount under "Amount" and press **"Send"**.
    - In the Keplr popup, press **"Approve"**. Mind the fee; you can set it to low, but it might not pass.
4. **Adding tSOAR in Keplr**
    - Go to **"Manage Chain Visibility"** > Type "soar" and pick "soar" > Save. Note: This step can also be done at the beginning.
    - In the Keplr app, click **"Staked"** to see your staked tokens.

**Reminder**: We do not recommend replicating this process if you have no prior experience in adding tokens to Keplr manually and using ping.pub style explorers.