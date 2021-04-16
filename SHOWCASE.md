# Showcase
This file collect a lot of real output useful to perform guidelines study
```
$ curl -Lo get-bpkg.sh http://get.bpkg.sh/
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0100    94  100    94    0     0    386      0 --:--:-- --:--:-- --:--:--   386
100  2374  100  2374    0     0   8508      0 --:--:-- --:--:-- --:--:--  8508
? 0
```
```
$ bash get-bpkg.sh
  info: Welcome to the 'bpkg' installer!
  info: Checking for git...

  info: Creating temporary files...
  warn: Already exists: '/tmp/bpkg-master'
  info: Fetching latest 'bpkg'...
  info: Installing...

  info: Uninstalling /home/runner/.local/bin/bpkg...
  info: Installing /home/runner/.local/bin/bpkg...
  info: Done!
? 0
```
```
$ bpkg install is@main

    info: Install /bpkg/is/main from remote https://raw.githubusercontent.com [https://github.com]
    warn: package.json doesn`t exist
    warn: Makefile not found, skipping remote: https://raw.githubusercontent.com/bpkg/is/main
    error: package not found on any remote

? 0
```
```
$ is --help
/home/runner/work/_temp/534b0bed-a4a3-4db5-a9cf-6fdf1b897803.sh: line 15: is: command not found
? 0
```
