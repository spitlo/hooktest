# Test repo for installable githooks

Installs a `post-merge` hook that notifies on a Slack channel if diff is detected on pull.

1. Run `bin/install_hooks`
2. Answer the questions. Only the first one is required.

The next time you run `git pull` and something has changed, your team will get a Slack notification.

## Warning!
The `bin/install_hooks` script will overwrite existing `post-merge` hook.
