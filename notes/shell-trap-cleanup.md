# Clean up temp files with trap

`trap 'rm -rf "$tmp"' EXIT` runs the cleanup on any exit path, including errors and Ctrl+C, so temp dirs never leak.
