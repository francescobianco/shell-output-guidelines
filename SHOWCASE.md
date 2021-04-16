# Showcase
This file collect a lot of real output useful to perform guidelines study
```
$ curl -Lo setup-bpkg.sh http://get.bpkg.sh/
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0100    94  100    94    0     0    618      0 --:--:-- --:--:-- --:--:--   622
100  2374  100  2374    0     0   7259      0 --:--:-- --:--:-- --:--:--  7259
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
$ bpkg install is

    info: Install /bpkg/is/master from remote https://raw.githubusercontent.com [https://github.com]
    warn: package.json doesn`t exist
    warn: Makefile not found, skipping remote: https://raw.githubusercontent.com/bpkg/is/master
    error: package not found on any remote
? 0
```
```
$ is --help
/home/runner/work/_temp/bc1266f9-d685-4be8-be8c-064d6362a21b.sh: line 14: is: command not found
? 0
```
