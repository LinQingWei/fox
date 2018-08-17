## Purpose

decompile source code from android phone(android N & Pre)

## Setup

prepare env
```shell
$ cd ~
$ git clone https://github.com/HEZI0427/fox.git
$ mkdir -p ~/bin; cd ~/bin
$ ln -fs ~/fox/fox
$ fox install
```
## Use
#### decompile framework
1. `mkdir system`
2. pull `system/framework/` from android phone, and put it to system dir
3. run `fox decrom all system`
#### decompile app
1. `mkdir system`
2. pull ` system/app/ or priv-app `  dir from android phone, and put it to system dir (must pull framework dir first)
3. run `fox decrom app system system/app/XXX`

