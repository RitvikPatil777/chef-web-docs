+++
title = "Update an organization"
draft = false
weight = 370
+++

## cms-atlas-cli admin update-org

Update an organization

```
cms-atlas-cli admin update-org [flags]
```

### Options

```
      --description string   New description
  -h, --help                 help for update-org
      --name string          New name
      --org-id string        Organization ID (use saved state if omitted)
      --visibility string    New visibility
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

