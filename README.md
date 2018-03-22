# Installing

All scripts should be copied to `~/bin`. Other than this, `~/bin` directory should be added at `$PATH` env var. If you already don't have, you can do it

with zsh:
```
$ echo 'export PATH="$PATH:$HOME/bin"' >> ~/.zshrc
```

with bash:
```
$ echo 'export PATH="$PATH:$HOME/bin"' >> ~/.bashrc
```

# Cisco VPN Connect

## Installing

First make sure that you have `openconnect` package installed.

Edit `cisco-tool` and fill with your data. After edit, copy to your `~/bin` directory and run

## Running

Connect:
```
$ cisco-tool connect
```

Disconnect:
```
$ cisco-tool disconnect
```

# Docker Cleanup

This script remove older containers, images and volumes. Be careful, it can remove data from your volumes.

## Installing

Just copy to your `~/bin` dir.

## Running

Just run
```
$ docker-cleanup
```
