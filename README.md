# Setup Environment

## Enable Git

- Enable git:

```zsh
git -v
```

## Install Homebrew

```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew update
```

- Checkout:

```zsh
# Brew path
export PATH="/opt/homebrew/bin:$PATH"
```

## Install Oh my zsh

```zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install NVM

```zsh
brew install nvm
```

- Checkout:

```zsh
# NVM path
export NVM_DIR=$(brew --prefix nvm)
[ -s $NVM_DIR/nvm.sh ] && . $NVM_DIR/nvm.sh
```

## Python alias

```zsh
# Python alias
alias python='python3'
alias pip='pip3'
```
