dokku-app-url
=============

Makes app URL available as environment variable


# `git rev-parse HEAD` in dokku env

Lets you fetch the URL the app is served from using the `APP_URL` environment variable.

## Installation

```
cd /var/lib/dokku/plugins
git clone https://github.com/mikecsh/dokku-app-url

```

The environment variable will be set next time you deploy.