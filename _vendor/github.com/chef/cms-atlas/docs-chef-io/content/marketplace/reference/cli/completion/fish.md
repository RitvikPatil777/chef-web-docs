+++
title = "Generate the autocompletion script for fish"
draft = false
weight = 20
+++

## cms-atlas-cli completion fish

Generate the autocompletion script for fish

### Synopsis

Generate the autocompletion script for the fish shell.

To load completions in your current shell session:

	cms-atlas-cli completion fish | source

To load completions for every new session, execute once:

	cms-atlas-cli completion fish > ~/.config/fish/completions/cms-atlas-cli.fish

You will need to start a new shell for this setup to take effect.


```
cms-atlas-cli completion fish [flags]
```

### Options

```
  -h, --help              help for fish
      --no-descriptions   disable completion descriptions
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

* [cms-atlas-cli completion](_index.md)	 - Generate the autocompletion script for the specified shell

