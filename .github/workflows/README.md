# Testing locally GitHub Actions Workflows

```shell
# Install 
gh extension install https://github.com/nektos/gh-act

# Run workflows, e.g.pull_request
gh act pull_request -e .github/workflows/pr_event.json -s GITHUB_TOKEN="$(gh auth token)"
```
