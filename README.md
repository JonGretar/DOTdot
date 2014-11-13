# DOTdot

## Description

## Setup

### Bash Config

Install bash-completion brew

	brew install bash-completion2

Source the bash init in your `~/bash_profile`.

	source ~/.dot/bash.d/init

For best experience install the latest Bash:

	brew install bash
	echo "/usr/local/bin/bash" | sudo tee -a /etc/shells
	chsh -s /usr/local/bin/bash

### Other Config Files

Symlink the rest of the dot files to your home directory.
*Alternatively symlink just the files you want.*

	ln -s $HOME/.dot/linkable.dotfiles/* $HOME/

## Usage

### Bash Completions

Additionally DOTdot loads Homebrew installed completions. To get a list of installable completions issue the command:

	brew search -completion
