# Linux Server Administration Lab

## Project Overview

This project demonstrates practical Linux server administration using Rocky Linux in a VMware Workstation virtual machine.

The project covers user and group management, file permissions, ACL, Apache web server, SSH, firewall configuration, system monitoring, log analysis, backup, and restore verification.

## Environment

- Operating System: Rocky Linux
- Virtualization: VMware Workstation
- Web Server: Apache HTTP Server
- Firewall: firewalld
- Version Control: Git
- Repository: GitHub

## Tasks Performed

### User and Group Management
- Created Linux users
- Created developers and operations groups
- Configured group membership
- Verified users and groups using id and getent

### File Permissions and Security
- Created application directories
- Configured ownership using chown
- Configured permissions using chmod
- Tested user access
- Configured and tested ACL using setfacl and getfacl

### Web Server
- Installed Apache HTTP Server
- Started and enabled the service
- Created a custom HTML page
- Verified the web server using curl

### SSH
- Enabled SSH service
- Verified SSH connectivity locally

### Firewall
- Configured HTTP access
- Configured SSH access
- Verified firewall services using firewall-cmd

### Monitoring and Troubleshooting
- Checked CPU usage
- Checked memory usage
- Checked disk usage
- Reviewed Apache and system logs

### Backup and Restore
- Created a compressed project backup using tar
- Listed backup contents
- Extracted the backup into a test directory
- Verified restored project files

## Project Evidence

The screenshots directory contains screenshots showing practical configuration and verification performed on the Rocky Linux server.

## Project Structure

linux-server-project/
├── README.md
├── commands.txt
├── users-groups.txt
├── permissions.txt
├── acl.txt
├── server-verification.txt
├── logs-verification.txt
├── final-verification-report.txt
└── screenshots/

## Key Linux Commands Used

useradd
usermod
groupadd
id
getent
chown
chmod
setfacl
getfacl
dnf
systemctl
firewall-cmd
journalctl
top
free
df
tar
git

## Verification

The project includes verification reports containing the output of important Linux administration commands.

This project was completed as a practical Rocky Linux lab environment and can be reproduced in a virtual machine.
