+++
title = "Update admin service settings"
draft = false
weight = 400
+++

## cms-atlas-cli admin update-settings

Update admin service settings

```
cms-atlas-cli admin update-settings [flags]
```

### Options

```
  -h, --help                          help for update-settings
      --license-verification string   Enable/disable license verification (true/false)
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

* [cms-atlas-cli admin](_index.md)	 - Administrative operations (tenant, org, repo, distro, remote, settings)

