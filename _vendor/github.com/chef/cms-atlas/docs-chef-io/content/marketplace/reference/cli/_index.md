+++
title = "Command line client for CMS Atlas"
draft = false
weight = 0
+++

## cms-atlas-cli

Command line client for CMS Atlas

### Synopsis

cms-atlas-cli provides core content operations and administrative management for CMS Atlas.

### Options

```
      --api-token string       API token for authentication
  -b, --base-url string        Base URL to CMS service
      --config string          Path to config file
      --debug                  Enable debug mode (logs requests/responses)
      --format string          Output format: json, yaml, or table (default: table)
  -h, --help                   help for cms-atlas-cli
      --insecure               Skip SSL certificate verification (alias)
      --insecure-skip-verify   Skip SSL certificate verification
      --tenant-id string       Tenant ID for admin operations
      --token string           API token for authentication (alias)
      --user-id string         User ID for authentication
      --verbose                Verbose output
      --version                Show version
```

### SEE ALSO

* [cms-atlas-cli admin](admin/_index.md)	 - Administrative operations (tenant, org, repo, distro, remote, settings)
* [cms-atlas-cli berks](berks/_index.md)	 - Berkshelf compatibility commands
* [cms-atlas-cli completion](completion/_index.md)	 - Generate the autocompletion script for the specified shell
* [cms-atlas-cli core](core/_index.md)	 - Core content API operations
* [cms-atlas-cli inspec](inspec/_index.md)	 - InSpec compatibility commands (stubs)
* [cms-atlas-cli knife](knife/_index.md)	 - Knife compatibility commands

