---
date: 2018-03-07T09:51:50Z
title: "jx create git user"
slug: jx_create_git_user
url: /commands/jx_create_git_user/
---
## jx create git user

Adds a new user to the git server

### Synopsis

Creates a new user for a Git Server. Only supported for Gitea so far

```
jx create git user [username] [flags]
```

### Examples

```
  # Creates a new user in the local gitea server
  jx create git user -n local someUserName -p somepassword -e foo@bar.com
```

### Options

```
  -a, --admin              Whether the user is an admin user
  -t, --api-token string   The API Token for the user
  -b, --batch-mode         In batch mode the command never prompts for user input
  -e, --email string       The User email address
      --headless           Enable headless operation if using browser automation
  -h, --help               help for user
  -n, --name string        The name of the git server to add a user
  -p, --password string    The User password to try automatically create a new API Token
  -u, --url string         The URL of the git server to add a user
      --verbose            Enable verbose logging
```

### SEE ALSO

* [jx create git](/commands/jx_create_git/)	 - Creates a git resource

###### Auto generated by spf13/cobra on 7-Mar-2018