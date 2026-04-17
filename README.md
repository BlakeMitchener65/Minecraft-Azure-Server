# Minecraft-Azure-Server



Portfolio Project: Minecraft server deployed on Azure with Infrastructure as Code



\## **Infrastructure**

\--Set up resource group  `RG\_Minecraft`

\--Deployed Linux (ubuntu 24.04) On  `Standard B2ls v2` (2 vcpus, 4 GiB memory) Virtual Machine  (`VM\_Minecraft`)

\--Configured NSG inbound rules: SSH (22) and Minecrafts(25565/TCP)

\--Generated SSH key pair for secure access



\## **Sever Setup**

\-- SSH'd into the VM from my local machine via Git Bash

\-- Updated and Upgraded Ubuntu (`apt update \&\& apt upgrade`)

\-- Installed Docker via the official install script

\--Added userIDs to docker for non-sudo access 

