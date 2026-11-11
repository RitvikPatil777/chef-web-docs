+++
title = "Update a remote source"
draft = false
weight = 380
+++

## cms-atlas-cli admin update-remote

Update a remote source

```
cms-atlas-cli admin update-remote [flags]
```

### Options

```
  -h, --help               help for update-remote
      --remote-id string   Remote ID (use saved state if omitted)
      --tenant-id string   Tenant ID (use saved state if omitted)
      --url string         New remote URL (required)
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
      --token string           API token for authentication (alias)
      --user-id string         User ID for authentication
      --verbose                Verbose output
```

### SEE ALSO

* [cms-atlas-cli admin](_index.md)	 - Administrative operations (tenant, org, repo, distro, remote, settings)

