---
date: 2018-03-07T09:51:50Z
title: "jx get environments"
slug: jx_get_environments
url: /commands/jx_get_environments/
---
## jx get environments

Display one or many Environments

### Synopsis

Display one or many environments.

```
jx get environments [flags]
```

### Examples

```
  # List all environments
  jx get environments
  
  # List all environments using the shorter alias
  jx get env
```

### Options

```
  -h, --help             help for environments
  -o, --output string    The output format such as 'yaml'
  -p, --promote string   Filters the environments by promotion strategy. Possible values: Auto, Manual, Never
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or many resources

###### Auto generated by spf13/cobra on 7-Mar-2018