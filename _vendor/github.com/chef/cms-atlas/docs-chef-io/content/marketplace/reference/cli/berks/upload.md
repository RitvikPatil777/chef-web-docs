+++
title = "Upload a cookbook to the server"
draft = false
weight = 30
+++

## cms-atlas-cli berks upload

Upload a cookbook to the server

```
cms-atlas-cli berks upload <cookbook> [flags]
```

### Options

```
  -B, --berksfile string       Path to Berksfile (default "Berksfile")
      --cookbook-path string   Path to cookbook tarball
  -h, --help                   help for upload
      --ssl-verify             Enable SSL verification (default true)
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

* [cms-atlas-cli berks](_index.md)	 - Berkshelf compatibility commands

