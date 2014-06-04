# `git rev-parse --short HEAD` in dokku env

Lets you fetch the git revision hash used to build the app from the `COMMIT_HASH`
environment variable.

## Installation

```
cd /var/lib/dokku/plugins
git clone https://github.com/aidansteele/dokku-git-rev
```

The environment variable will be set next time you deploy.
