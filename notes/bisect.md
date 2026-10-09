# Finding a regression with bisect

`git bisect start BAD GOOD`, then mark each checkout with `git bisect good` / `bad`. `git bisect run ./test.sh` automates it: exit 0 is good, 125 skips the commit, anything else is bad.
