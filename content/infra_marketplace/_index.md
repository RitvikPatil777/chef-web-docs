+++
title = "Infra Marketplace overview"
draft = false

[menu]
  [menu.infra_marketplace]
    title = "Overview"
    identifier = "infra_marketplace/overview"
    parent = "infra_marketplace"
    weight = 10
+++

Infra Marketplace provides backward-compatible public cookbook consumption for Chef Supermarket workflows.
This page describes the confirmed initial-release scope.

## Intended audience

This page is for DevOps engineers and platform teams that currently consume cookbooks from the public Chef Supermarket.

## Initial-release scope

The initial release is limited to backward compatibility for cookbook-consumption workflows that currently use the public Chef Supermarket.

The confirmed scope includes:

- Backward compatibility for unauthenticated, read-only `knife supermarket` commands, including `download`, `install`, `list`, `search`, and `show`.
- Backward compatibility for Berkshelf cookbook consumption workflows.
- Backward compatibility for Policyfile cookbook consumption workflows.
- Compatibility only for cookbooks from the public Chef Supermarket.
- Parallel support for public Chef Supermarket and Infra Marketplace cookbook sources.

## Out-of-scope for initial release

The following items are outside the initial-release scope:

- Private Chef Supermarket content.
- `knife supermarket` write or administrative workflows.
- Publishing, sharing, unsharing, deprecating, deleting, and administrative content operations.
- Migration workflows for private Chef Supermarket.
- New content types beyond cookbooks from the public Chef Supermarket.

## Limitations

Compatibility applies only to cookbooks from the public Chef Supermarket.
Private Chef Supermarket content is not supported in this initial release.
Unauthenticated, read-only `knife supermarket` commands are in scope.
Write and administrative commands are outside the initial-release scope.

## Related information

- [Infra Marketplace compatibility reference](/infra_marketplace/compatibility_reference/)
- [knife supermarket](/workstation/latest/tools/knife/knife_supermarket/)
- [Berkshelf](/workstation/latest/tools/berkshelf/)
- [About Policyfiles](/client/latest/policy/policyfile/)