# Fix an earlier commit with fixup and autosquash

`git commit --fixup <sha>` records a fix for an old commit. Later `git rebase -i --autosquash <base>` moves and squashes it into place automatically.
