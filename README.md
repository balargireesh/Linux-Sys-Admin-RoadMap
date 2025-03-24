# Minimal Linux System Administrator Roadmap

### 1. **Linux Basics**
- Install & Set Up Linux (Ubuntu, Debian, CentOS, Arch)
- Learn Basic Commands (`ls`, `cd`, `cp`, `mv`, `rm`, `cat`, `grep`, `find`)
- File & Directory Permissions (`chmod`, `chown`, `chgrp`)
- User & Group Management (`useradd`, `usermod`, `passwd`, `groupadd`)
- Process Management (`ps`, `top`, `kill`, `nice`, `htop`)

### 2. **Shell & Scripting**
- Master `bash` shell & environment variables
- Learn shell scripting (`if`, `for`, `while`, `case`, `functions`)
- Automate tasks with `cron` (`crontab -e`)

### 3. **Networking Basics**
- Check network settings (`ifconfig`, `ip a`, `ip route`, `netstat`, `ss`)
- Manage connections (`ping`, `curl`, `wget`, `scp`, `rsync`)
- Firewall & Security (`ufw`, `iptables`, `fail2ban`)

### 4. **Package Management**
- Debian-based: `apt`, `dpkg`
- RedHat-based: `yum`, `dnf`, `rpm`
- Arch-based: `pacman`

### 5. **System Monitoring & Logs**
- Check system usage (`free -m`, `df -h`, `du -sh *`)
- Read logs (`journalctl`, `/var/log/syslog`, `/var/log/auth.log`)
- Monitor system with `top`, `htop`, `vmstat`, `iostat`, `sar`

### 6. **Services & Daemons**
- Manage services (`systemctl start/stop/status <service>`)
- Configure & check startup services (`systemctl list-units --type=service`)

### 7. **SSH & Remote Access**
- Secure SSH (`sshd_config`, disable root login, change ports)
- Use `scp` / `rsync` for file transfers
- Automate SSH access with SSH keys

### 8. **Disk & Filesystem Management**
- Partition & format drives (`fdisk`, `mkfs`, `lsblk`)
- Mount & unmount (`mount`, `umount`, `fstab`)
- Check disk health (`fsck`, `smartctl`)

### 9. **Backup & Recovery**
- Use `tar`, `rsync`, and `dd` for backups
- Create & restore snapshots (`Timeshift`, `LVM snapshots`)
- Automate backups (`crontab`, `rsync`)

### 10. **Web Server & Databases (Optional, But Useful)**
- Set up Apache/Nginx (`systemctl enable nginx`, `/etc/nginx/nginx.conf`)
- Install & configure MySQL/PostgreSQL (`mysql_secure_installation`, `psql`)

### 11. **Virtualization & Containers (Optional, But Useful)**
- Learn Docker (`docker run`, `docker ps`, `docker-compose`)
- Work with Virtual Machines (`VirtualBox`, `KVM`, `VMware`)
