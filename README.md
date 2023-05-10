# Synopsis

This repo is where I keep my environment setup files for MacOS.  Feel free to fork this repo and add your settings to it.

# Requirements

## Install Utilities and Package Dependencies

1. Install Xcode CLI tools

    ```bash
    xcode-select --install
    ```

    > Click `Install` in the popup window and wait for installation to complete

1. Install [HomeBrew](https://brew.sh)

    ```bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

    # Press enter to continue and enter your password when prompted
    ```

1. Install [Anaconda3](https://www.anaconda.com/distribution/)

    > Follow the [instructions](https://docs.anaconda.com/anaconda/install) in the documentation to install           __Anaconda3__, not Anaconda2.
    >
    > *__NOTE:__* It is __strongly advised__ that you install using the [MacOS command line](https://docs.anaconda.   com/anaconda/install/mac-os/#using-the-command-line-install) as this will install Anaconda within your user directory and initialize your shell environment.


# Usage

## Setup HomeBrew

From this repo path run the following to have HomeBrew install the environment in the `Brewfile`

```bash
brew bundle
```

## Setup Vim/MacVim

Link `~/.vimrc` to the `vimrc` file in this directory

```bash
ln -s $(pwd)/vimrc ~/.vimrc
```
