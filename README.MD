# Lint

**WORK IN PROGRESS: This language is not finished.**

It's like Forth, but in python & im basically copying **[Porth](https://gitlab.com/tsoding/porth)**.

## TODO
- [x] Compilable
- [x] Native
- [x] Stack-based
- [ ] Turing complete
- [ ] Statically typed
- [ ] Self-hosted (Written in itself when it is mature enough) 

## Quick Start

### Dependencies
```console
$ sudo apt-get update -y
$ sudo apt-get install nasm -y
$ sudo apt-get install bintuils -y

**If you get an error like: /usr/bin/env: ‘python3\r’: No such file or directory**

$ sudo apt-get install dos2unix -y
$ sudo dos2unix ./lint.py
```

### Linux Executable Permissions
```console
$ sudo chmod +x ./lint.py
$ sudo chomod +x ./output
```

### Compilation & Simulatioon (May need permissions)
```console
$ ./lint.py com ./examples/test.lint
$ ./lint.py sim ./examples/test.lint
$ ./output
```
