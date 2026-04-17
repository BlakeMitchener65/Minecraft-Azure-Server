# Minecraft-Azure-Server



Portfolio Project: Minecraft server deployed on Azure with Infrastructure as Code.



\## Infrastructure

\- Set up resource group `RG-Minecraft`

\- Deployed Ubuntu 24.04 LTS on (`Standard B2ls v2, 2 vCPU, 4 GiB RAM`) — VM named `VM-Minecraft`

\- Configured NSG inbound rules: `SSH (22)` and `Minecraft (25565/TCP)`

\- Generated SSH key pair for secure access



\## Server Setup

\- SSH'd into the VM from my local machine via Git Bash

\- Updated and upgraded Ubuntu packages (`apt update \&\& apt upgrade`)

\- Installed Docker via the official install script

\- Added user to the `docker` group for non-sudo access

