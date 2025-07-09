# 🐝 TokensHive

**Building secure, blazing-fast Web3 tooling for the Solana ecosystem and beyond.**

Welcome to **TokensHive**, an open-source hub where engineers and builders craft the next generation of decentralized applications. Our mission: provide powerful, audited tools that make Web3 development **simpler, faster, and safer** for everyone.

---

## 🚀 What We’re Building

### 🔑 [Hive Wallets](https://github.com/TokensHive/hive-wallets)

> **Encryption-first vanity Solana wallet generator (Go CLI)**

- Generate Solana Ed25519 key-pairs that match comma-separated prefix/suffix filters (case-insensitive & 1337 look-alikes optional).
- Multi-core brute-force engine with -workers and -timeout flags for full CPU control.
- Outputs a single AES-256 OpenPGP–encrypted .json.gpg file—keys are unreadable without your pass-phrase.
- Companion decrypt command to restore the clear JSON whenever you need it.
- Written in Go, cross-compiles for macOS / Linux / Windows, released under the MIT license.

Hive Wallets lets you craft custom Solana addresses and store them safely—all in one command.

---

### ⚙️ SDKs for Solana (Coming Soon)

> **Plug-and-play libraries to supercharge dApp development**

- Web3 utility packages
- Instruction fees estimation
- Priority fees precise calculation (DEX and writable addresses)
- Multi DEX transaction and accounts parsers
- Multi DEX transaction instruction builders

Whether you’re coding a DeFi protocol or an NFT marketplace, our SDKs save weeks of development time while keeping your stack secure and scalable.

---

### 🚚 [Tx Dispatcher] (API Access only)

> **Fast, reliable transaction dispatching to the Solana network**

- High-performance transaction forwarding
- WebSocket, HTTP, and gRPC support
- Bi-directional transaction process, immediate status streaming on transaction receival
- API-key based multi-tenant architecture
- Built-in ACLs for IPs, CIDRs, and allowed domains
- Supports tracking transaction status across multiple RPC nodes and Shredsteam

Tx Dispatcher ensures your transactions hit the Solana network quickly and reliably, even under heavy load.

---

## ✨ Why TokensHive?

✅ **Open Source SDKs and utilities.**  
✅ **Battle-tested code, written for performance.**  
✅ **Focused on developer experience and elegant APIs.**  
✅ **Active engineering team eager to collaborate.**

We’re not just building tools—we’re building infrastructure that empowers **all builders** in Web3.

---

## 💛 Contribute

We believe the best software comes from **community collaboration.** Found a bug? Want to contribute features? Or simply have ideas for new Solana tooling? [Open an issue](https://github.com/TokensHive) or reach out via discussions. Let’s make Web3 better together!

---

## 📫 Connect

- Twitter: [@TokensHive](https://twitter.com/TokensHive)
- Discord: [TokensHive Community](https://discord.gg/tokenshive)
- Website: [www.tokenshive.com](https://www.tokenshive.com)

**Build with us. The hive is buzzing. 🐝**
