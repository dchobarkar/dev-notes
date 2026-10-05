# Recover lost commits with reflog

`git reflog` lists where HEAD has been, even after a hard reset. Find the sha you lost and `git switch -c rescue <sha>` to get it back.
