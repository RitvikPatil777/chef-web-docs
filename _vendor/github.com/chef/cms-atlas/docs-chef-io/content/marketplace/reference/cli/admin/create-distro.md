+++
title = "Create a distribution in an organization"
draft = false
weight = 70
+++

## cms-atlas-cli admin create-distro

Create a distribution in an organization

```
cms-atlas-cli admin create-distro [flags]
```

### Options

```
      --base-path string    Base path (required)
  -h, --help                help for create-distro
      --name string         Distribution name (required)
      --org-id string       Organization ID (use saved state if omitted)
      --repository string   Repository ID (use saved state if omitted)
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

