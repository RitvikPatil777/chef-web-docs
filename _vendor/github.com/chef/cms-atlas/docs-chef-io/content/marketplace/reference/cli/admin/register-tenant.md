+++
title = "Register a new tenant"
draft = false
weight = 300
+++

## cms-atlas-cli admin register-tenant

Register a new tenant

```
cms-atlas-cli admin register-tenant [flags]
```

### Options

```
      --admin-email string      Tenant admin email
      --admin-password string   Tenant admin password (required)
      --admin-username string   Tenant admin username (required)
      --content-types strings   Content types (cookbook,inspec,habitat) (default [cookbook])
  -h, --help                    help for register-tenant
      --name string             Tenant name (required)
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

