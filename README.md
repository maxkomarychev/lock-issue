# Lock issue

Lock issue

This action is a wrapper for one of [octokit's](https://octokit.github.io/rest.js) methods.

Original docs can be found here: https://octokit.github.io/rest.js/#octokit-routes-issues-lock

# Quick start

```yaml
- uses: maxkomarychev/lock-issue@v0.5.1
  with:
    token: ${{ secrets.GITHUB_TOKEN }}
    issue_number: 100
    lock_reason: off-topic
```


# Inputs

| Name | Is required | Description |
|---|---|---|
|token|true|A token to perform API calls
|issue_number|true|Issue number to lock
|lock_reason|true|"The reason for locking the issue or pull request conversation. Available reasons: off-topic, too heated, resolved, spam"



