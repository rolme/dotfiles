# .files

This is a configuration repository to get a new MacOSX up and running

## Installation

```zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/rolme/.files/master/install)"
```

## Generating new SSH keys

Generate [SSH keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) for new installations.

## Configuring Oh-My-Zsh

Clone this repo into your home directory. This will allow oh-my-zsh to access the custom themes, plugins. and resource files.

```zsh
git clone git@github.com:rolme/.files.git
```

link .zshrc into home directory

```zsh
ln -s ~/.files/oh-my-zsh/.zshrc ~/.zshrc
```

Specific customizations that exists only for target machine can be placed in .z