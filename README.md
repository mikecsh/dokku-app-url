dokku-app-url
=============

#WARNING
**This plugin is not compatible with the latest version of dokku.** Unfortunately I do not have time to adapt this to the new plugin architecture at the moment.

## Introduction

Lets you fetch the URL the app is served from using the `APP_URL` environment variable.

## Installation

```
cd /var/lib/dokku/plugins
git clone https://github.com/mikecsh/dokku-app-url
dokku plugins-install

```

The environment variable will be set next time you deploy.