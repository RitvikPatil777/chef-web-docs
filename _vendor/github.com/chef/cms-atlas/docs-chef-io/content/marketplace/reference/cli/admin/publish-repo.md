+++
title = "Publish a repository version"
draft = false
weight = 270
+++

## cms-atlas-cli admin publish-repo

Publish a repository version

```
cms-atlas-cli admin publish-repo [flags]
```

### Options

```
  -h, --help               help for publish-repo
      --repo-id string     Repository ID (use saved state if omitted)
      --tenant-id string   Tenant ID (use saved state if omitted)
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

