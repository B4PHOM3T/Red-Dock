![1689688010984](https://github.com/B4PHOM3T/Red-Dock/assets/89618500/6b7fe5bd-e07c-4305-a68d-6290b0f20bf4)


# Red Dock
Red Dock is a Linux tool designed for managing Docker, facilitating the installation and utilization of Docker specifically tailored for penetration testing purposes.
---
## Why opt for this tool?
- The primary goal of Red Dock is to furnish penetration testers with a pre-configured Kali Linux environment containing a comprehensive set of popular tools and frameworks.
- The tool includes a Python script designed to streamline the management of Docker containers, eliminating the need for cumbersome Docker commands.
- Kali is the default image due to its Custom Package Repositories, simplifying the installation of additional tools not initially included.
- It resolves the perennial dilemma faced by novice hackers on whether to use a virtual machine (VM) or dual boot by advocating for Docker—faster than a VM and equally secure.
---
## Prerequisites
- Docker must be installed on your system.
- If Docker is not installed, refer to the official Docker installation guide: [Get Docker](https://docs.docker.com/get-docker/).
---
## Installation Instructions for Ubuntu/Debian
Execute the `install.sh` script to initiate the automated installation process.
```bash
./install.sh
```
---
## Usage

### Launch the container

```bash
rd start
```
This command initiates the Kali Linux Docker container, attaching a volume for persistence and mounting it as `/vol`.

### Stop all container instances

```bash
rd stop
```
Cease and remove all actively running containers.

### Check Container Status

```bash
rd status
```
View the status of Docker containers.

### Update Kali Linux Image

```bash
rd update
```
Update the Kali Linux Docker image by committing changes from the container.

### Transfer Files to/from Container

```bash
rd cp <path-to-file> <path-to-copy>
```
Transfer files between the volume and the host machine.

---
### Installed Tools
- [x] nmap
- [x] hydra
- [x] metasploit-framework
- [x] sqlmap
- [x] smbclient
- [x] enum4linux
- [x] smbmap
- [x] sublist3r
- [x] dirb
- [x] nikto
- [x] dnsenum
- [x] fierce
- [x] exploitdb
- [x] theharvester
- [x] wafw00f
- [x] hashcat
- [x] john
- [x] crackmapexec
- [x] evil-winrm
- [x] powershell-empire
- [x] whatweb
- [x] beef-xss
- [x] netcat-traditional
- [x] traceroute
- [x] steghide
- [x] set
- [x] wpscan
- [x] linux-exploit-suggester

