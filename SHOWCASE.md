# Showcase
This file collect a lot of real output useful to perform guidelines study
```
$ curl -Lo setup-bpkg.sh http://get.bpkg.sh/
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0100    94  100    94    0     0    269      0 --:--:-- --:--:-- --:--:--   268100    94  100    94    0     0    269      0 --:--:-- --:--:-- --:--:--   268
100  2374  100  2374    0     0   4691      0 --:--:-- --:--:-- --:--:--  4691
? 0
```
```
$ bash setup-bpkg.sh
  info: Welcome to the 'bpkg' installer!
  info: Checking for git...

  info: Creating temporary files...
  info: Fetching latest 'bpkg'...
  info: Installing...

  info: Uninstalling /home/runner/.local/bin/bpkg...
  info: Installing /home/runner/.local/bin/bpkg...
  info: Done!
? 0
```
```
$ rm -f setup-bpkg.sh
? 0
```
```
$ bpkg install umq -g

    info: Install /bpkg/umq/master from remote https://raw.githubusercontent.com [https://github.com]
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
    info: Cloning https://github.com/bpkg/umq.git to umq-master
Cloning into 'umq-master'...
Already on 'master'
Your branch is up to date with 'origin/master'.
    info: Performing install: `env PREFIX=/home/runner/.local make install'
install: cannot create regular file '/home/runner/.local/share/man/man1': No such file or directory
install: cannot create regular file '/home/runner/.local/share/man/man1': No such file or directory
install: cannot stat 'umq-help.1': No such file or directory
install: cannot create regular file '/home/runner/.local/share/man/man1': No such file or directory
make: *** [Makefile:19: install] Error 1
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
/home/runner/work/_temp/aaf9a95a-d2b8-4a9d-9d77-8f1fbebc5a75.sh: line 14: ump: command not found
? 0
```
