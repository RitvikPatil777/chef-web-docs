+++
title = "Generate the autocompletion script for bash"
draft = false
weight = 10
+++

## cms-atlas-cli completion bash

Generate the autocompletion script for bash

### Synopsis

Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(cms-atlas-cli completion bash)

To load completions for every new session, execute once:

#### Linux:

	cms-atlas-cli completion bash > /etc/bash_completion.d/cms-atlas-cli

#### macOS:

	cms-atlas-cli completion bash > $(brew --prefix)/etc/bash_completion.d/cms-atlas-cli

You will need to start a new shell for this setup to take effect.


```
cms-atlas-cli completion bash
```

### Options

```
  -h, --help              help for bash
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

