+++
title = "Deregister (disable) a tenant without deleting data"
draft = false
weight = 140
+++

## cms-atlas-cli admin deregister-tenant

Deregister (disable) a tenant without deleting data

```
cms-atlas-cli admin deregister-tenant [flags]
```

### Options

```
  -h, --help          help for deregister-tenant
      --name string   Tenant name (use saved state if omitted)
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

