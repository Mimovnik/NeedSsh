### Prerequisites
- bitwarden-cli
- zsh
- oh my zsh
- xclip
(All available on Manjaro with AUR enabled)

### Instalation
Put `bwpassword` in `/usr/local/bin`. Put `ssh-agent.zsh` in `$ZSH_CUSTOM` directory.

### Use

##### Get password from bitwarden vault
1. Open terminal.
2. Type `bwpassword <your bitwarden password name>`.
3. Type in your bitwarden master password.
    Now you have your password in the clipboard. If that was your goal you're done.

##### Start an ssh agent
4. With your ssh password in the clipboard type `need-ssh`.
5. Paste your password from the clipboard.
   Done.
