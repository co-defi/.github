# Co-DeFi

**Co-DeFi** is a DeFi platform utilizing the VultiSig co-signing protocol, enabling users to create multisig multidevice multichain wallets. Co-DeFi matches different peers in DeFi who wish to hold their assets and increase their yields without the need to swap their assets.

## Features

- **VultiSig Protocol**: Create secure multisig wallets across multiple devices and chains.
- **Peer Matching**: Match with peers to collaboratively provide liquidity without needing to trust each other.
- **Flexible Security Options**: Choose between 2-out-of-2 and 2-out-of-3 vaults depending on your security and automation needs.

## How It Works

Co-DeFi ensures secure and trustless participation in DeFi by using the VultiSig protocol to create shared vaults between matched peers. 

### Vault Options

- **2-out-of-2 Vault**: Highest security, requiring both peers to sign off on every transaction.
- **2-out-of-3 Vault**: Simplified and automated flow, with Co-DeFi holding the third key to facilitate transactions.

### Peer Matching and Liquidity Provision

1. **Peer Matching**:
    - User A wants to provide $100 in Rune.
    - User B wants to provide $100 in USDC.
    - Co-DeFi verifies that User A holds $100 in Rune and User B holds $100 in USDC.
    - Co-DeFi matches User A and User B and helps create a 2-out-of-2 vault.

2. **Secure Deposit Process**:
    - Both users need to sign a withdrawal transaction before depositing assets to ensure security if the other peer does not fulfill their part.
    - User A deposits $100 in Rune into the shared vault.
    - If User B does not deposit USDC in the given time, User A can withdraw their Rune.
    - User B deposits $100 in USDC into the shared vault.
    - If User A does not deposit Rune in the given time, User B can withdraw their USDC.

3. **Liquidity Provision**:
    - Both User A and User B sign two add liquidity transactions for Rune and USDC deposits simultaneously.

## Why Trust Co-DeFi?

Users don't need to trust each other because the VultiSig protocol ensures secure transactions. In a 2-out-of-2 vault, each transaction requires signatures from both parties. This way, if one party acts maliciously, the other can revert the transaction.

### Example Flow

1. User A wants to provide $100 in Rune.
2. User B wants to provide $100 in USDC.
3. Co-DeFi verifies the assets and matches the users.
4. Users create a 2-out-of-2 vault and sign pre-agreed withdrawal transactions.
5. User A deposits Rune, and User B deposits USDC into the vault.
6. Both users sign add liquidity transactions for Rune and USDC.

## Getting Started

To get started with Co-DeFi, follow these steps:

1. **Sign Up**: Create an account on the Co-DeFi platform.
2. **Verify Assets**: Verify your assets with Co-DeFi.
3. **Match with Peers**: Find and match with peers who have complementary assets.
4. **Create Vault**: Set up a multisig vault and deposit assets.
5. **Provide Liquidity**: Sign transactions and start earning yields.

## Contributing

We welcome contributions to Co-DeFi! Please read our [Contributing Guidelines](CONTRIBUTING.md) for more information.

## License

Co-DeFi is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or support, please contact us at support@codefi.com.

---

**Co-DeFi**: Maximizing DeFi yields through secure, collaborative liquidity provision.
