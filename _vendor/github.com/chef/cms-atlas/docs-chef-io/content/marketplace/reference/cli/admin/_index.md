+++
title = "Administrative operations (tenant, org, repo, distro, remote, settings)"
draft = false
weight = 10
+++

## cms-atlas-cli admin

Administrative operations (tenant, org, repo, distro, remote, settings)

### Synopsis

Administrative management for CMS Atlas: tenants, organizations, repositories, distributions, remotes, settings, and more.

### Options

```
  -h, --help   help for admin
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

* [cms-atlas-cli](../_index.md)	 - Command line client for CMS Atlas
* [cms-atlas-cli admin add-remote](add-remote.md)	 - Add a remote source for content synchronization
* [cms-atlas-cli admin audit-logs](audit-logs.md)	 - Query audit logs
* [cms-atlas-cli admin bulk-folder](bulk-folder.md)	 - Get the bulk import folder path
* [cms-atlas-cli admin bulk-import](bulk-import.md)	 - Start bulk upload processing
* [cms-atlas-cli admin clear-state](clear-state.md)	 - Clear all saved state
* [cms-atlas-cli admin content-types](content-types.md)	 - List supported content types
* [cms-atlas-cli admin create-distro](create-distro.md)	 - Create a distribution in an organization
* [cms-atlas-cli admin create-org](create-org.md)	 - Create a new organization
* [cms-atlas-cli admin create-repo](create-repo.md)	 - Create a repository in an organization
* [cms-atlas-cli admin delete-distro](delete-distro.md)	 - Delete a distribution
* [cms-atlas-cli admin delete-org](delete-org.md)	 - Delete an organization
* [cms-atlas-cli admin delete-repo](delete-repo.md)	 - Delete a repository
* [cms-atlas-cli admin delete-tenant](delete-tenant.md)	 - Delete (deregister) a tenant
* [cms-atlas-cli admin deregister-tenant](deregister-tenant.md)	 - Deregister (disable) a tenant without deleting data
* [cms-atlas-cli admin get-distro](get-distro.md)	 - Get distribution details
* [cms-atlas-cli admin get-org](get-org.md)	 - Get organization details
* [cms-atlas-cli admin get-repo](get-repo.md)	 - Get repository details
* [cms-atlas-cli admin get-token](get-token.md)	 - Get an API token for a tenant
* [cms-atlas-cli admin health](health.md)	 - Check admin service health
* [cms-atlas-cli admin internal-url](internal-url.md)	 - Get the internal Pulp service URL
* [cms-atlas-cli admin list-distros](list-distros.md)	 - List distributions in an organization
* [cms-atlas-cli admin list-orgs](list-orgs.md)	 - List organizations
* [cms-atlas-cli admin list-publishers](list-publishers.md)	 - List registered publishers
* [cms-atlas-cli admin list-repos](list-repos.md)	 - List repositories in an organization
* [cms-atlas-cli admin login](login.md)	 - Login to admin service and get a session token
* [cms-atlas-cli admin logout](logout.md)	 - Logout and invalidate the current session token
* [cms-atlas-cli admin publish-repo](publish-repo.md)	 - Publish a repository version
* [cms-atlas-cli admin read-settings](read-settings.md)	 - Read current admin service settings
* [cms-atlas-cli admin register-publisher](register-publisher.md)	 - Register a new publisher for the public marketplace
* [cms-atlas-cli admin register-tenant](register-tenant.md)	 - Register a new tenant
* [cms-atlas-cli admin remove-remote](remove-remote.md)	 - Remove a remote source
* [cms-atlas-cli admin roles](roles.md)	 - List available roles
* [cms-atlas-cli admin rotate-credentials](rotate-credentials.md)	 - Rotate admin credentials
* [cms-atlas-cli admin set-credentials](set-credentials.md)	 - Set admin credentials for the Pulp backend
* [cms-atlas-cli admin state](state.md)	 - Show saved state (auto-captured IDs from previous commands)
* [cms-atlas-cli admin sync-remote](sync-remote.md)	 - Synchronize content from a remote source
* [cms-atlas-cli admin update-org](update-org.md)	 - Update an organization
* [cms-atlas-cli admin update-remote](update-remote.md)	 - Update a remote source
* [cms-atlas-cli admin update-repo](update-repo.md)	 - Update a repository
* [cms-atlas-cli admin update-settings](update-settings.md)	 - Update admin service settings

