# Linux for DevOps

## Introduction
Linux is the most commonly used operating system in DevOps, cloud computing, and production environments. It powers servers, container systems, automation tools, and CI/CD pipelines. Understanding Linux fundamentals is essential for every DevOps engineer.

---

## Why Linux is Important in DevOps
- Most cloud servers run on Linux (AWS, Azure, GCP)
- Used heavily for automation, scripting, and deployment
- Required for Docker, Kubernetes, Ansible, Jenkins, Git, Terraform
- Provides strong security and access control
- Open-source and customizable platform

---

## Linux Architecture
| Layer | Description |
|-------|------------|
| Hardware | Physical computing resources |
| Kernel | Controls communication between hardware and software |
| Shell | Command-line interface to interact with the system |
| Applications | User-level programs and tools |

---

## Linux File System Structure
| Directory | Description |
|-----------|-------------|
| / | Root directory |
| /home | User directories and personal data |
| /bin | Essential system commands |
| /sbin | Administrative commands |
| /etc | Configuration files |
| /var | Variable files such as logs |
| /tmp | Temporary files |
| /usr | Application binaries and libraries |
| /boot | System boot files |
| /root | Root user home directory |

---

## Users and Permissions
Linux supports multiple users with different access levels. Permissions define what each user can do with files.

| Permission | Description |
|------------|-------------|
| r | Read |
| w | Write |
| x | Execute |

Permission groups:
- User
- Group
- Others

---

## Processes
A process is a running instance of a program.

Types of processes:
- Foreground processes
- Background processes
- Daemon services

Process attributes:
- Process ID (PID)
- Parent Process ID (PPID)
- State (running, sleeping, stopped, zombie)

---

## Package Management
Used to install, update, and remove software.

| Distribution | Package Manager |
|--------------|-----------------|
| Ubuntu / Debian | APT |
| CentOS / RHEL / Amazon Linux | YUM / DNF |

---

## Networking Basics in Linux
| Term | Description |
|------|-------------|
| IP Address | Unique address to identify a device |
| Hostname | Name assigned to the machine |
| DNS | Converts domain name to IP address |
| Gateway | Routes traffic between networks |
| Ports | Identify network-based services |

Common ports:
- 22 – SSH
- 80 – HTTP
- 443 – HTTPS

---

## Shell Scripting
Shell scripting is used to automate tasks in Linux.

Common use cases:
- Automated deployments
- Log monitoring
- Backup scheduling
- Server configuration

---

## SSH (Secure Shell)
SSH allows secure remote login and file transfer between servers. It is widely used for managing cloud infrastructure.

---

## Storage and Disk Concepts
| Term | Description |
|------|-------------|
| Partition | Logical division of disk space |
| Filesystem | Format for storing and accessing files |
| Mounting | Attaching a filesystem to directory structure |

---

## Logs and Monitoring
Logs help identify problems and performance issues.

Examples:
- System logs
- Security logs
- Application logs

Tools for monitoring:
- Prometheus
- Grafana
- ELK Stack

---

## Conclusion
Linux is the foundation of DevOps. Strong knowledge of Linux is necessary for managing servers, automating workflows, and working with containers, CI/CD, and cloud infrastructure.

---
