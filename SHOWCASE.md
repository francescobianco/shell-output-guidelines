# Showcase
This file collect a lot of real output useful to perform guidelines study
```
$ curl -Lo setup-bpkg.sh http://get.bpkg.sh/
? 0
```
```
$ bash setup-bpkg.sh
  info: Welcome to the 'bpkg' installer!
  info: Checking for git...
? 0
```
```
$ rm -f setup-bpkg.sh
? 0
```
```
$ bpkg install umq -g

    info: Install /bpkg/umq/master from remote https://raw.githubusercontent.com [https://github.com]
    info: Cloning https://github.com/bpkg/umq.git to umq-master
Your branch is up to date with 'origin/master'.
    info: Performing install: `env PREFIX=/home/runner/.local make install'
rm -f umq
ln -s push.sh umq-push
ln -s recv.sh umq-recv
ln -s help.sh umq-help
ln -s umq.sh umq
  +bin
  +doc
? 0
```
```
$ ump --help
? 0
```
