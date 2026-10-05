# Compare command output with process substitution

`diff <(sort a.txt) <(sort b.txt)` treats each command's output as a file. No temp files needed.
