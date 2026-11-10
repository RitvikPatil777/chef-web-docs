+++
title = "Query audit logs"
draft = false
weight = 20
+++

## cms-atlas-cli admin audit-logs

Query audit logs

```
cms-atlas-cli admin audit-logs [flags]
```

### Options

```
      --action string          Filter by action
      --actor-type string      Filter by actor type
  -h, --help                   help for audit-logs
      --limit int              Maximum number of logs to return (default 50)
      --resource-type string   Filter by resource type
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

