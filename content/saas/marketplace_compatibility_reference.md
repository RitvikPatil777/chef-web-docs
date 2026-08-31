+++
title = "Marketplace compatibility reference"
draft = false
[menu]
  [menu.cloud]
    title = "Marketplace compatibility"
    identifier = "chef_cloud/saas/Marketplace compatibility reference"
    parent = "chef_cloud/saas"
    weight = 40
+++

This reference documents the initial-release backward compatibility scope for cookbook consumption.
It applies only to cookbooks from the public Chef Supermarket.
It does not apply to private Chef Supermarket content.

## Verified baseline behavior in existing docs

The current `knife supermarket` documentation identifies these arguments as not requiring a user account: `download`, `search`, `install`, and `list`.
The same documentation defines `-m`, `--supermarket-site` as the option for setting the Supermarket URL, with a default of `https://supermarket.chef.io`.

## `knife supermarket` command comparison

The following table covers each verified read-only command listed in existing docs as not requiring a user account.

| Existing public Chef Supermarket command | Marketplace equivalent | Purpose | Notes or differences |
|---|---|---|---|
| `knife supermarket download COOKBOOK_NAME [COOKBOOK_VERSION] (options)` | [AUTHOR NOTE: Exact Marketplace command syntax requires engineering validation.] | Download a cookbook archive. | Existing docs verify `-m`, `--supermarket-site` and default `https://supermarket.chef.io`. Marketplace endpoint value and exact option placement are not yet confirmed in this repository. |
| `knife supermarket install COOKBOOK_NAME [COOKBOOK_VERSION] (options)` | [AUTHOR NOTE: Exact Marketplace command syntax requires engineering validation.] | Install a cookbook from Supermarket into a local git workflow. | Existing docs verify `-m`, `--supermarket-site` and default `https://supermarket.chef.io`. Marketplace endpoint value and exact option placement are not yet confirmed in this repository. |
| `knife supermarket list (options)` | [AUTHOR NOTE: Exact Marketplace command syntax requires engineering validation.] | List available cookbooks. | Existing docs verify `-m`, `--supermarket-site` and default `https://supermarket.chef.io`. Marketplace endpoint value and exact option placement are not yet confirmed in this repository. |
| `knife supermarket search SEARCH_QUERY (options)` | [AUTHOR NOTE: Exact Marketplace command syntax requires engineering validation.] | Search available cookbooks. | Existing docs verify `-m`, `--supermarket-site` and default `https://supermarket.chef.io`. Marketplace endpoint value and exact option placement are not yet confirmed in this repository. |

[AUTHOR NOTE: Validate whether any additional read-only `knife supermarket` commands are in initial-release scope. Existing docs also include `show`, but this repository does not confirm initial-release Marketplace support for it.]

## Berkshelf compatibility comparison

Current Berkshelf documentation verifies the default source pattern:

```ruby
source "https://supermarket.chef.io"
metadata
```

Current Berkshelf documentation also verifies support for custom source URLs by adding additional `source` entries.

| Existing public Chef Supermarket behavior | Marketplace equivalent | Verified configuration change | Verified limitation |
|---|---|---|---|
| Berkshelf resolves cookbooks from `source "https://supermarket.chef.io"`. | [AUTHOR NOTE: Marketplace Berkshelf source URL requires engineering validation.] | [AUTHOR NOTE: Confirm whether the only change is replacing the source URL with the Marketplace endpoint.] | Initial-release scope is limited to cookbooks from the public Chef Supermarket. Private Chef Supermarket content is out of scope. |

## Policyfile compatibility comparison

Current Policyfile documentation verifies that `default_source :supermarket` pulls from the public Chef Supermarket by default.
It also verifies a custom URL form:

```ruby
default_source :supermarket, "https://supermarket-name.example"
```

| Existing public Chef Supermarket behavior | Marketplace equivalent | Verified configuration change | Verified limitation |
|---|---|---|---|
| `default_source :supermarket` uses the public Chef Supermarket by default. | [AUTHOR NOTE: Marketplace Policyfile source endpoint and exact syntax require engineering validation.] | [AUTHOR NOTE: Confirm whether `default_source :supermarket, "<marketplace-endpoint>"` is the supported Marketplace pattern.] | Initial-release scope is limited to cookbooks from the public Chef Supermarket. Private Chef Supermarket content is out of scope. |

## Initial-release limitations

- Compatibility applies only to cookbooks from the public Chef Supermarket.
- Private Chef Supermarket content is not supported.
- Only verified supported read-only `knife supermarket` commands are supported.
- Write and administrative commands are outside the initial-release scope.

## Author validation required

- Confirm the exact Marketplace endpoint.
- Confirm whether the URL scheme is required.
- Confirm exact `knife supermarket` Marketplace syntax, including flag placement and required options.
- Confirm whether `show` is supported in the initial release.
- Confirm any Marketplace-specific authentication or configuration requirements for CLI, Berkshelf, and Policyfile.
