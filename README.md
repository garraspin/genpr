# genpr

This command groups all the boilerplate commands needed to create a pull request (PR) in github from uncommitted changes in your current branch using Jira ticket summary (title) as the commit message.

Usage:
```bash
genpr <jira-ticket-number>
```

Initial set up is needed. 
- Add genpr to your path:
```bash
export PATH=$PATH:<path-to-genpr>/genpr
```
- Set env vars:
```bash
export JIRA_TOKEN=<token> # generate token in https://id.atlassian.com/manage-profile/security/api-tokens
export JIRA_USER=<your-jira-user>
export JIRA_BASE=<jira-base-url>
export GITHUB_BASE=<github-base-url>
```


