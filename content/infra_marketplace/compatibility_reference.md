+++
title = "Infra Marketplace compatibility reference"
draft = false

[menu]
  [menu.infra_marketplace]
    title = "Compatibility reference"
    identifier = "infra_marketplace/compatibility_reference"
    parent = "infra_marketplace"
    weight = 20
+++

This reference documents the initial-release backward compatibility scope for cookbook consumption.
It applies only to cookbooks from the public Chef Supermarket.
It does not apply to private Chef Supermarket content.
Infra Marketplace is available at `https://marketplace.chef.io`.
You can continue to use `https://supermarket.chef.io` or configure Infra Marketplace as your public cookbook source.

## `knife supermarket` compatibility

Infra Marketplace supports all unauthenticated, read-only `knife supermarket` commands.
The command syntax is the same as it is for Chef Supermarket.
No Infra Marketplace credentials are required.

Configure Infra Marketplace for all `knife supermarket` commands by adding the following setting to your `knife.rb` file:

```ruby
knife[:supermarket_site] = "https://marketplace.chef.io"
```

You can also use the `--supermarket-site https://marketplace.chef.io` option with an individual command.

| Command | Infra Marketplace example | Purpose |
|---|---|---|
| `knife supermarket download <cookbook-name>` | `knife supermarket download <cookbook-name> --supermarket-site https://marketplace.chef.io` | Download a cookbook archive. |
| `knife supermarket install <cookbook-name>` | `knife supermarket install <cookbook-name> --supermarket-site https://marketplace.chef.io` | Install a cookbook into a local Git workflow. |
| `knife supermarket list` | `knife supermarket list --supermarket-site https://marketplace.chef.io` | List available cookbooks. |
| `knife supermarket search <search-query>` | `knife supermarket search <search-query> --supermarket-site https://marketplace.chef.io` | Search available cookbooks. |
| `knife supermarket show <cookbook-name>` | `knife supermarket show <cookbook-name> --supermarket-site https://marketplace.chef.io` | Show cookbook details. |

The examples use Infra Marketplace for a single command.
After you configure `knife[:supermarket_site]`, use the same commands without the `--supermarket-site` option.

## Berkshelf compatibility

To use Infra Marketplace with Berkshelf, replace the public Chef Supermarket source in your `Berksfile`:

```ruby
source "https://marketplace.chef.io"
metadata
```

Use your existing Berkshelf commands, such as `berks install`.
No Infra Marketplace credentials are required.

| Public cookbook source | Infra Marketplace source | Configuration change | Limitation |
|---|---|---|---|
| `source "https://supermarket.chef.io"` | `source "https://marketplace.chef.io"` | Replace the source URL. | Private Chef Supermarket content is out of scope. |

## Policyfile compatibility

To use Infra Marketplace with a Policyfile, configure Infra Marketplace as the Supermarket source:

```ruby
default_source :supermarket, "https://marketplace.chef.io"
```

Use your existing Policyfile commands after you change the source URL.
No Infra Marketplace credentials are required.

| Public cookbook source | Infra Marketplace source | Configuration change | Limitation |
|---|---|---|---|
| `default_source :supermarket` | `default_source :supermarket, "https://marketplace.chef.io"` | Add the Marketplace URL to `default_source`. | Private Chef Supermarket content is out of scope. |

## Initial-release limitations

- Compatibility applies only to cookbooks from the public Chef Supermarket.
- Private Chef Supermarket content is not supported.
- Infra Marketplace supports unauthenticated, read-only `knife supermarket` commands.
- Write and administrative commands are outside the initial-release scope.