# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
$ brew install git
```

### Stow

```
$ brew install stow
```

## Installation

First, check out the dotfiles repo in you $HOME directory using git

```
$ git clone git@github.com/LotteFiber/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
