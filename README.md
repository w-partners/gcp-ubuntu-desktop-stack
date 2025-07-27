# GCP Ubuntu Desktop Stack

Infrastructure automation project for setting up a comprehensive development environment on Google Cloud Platform.

## Overview

This project automates the deployment of a 6-layer stack architecture on GCP Ubuntu VMs:

1. **System Layer**: Development tools (Node.js, Ruby, Git)
2. **Container Layer**: Docker and Docker Compose
3. **Data Layer**: PostgreSQL database
4. **Backend Layer**: Express.js and Ruby on Rails
5. **Automation Layer**: n8n workflow automation
6. **Network Layer**: Chrome Remote Desktop for GUI access

## Project Structure

```
gcp-ubuntu-desktop-stack/
├── workflow/               # Task execution snapshots
├── scripts/               # Installation scripts
├── CLAUDE.md             # AI assistant instructions
├── EXECUTION_PLAN.md     # Detailed task breakdown
├── PROJECT_OVERVIEW.md   # Architecture and specifications
└── README.md             # This file
```

## Installation Progress

- [x] Task 1: System base environment
- [x] Task 2: XFCE4 GUI and Chrome Remote Desktop
- [ ] Task 3: Docker and Docker Compose
- [ ] Task 4: PostgreSQL installation
- [ ] Task 5: Backend services deployment
- [ ] Task 6: n8n workflow automation
- [ ] Task 7: SSL/TLS configuration
- [ ] Task 8: Monitoring setup
- [ ] Task 9: Backup configuration
- [ ] Task 10: Performance optimization

## VM Specifications

- **Instance**: e2-standard-4
- **vCPUs**: 4
- **Memory**: 16GB
- **Storage**: 30GB balanced persistent disk
- **OS**: Ubuntu 24.04 LTS
- **Region**: us-central1-c

## Quick Start

1. Create a GCP VM with the specifications above
2. Run the installation scripts in order:
   ```bash
   ./install_base.sh
   ./install_gui.sh
   ./install_additional.sh
   ```
3. Set up Chrome Remote Desktop for GUI access
4. Continue with remaining tasks

## Documentation

- [Project Overview](PROJECT_OVERVIEW.md) - Detailed architecture and requirements
- [Execution Plan](EXECUTION_PLAN.md) - Step-by-step task breakdown
- [Claude Instructions](CLAUDE.md) - AI assistant guidance