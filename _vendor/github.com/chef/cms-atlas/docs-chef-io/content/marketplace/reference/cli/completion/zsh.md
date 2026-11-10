+++
title = "Generate the autocompletion script for zsh"
draft = false
weight = 40
+++

## cms-atlas-cli completion zsh

Generate the autocompletion script for zsh

### Synopsis

Generate the autocompletion script for the zsh shell.

If shell completion is not already enabled in your environment you will need
to enable it.  You can execute the following once:

	echo "autoload -U compinit; compinit" >> ~/.zshrc

To load completions in your current shell session:

	source <(cms-atlas-cli completion zsh)

To load completions for every new session, execute once:

#### Linux:

	cms-atlas-cli completion zsh > "${fpath[1]}/_cms-atlas-cli"

#### macOS:

	cms-atlas-cli completion zsh > $(brew --prefix)/share/zsh/site-functions/_cms-atlas-cli

You will need to start a new shell for this setup to take effect.


```
cms-atlas-cli completion zsh [flags]
```

### Options

```
  -h, --help              help for zsh
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

