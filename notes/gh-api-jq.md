# Query the GitHub API with gh and jq

`gh api repos/OWNER/REPO/issues --jq '.[].title'` calls the REST API with your login and filters with built-in jq.
