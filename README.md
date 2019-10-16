# Lock issue

Lock issue

This action is a wrapper for one of [octokit's](https://octokit.github.io/rest.js) methods.

Original docs can be found here: https://octokit.github.io/rest.js/#octokit-routes-issues-lock

# Usage

```yaml
- uses: maxkomarychev/lock-issue@vv0.2.1
  with:
    token: ${{ secrets.GITHUB_TOKEN }}
    issue_number: 100
    lock_reason: off-topic
```
