+++
title = "Start bulk upload processing"
draft = false
weight = 40
+++

## cms-atlas-cli admin bulk-import

Start bulk upload processing

```
cms-atlas-cli admin bulk-import [flags]
```

### Options

```
      --content-type string   Content type (default "cookbook")
      --folder string         Folder path (required)
  -h, --help                  help for bulk-import
      --tenant-id string      Tenant ID (use saved state if omitted)
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

