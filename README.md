# LinuxServer Docker Project

This project orchestrates multiple services using [LinuxServer.io](https://www.linuxserver.io/) Docker images for media management and documentation.

## Services

- **MariaDB**: Database for BookStack
- **BookStack**: Wiki/documentation platform
- **Sonarr**: TV show management
- **Radarr**: Movie management
- **qBittorrent**: Torrent client
- **Plex**: Media server
- **Nginx**: Web server (configurable as a reverse proxy)

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <your-github-repo-url>
   cd linuxserver-docker-project
   ```
