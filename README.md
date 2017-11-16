# Cisco VPN Connect

## Installing

First make sure that you have `openconnect` package installed.

Edit `cisco-tool` and fill with your data. After, copy to your `~/bin` directory and run

with zsh:
```
$ echo 'export PATH="$PATH:$HOME/bin"' >> ~/.zshrc
```

with bash:
```
$ echo 'export PATH="$PATH:$HOME/bin"' >> ~/.bashrc
```

## Running

Connect:
```
$ cisco-tool connect
```

Disconnect:
```
$ cisco-tool disconnect
```
