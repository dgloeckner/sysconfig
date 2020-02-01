# System configuration

This repository contains macOS specific configuration for daily development needs.

## Homebrew

"The missing package manager for macOS". The [first thing to install](https://brew.sh/index) on a new Mac ;)

Makes it a breeze to install and update tools like `git`, ``kubect`, etc.

WIth `brew cask`it's also possible to install macOS applications which are distributed as binaries, e.g. Java.

## Terminal

[iTerm2](https://iterm2.com/features.html) is a great replacement for the standard Terminal application

```brew cask install iterm2```

## Oh My ZSH

ZSH is the default shell on macOS since Catalina. It's a very custimizable shell and you can spend days to create a neat configuration – fortunately there's a whole community behind [Oh My ZSH](https://ohmyz.sh) who already did that for you. This will give you shell completion for popular CLI tools.

This repository provides a `.zshrc` file which enables some useful plugins among other things.

