---
title: Customize Terminal for Mac by iTerm2 Part I:Install Requirements
date: 2024-10-10 20:48:12
---

Part2 will come soon.
## 1. Install required software
### 1.1 Install Homebrew and Git
#### 1.1.1 Install Homebrew
If you can't make sure that you have installed Homebrew,open your terminal and try this:
```bash
brew -v
```
If homebrew has installed,it shows "**Homebrew 4.1.2(your homebrew vision)**", which means you have installed homebrew and then you can skip to  **1.2 Install iTerm2**.

If not, try this in your terminal to install Homebrew:
```bash
 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
### 1.1.2 Install git
Try this to see if you have installed git
```bash
git --version
```
If it shows"**git version 4.2.3(your git vision)**", please skip to  **1.2 Install iTerm2**.

If not, try this to install：
```bash
brew install git
```
### 1.2 Install iTerm2
Try this in your terminal to install iTerm2
```bash
brew install iterm2
```

Also you can install iTerm2 through [iTerm Official website](https://iterm2.com/downloads.html)


