+++
title = "Marketplace release notes"
draft = false
linkTitle = "Marketplace"
summary = "Marketplace release notes"

[menu]
  [menu.release_notes]
    title = "Marketplace"
    identifier = "release_notes/Marketplace"
    parent = "release_notes"
    weight = 130
+++

## Marketplace 1.0.0

Release date: September 2, 2026

Marketplace 1.0.0 provides backward-compatible public cookbook consumption for Chef Supermarket workflows.

### New features requiring configuration updates

- **Marketplace public cookbook source**: You can use Marketplace as the public cookbook source for Berkshelf, Policyfiles, and `knife supermarket` commands.
  Update your source URL to `https://marketplace.chef.io`.
  See [Marketplace compatibility reference](/saas/marketplace_compatibility_reference/) for configuration steps.

### New features

- **Unauthenticated read-only Knife commands**: Marketplace supports unauthenticated, read-only `knife supermarket` commands, including `download`, `install`, `list`, `search`, and `show`.
- **Parallel public-source support**: You can continue to use the public Chef Supermarket source or configure Marketplace as your public cookbook source.

### Limitations

- Marketplace 1.0.0 supports cookbooks from the public Chef Supermarket only.
- Private Chef Supermarket content, write operations, and administrative workflows aren't supported.