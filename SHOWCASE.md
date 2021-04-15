# Showcase
This file collect a lot of real output useful to perform guidelines study
```shell
$ curl -Lo setup-bpkg.sh http://get.bpkg.sh/
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0100    94  100    94    0     0    472      0 --:--:-- --:--:-- --:--:--   472
100  2374  100  2374    0     0  10059      0 --:--:-- --:--:-- --:--:-- 10059
? 0
```
```shell
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
```shell
$ rm -f setup-bpkg.sh
? 0
```
```shell
$ bpkg install umq

[36m    info[0m: [0m[1mInstall /bpkg/umq/master from remote https://raw.githubusercontent.com [https://github.com]
[0m/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
[36m    info[0m: [0m[1mInstall dependencies for umq
[0m[36m    fetch[0m: [0m[1mhttps://raw.githubusercontent.com/bpkg/umq/master/umq.sh
[0m[36m    write[0m: [0m[1m/home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/umq/umq.sh
[0m[36m    umq to PATH[0m: [0m[1m/home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/bin/umq
[0m[36m    fetch[0m: [0m[1mhttps://raw.githubusercontent.com/bpkg/umq/master/recv.sh
[0m[36m    write[0m: [0m[1m/home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/umq/recv.sh
[0m[36m    recv to PATH[0m: [0m[1m/home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/bin/recv
[0m[36m    fetch[0m: [0m[1mhttps://raw.githubusercontent.com/bpkg/umq/master/push.sh
[0m[36m    write[0m: [0m[1m/home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/umq/push.sh
[0m[36m    push to PATH[0m: [0m[1m/home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/bin/push
[0m[36m    fetch[0m: [0m[1mhttps://raw.githubusercontent.com/bpkg/umq/master/help.sh
[0m[36m    write[0m: [0m[1m/home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/umq/help.sh
[0m[36m    help to PATH[0m: [0m[1m/home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/bin/help
[0m? 0
```
```shell
$ ump --help
/home/runner/work/_temp/54619542-0c1f-48b9-9ed2-9635efc6fe8a.sh: line 14: ump: command not found
? 127
```
