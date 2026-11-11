+++
title = "Add a remote source for content synchronization"
draft = false
weight = 10
+++

## cms-atlas-cli admin add-remote

Add a remote source for content synchronization

```
cms-atlas-cli admin add-remote [flags]
```

### Options

```
      --content-type string   Content type (cookbook, inspec, habitat) (default "cookbook")
  -h, --help                  help for add-remote
      --name string           Remote name (required)
      --tenant-id string      Tenant ID (use saved state if omitted)
      --url string            Remote URL (required)
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

