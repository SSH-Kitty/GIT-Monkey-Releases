<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="docs/assets/banner-light.svg">
  <img alt="Git Grunt: Git and GitHub, without the command line." src="docs/assets/banner-dark.svg" width="100%">
</picture>

<br>

![Version](https://img.shields.io/badge/version-0.1.0-f4a62a?style=flat)
![Platforms](https://img.shields.io/badge/Linux%20%C2%B7%20Windows%20%C2%B7%20macOS-262c3d?style=flat)
![Tauri 2](https://img.shields.io/badge/Tauri-2-24C8DB?style=flat&logo=tauri&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)

**A friendly desktop app for Git and GitHub, made for people who are new to them.**<br>
Commit, push, pull, switch branches, open pull requests and issues, and check Actions runs, all without the command line.

[**Download**](https://github.com/SSH-Kitty/git-grunt-releases/releases/latest) · [Features](#-features) · [Screenshots](#-screenshots) · [Report a bug](https://github.com/SSH-Kitty/git-grunt-releases/issues)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/screenshots/changes-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="docs/screenshots/changes-light.svg">
  <img alt="Git Grunt Changes view showing a file diff" src="docs/screenshots/changes-dark.svg" width="100%">
</picture>

</div>

<br>

## 👷 Why Git Grunt

Git is powerful, but its error messages assume you already know Git. Git Grunt does the grunt work for you: it shows
what changed in plain colors, tells you what each step does as you go, and when Git reports an error it **explains it
in plain English and offers a one-click fix**.

Under the hood it runs the real `git` and `gh` (GitHub CLI) commands, so everything it does matches the command line
exactly. Nothing is hidden and nothing is locked in.

<img src="docs/assets/divider.svg" width="100%" alt="">

## ✨ Features

<table>
<tr>
<td width="33%" valign="top">
<img src="docs/assets/icon-commit.svg" width="44" alt=""><br>
<b>Commit with confidence</b><br>
Tick the files you want, write what you did, and save a snapshot. Green lines are new, red lines were removed.
</td>
<td width="33%" valign="top">
<img src="docs/assets/icon-sync.svg" width="44" alt=""><br>
<b>Push and pull</b><br>
See at a glance what's waiting to go up or come down, and sync with GitHub in one click.
</td>
<td width="33%" valign="top">
<img src="docs/assets/icon-branch.svg" width="44" alt=""><br>
<b>Branches made simple</b><br>
Create and switch branches from a menu. When changes clash, Git Grunt walks you through combining them.
</td>
</tr>
<tr>
<td valign="top">
<img src="docs/assets/icon-pr.svg" width="44" alt=""><br>
<b>Pull requests</b><br>
Open pull requests, see their review and check status, and try out their code on your computer.
</td>
<td valign="top">
<img src="docs/assets/icon-issue.svg" width="44" alt=""><br>
<b>Issues</b><br>
Read and write issues with attachments, assignees, labels, projects and milestones. Open and closed views.
</td>
<td valign="top">
<img src="docs/assets/icon-actions.svg" width="44" alt=""><br>
<b>GitHub Actions</b><br>
Watch your checks and release builds run after every push, and open any run on GitHub.
</td>
</tr>
<tr>
<td valign="top">
<img src="docs/assets/icon-help.svg" width="44" alt=""><br>
<b>Errors in plain English</b><br>
Git's cryptic messages turned into clear help, with a one-click fix for the common ones.
</td>
<td valign="top">
<img src="docs/assets/icon-editor.svg" width="44" alt=""><br>
<b>Built-in editor</b><br>
Browse your project's files and make quick edits with syntax highlighting.
</td>
</tr>
</table>

Plus light and dark themes, a built-in title bar, and an update checker so you're always on the latest version.

<img src="docs/assets/divider.svg" width="100%" alt="">

## 📸 Screenshots

<table>
<tr>
<td width="50%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/history-light.svg"><img src="docs/screenshots/history-dark.svg" alt="History view"></picture><p align="center"><sub><b>History</b>: every snapshot on the branch, newest first</sub></p></td>
<td width="50%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/files-light.svg"><img src="docs/screenshots/files-dark.svg" alt="Files view with editor"></picture><p align="center"><sub><b>Files</b>: browse and edit with syntax highlighting</sub></p></td>
</tr>
<tr>
<td width="50%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/issues-light.svg"><img src="docs/screenshots/issues-dark.svg" alt="Issues view"></picture><p align="center"><sub><b>Issues</b>: bugs, ideas and to-dos with labels</sub></p></td>
<td width="50%"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/actions-light.svg"><img src="docs/screenshots/actions-dark.svg" alt="Actions view"></picture><p align="center"><sub><b>Actions</b>: checks and builds after each push</sub></p></td>
</tr>
<tr>
<td colspan="2"><picture><source media="(prefers-color-scheme: light)" srcset="docs/screenshots/errhelp-light.svg"><img src="docs/screenshots/errhelp-dark.svg" alt="Error explained in plain English"></picture><p align="center"><sub><b>Errors in plain English</b>: what went wrong, and a one-click fix</sub></p></td>
</tr>
</table>

<img src="docs/assets/divider.svg" width="100%" alt="">

## 📦 Install

Grab the installer for your system from the [**Releases**](https://github.com/SSH-Kitty/git-grunt-releases/releases/latest) page:

| System | File |
|--------|------|
| 🐧 Linux | `.AppImage`, `.deb` or `.rpm` |
| 🪟 Windows | `.msi` or `-setup.exe` |
| 🍎 macOS | `.dmg` |

> [!NOTE]
> Builds are unsigned for now, so Windows SmartScreen and macOS Gatekeeper show a warning the first time the app is
> opened.

### Requirements

- [Git](https://git-scm.com/downloads)
- [GitHub CLI](https://cli.github.com) (`gh`). Git Grunt signs you in through it on first launch.

<img src="docs/assets/divider.svg" width="100%" alt="">

### Updates

Git Grunt checks this page for new versions and offers a one-click update from inside the app.

## 🐞 Feedback

Found a bug or have an idea? [Open an issue](https://github.com/SSH-Kitty/git-grunt-releases/issues). Git Grunt is closed source; this repository hosts the downloads, screenshots and issue tracker.

<br>

<div align="center">
<img src="docs/assets/icon.svg" width="56" alt="Git Grunt logo"><br>
</div>
