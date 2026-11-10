+++
title = "Install cookbooks from the universe endpoint"
draft = false
weight = 10
+++

## cms-atlas-cli berks install

Install cookbooks from the universe endpoint

### Synopsis

Resolves and installs cookbook dependencies via the /api/v1/universe endpoint.

```
cms-atlas-cli berks install [cookbook] [flags]
```

### Options

```
  -B, --berksfile string   Path to Berksfile (default "Berksfile")
  -h, --help               help for install
      --ssl-verify         Enable SSL verification (default true)
```

### Options inherited from parent commands

```
      --api-token string       API token for authentication
  -b, --base-url string        Base URL to CMS service
      --config string          Path to config file
      --debug                  Enable debug mode (logs requests/responses)
      --format string          Output format: json, yaml, or table (default: table)
      --insecure               Skip SSL certificate verification (alias)
      --insecure-skip-verify   Skip SSL certificate verification
      --tenant-id string       Tenant ID for admin operations
      --token string           API token for authentication (alias)
      --user-id string         User ID for authentication
      --verbose                Verbose output
```

### SEE ALSO

* [cms-atlas-cli berks](_index.md)	 - Berkshelf compatibility commands

