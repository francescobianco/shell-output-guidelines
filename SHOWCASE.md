# Showcase
This file collect a lot of real output useful to perform guidelines study
```
$ ./get-bpkg.sh
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
$ bpkg install is

    info: Install /bpkg/is/master from remote https://raw.githubusercontent.com [https://github.com]
    warn: package.json doesn`t exist
    warn: Makefile not found, skipping remote: https://raw.githubusercontent.com/bpkg/is/master
    error: package not found on any remote

? 0
```
```
$ ./deps/is/is.sh --help
/home/runner/work/_temp/516e3cbb-a032-42e1-8d6a-f72f3978b1bd.sh: line 16: ./deps/is/is.sh: No such file or directory
? 0
```
