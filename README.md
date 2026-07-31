# static-sites

Placeholder "coming soon" pages for domains being migrated from zone.ee to Hetzner/Coolify. No backend - each folder is a standalone static site (nginx + one HTML file) deployed as its own Coolify application, `base_directory` pointed at the domain's folder.

## Domains

- itwisehub.com
- itwisehub.ee
- proxmox.ee
- servicehub.ee
- bidhub.ee
- procurement.ee

## Adding a real site later

Replace the folder's contents with the real project (or point a new Coolify application at a different repo/branch) and swap the domain's FQDN over - the placeholder Dockerfile is disposable.
