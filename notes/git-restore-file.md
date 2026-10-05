# Discard changes to one file with git restore

`git restore path/to/file` throws away unstaged edits to that file. Use `git restore --staged path` to unstage without losing the edit. Newer and clearer than `git checkout -- path`.
