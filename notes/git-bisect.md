# Find the commit that broke things

`git bisect start`, then `git bisect bad` and `git bisect good <sha>`. Git checks out midpoints until it names the first bad commit. `git bisect run ./test.sh` automates it.
