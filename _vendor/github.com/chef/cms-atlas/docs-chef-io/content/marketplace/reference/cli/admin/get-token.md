+++
title = "Get an API token for a tenant"
draft = false
weight = 180
+++

## cms-atlas-cli admin get-token

Get an API token for a tenant

```
cms-atlas-cli admin get-token [flags]
```

### Options

```
  -h, --help               help for get-token
      --password string    Tenant admin password (required)
      --role string        Token role (admin, writer, reader) (default "admin")
      --tenant-id string   Tenant ID (use saved state if omitted)
      --username string    Tenant admin username (required)
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

