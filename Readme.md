
---

## VPS Setup

This is my simple VPS setup guide for future reference.

### Services Running in Docker:

## Stream setup
- **Gluten** (with Mullvad OpenVPN/Wireguard) — All containers are in the same network.
- **qBittorrent**
- **Homarr**
- **Sonarr**
- **Prowlarr**
- **Radarr**
- **Jackett**
- **Bazarr**
- **Jellyseerr**

## Discord music bot
- **Ellen** — A custom bot that plays music and videos and has AI chat 

### Web Servers:
- **Nginx Proxy Manager** — Used to obtain wildcard SSL for my domain.
- **Nginx** — Installed and fix some Webmin errors I ran into.

### Management Tools:
- **Webmin** — For system management (not in Docker).
- **Portainer** — For easy Docker deployment and configuration.
- **FileBrowser** — For easily browse files.

### Game Server Management:
- **Pterodactyl** with Wings — Running in Docker.
- **Petropal** — A custom bot to manage servers, shutting them down to free resources and backing up saves to Google Drive.

### Streaming Setup:
- **Plex**
- **Jellyfin** - and some english fonts so subs work properly

### SSL:
- Standard SSL configuration for all services.
- Specific WebSocket SSL configuration for Wings.

### - **Ports** — To open port only to local host EX: 127.0.0.1:8085:8085

---