---
layout: post
title:  "Install Yay: Yet another yogurt"
date:   2022-11-24 12:30:00 +0100
categories: Arch-Linux
tags: tutorials arch packages yay
pin: false
toc: true
---

```zsh
# Install the needed packages
sudo pacman -Syu git base-devel

# Change into the tmp directory. Here the sources will get cleaned automatically
cd /tmp

# Clone the repository
git clone https://aur.archlinux.org/yay.git

# Navigate into the cloned repository
cd yay

# Build and install yay
makepkg -si
```