# Make curl scripts fail properly

`curl -fsSL URL` fails on HTTP errors (`-f`), hides progress (`-s`), still shows errors (`-S`), and follows redirects (`-L`). Good default for scripts.
