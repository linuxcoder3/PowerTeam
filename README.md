# PowerTeam
# Installation
```bash
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install libreadline-dev libssl-dev lua5.2 liblua5.2-dev git make unzip redis-server curl
```

**We are going now to install LuaRocks and the required Lua modules**

```bash
$ wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz
$ tar zxpf luarocks-2.2.2.tar.gz
$ cd luarocks-2.2.2
$ ./configure; sudo make bootstrap
$ sudo luarocks install luasocket
$ sudo luarocks install luasec
$ sudo luarocks install redis-lua
$ sudo luarocks install lua-term
$ sudo luarocks install serpent
$ sudo luarocks install dkjson
$ cd ..
```

**Clone the repository and give the permissions to start the launch script**

```bash

```
