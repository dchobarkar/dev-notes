# Safe filenames with find and xargs

`find . -name '*.log' -print0 | xargs -0 rm` handles spaces and newlines in filenames. Without `-print0` and `-0` odd names break the pipeline.
