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
$ bpkg install qzb/is.sh

    info: Install /qzb/is.sh/master from remote https://raw.githubusercontent.com [https://github.com]
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
/home/runner/.local/bin/bpkg-json: line 172: printf: write error: Broken pipe
    info: Install dependencies for is.sh
    fetch: https://raw.githubusercontent.com/qzb/is.sh/master/shellcheck
    write: /home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/is.sh/shellcheck
    shellcheck to PATH: /home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/bin/shellcheck
    fetch: https://raw.githubusercontent.com/qzb/is.sh/master/./tests/tests.sh
    write: /home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/is.sh/./tests/tests.sh
    tests to PATH: /home/runner/work/shell-output-guidelines/shell-output-guidelines/deps/bin/tests

? 0
```
```
$ ./deps/bin/is --help
/home/runner/work/_temp/372adbc8-e545-4ddb-bc6a-ad0c5ffd7e42.sh: line 16: ./deps/bin/is: No such file or directory
? 0
```
