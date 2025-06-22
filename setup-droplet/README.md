# Server Setup Script for Nexus and Jenkins with Docker

### Features
- Updates and upgrades the system packages.
- Installs OpenJDK 8, Node.js, Docker, and network utilities.
- Creates a new user with sudo privileges.
- Downloads and configures Nexus Repository Manager to run as a dedicated user.
- Sets up Nexus using Docker with persistent storage.
- Deploys Jenkins in a Docker container with Docker-in-Docker capabilities.

### Install Script
```
chmod +x setup-droplet .sh
./setup-droplet 
```
