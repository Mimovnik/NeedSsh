### Prerequisites
- bitwarden-cli
- zsh
- oh my zsh
- xclip
- keychain
- openssh

### Instalation
```
chmod +x install.zsh
./install.sh
```

### Use

##### Get password from bitwarden vault
1. Open new terminal.
2. Type `bw login` to login to your bitwarden vault.
3. Type `bwcopy <your bitwarden password name>`.
4. Type in your bitwarden master password.
    Now you have your password in the clipboard. If that was your goal you're done.

##### Start an ssh agent
5. With your ssh password in the clipboard type `need-ssh`.
6. Paste your password from the clipboard.
   Done.

#### Note
In case need-ssh ask for a password outside a terminal via kssaskpass you can try to disable it by:
1. uninstalling kssaskpass
2. appending `unset SSH_ASKPASS;` in your `.zshrc` manually or using this command: `echo "unset SSH_ASKPASS;" >> ~/.zshrc"

