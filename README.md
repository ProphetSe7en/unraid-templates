# Unraid Templates

Docker container templates for [Unraid Community Applications](https://forums.unraid.net/topic/38582-plug-in-community-applications/).

## Available Containers

| Container | Description | Repository |
|-----------|-------------|------------|
| [Clonarr](https://github.com/ProphetSe7en/clonarr) | TRaSH Guides sync tool for Radarr/Sonarr — profiles, custom formats, scores, quality sizes | [GHCR](https://github.com/ProphetSe7en/clonarr/pkgs/container/clonarr) |
| [Constat](https://github.com/ProphetSe7en/constat) | Docker container monitor with auto-healing, live stats, and web UI | [GHCR](https://github.com/ProphetSe7en/constat/pkgs/container/constat) |
| [containernetwork-autofix](https://github.com/ProphetSe7en/containernetwork-autofix) | Auto-fix dependent containers when network-parent restarts (fork with bug fixes) | [GHCR](https://github.com/ProphetSe7en/containernetwork-autofix/pkgs/container/containernetwork-autofix) |
| [Dozzle](https://github.com/ProphetSe7en/dozzle) | Real-time Docker log viewer — wrapper with Docker HEALTHCHECK (upstream doesn't work on Unraid) | [GHCR](https://github.com/ProphetSe7en/dozzle/pkgs/container/dozzle) |
| [Cloudflare Tunnel](https://github.com/ProphetSe7en/cloudflare-tunnel) | Cloudflare Tunnel wrapper with Docker HEALTHCHECK | [GHCR](https://github.com/ProphetSe7en/cloudflare-tunnel/pkgs/container/cloudflare-tunnel) |
| [PurgeBot](https://github.com/ProphetSe7en/purgebot) | Automated Discord message cleanup with retention policies, channel sorting, and web UI | [GHCR](https://github.com/ProphetSe7en/purgebot/pkgs/container/purgebot) |
| [vpn-gateway](https://github.com/ProphetSe7en/vpn-gateway) | VPN gateway with nftables bandwidth limiting, per-service monitoring, scheduling, and web UI | [GHCR](https://github.com/ProphetSe7en/vpn-gateway/pkgs/container/vpn-gateway) |

## Installation

These templates are available through the Unraid Community Applications plugin. Search for "ProphetSe7en" or the container name in the Apps tab.

### Manual Installation

To add this repository manually, go to the **Apps** tab in Unraid, click **Settings**, and add this URL under Template Repositories:

```
https://github.com/ProphetSe7en/unraid-templates
```
