## .env

Non-comprehensive list of tools I use across all my workstations.



## macOS Setup

#### Install Oh My Zsh (via [ohmyz.sh](https://ohmyz.sh))

```bash
$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

*Notes:*

- to make it default shell, run `$ chsh -s $(which zsh)`



#### Download latest, officially released version of Xcode and latest beta (via [xcodereleases.com](https://xcodereleases.com/))

*Notes:* 

- be sure to install *Command Line Tools for Xcode* (also installed by homebrew)



#### Install Homebrew (via [brew.sh](https://brew.sh))

```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```



#### Install m-cli (via [rgcr/m-cli](https://github.com/rgcr/m-cli))

```bash
$ brew install m-cli
```



#### Install `rbenv` (via [rbenv/rbenv](https://github.com/rbenv/rbenv#installation))

```bash
$ brew install rbenv
```

*Notes*:

- be sure to run `$ rbenv init` after install and update `~/.zshrc` as needed.
- Use `rbenv` to install latest/necessary ruby versions via `$ rbenv install 2.6.5`



#### Install Bundler (via [bundler.io](https://bundler.io))

```bash
$ gem install bundler
```

*Notes:*

- If you see file permission errors, be sure to use `rbenv` to change global ruby version prior to installing bundler.



#### Install useful macOS Quick Look plugins (source: [sindresorhus](https://github.com/sindresorhus/quick-look-plugins))

```bash
$ brew cask install qlcolorcode qlstephen qlmarkdown quicklook-json
```



## Other useful tools and applications

... in no particular order

- SublimeText 
  - Install Package Control, Pretty JSON 
- Keybase
- Google Chrome
- Postman
- 1Password
- Slack
- Typora