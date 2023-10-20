# need-ssh
`need-ssh` is a simple script to automate ssh-agent authentication

### Prerequisites

- bitwarden-cli
- zsh
- keychain
- openssh
- sshpass

### Installation

```
sudo cp need-ssh /usr/local/bin
```

### One time preperation

Type `bw login` to login to your bitwarden vault.
Bitwarden-cli will now remember your login.
Note:
Use bitwarden-cli to fetch your vault in case 

### Usage

1. Open a new terminal after installation
2. Type `need-ssh`.
3. Type your bitwarden master password.

### Uninstallation

```
sudo rm /usr/local/bin/need-ssh
```
