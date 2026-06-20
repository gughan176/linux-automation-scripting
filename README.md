# Linux Automation Scripting

A collection of Bash scripts designed to automate common Linux system administration and DevOps tasks.

## Project Overview

This project demonstrates Linux automation using Bash scripting to reduce manual effort, improve system reliability, and simplify routine administrative tasks.

## Features

### 1. Automated Backup Script
- Creates compressed backups of files and directories.
- Generates timestamped backup archives.
- Removes old backups automatically.
- Supports scheduled execution using Cron.

### 2. Server Health Check Script
- Monitors CPU utilization.
- Checks memory usage.
- Reports disk space usage.
- Displays system uptime.
- Lists failed services.

### 3. Disk Usage Monitoring
- Monitors disk consumption.
- Identifies low-storage conditions.
- Generates usage reports.

### 4. User Management Automation
- Creates Linux users.
- Assigns groups and permissions.
- Automates account administration tasks.

## Technologies Used

- Linux
- Bash Shell Scripting
- Cron Jobs
- Tar
- Systemctl
- Linux Monitoring Commands

## Project Structure

```text
linux-automation-scripting/
│
├── backup.sh
├── health_check.sh
├── disk_monitor.sh
├── user_management.sh
└── README.md
```

## Prerequisites

- Linux Server (Ubuntu/CentOS/RHEL)
- Bash Shell
- Root or Sudo Privileges

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/linux-automation-scripting.git
cd linux-automation-scripting
```

Grant execution permissions:

```bash
chmod +x *.sh
```

## Usage

### Run Backup Script

```bash
./backup.sh
```

### Run Health Check Script

```bash
./health_check.sh
```

### Run Disk Monitoring Script

```bash
./disk_monitor.sh
```

### Run User Management Script

```bash
./user_management.sh
```

## Cron Job Automation

Example: Run backup every day at 11 PM.

```bash
crontab -e
```

Add:

```bash
0 23 * * * /path/to/backup.sh
```

## Sample Output

```text
=================================
      SERVER HEALTH REPORT
=================================
Hostname: server01
Date: 2026-06-20

CPU Usage: 12%
Memory Usage: 45%
Disk Usage: 60%
System Uptime: 15 Days
```

## DevOps Concepts Demonstrated

- Linux Administration
- Automation
- Monitoring
- Backup and Recovery
- Cron Scheduling
- Shell Scripting
- Infrastructure Operations

## Future Enhancements

- Email Notifications
- Slack Alerts
- AWS S3 Backup Integration
- Log Analysis Automation
- Monitoring Dashboard Integration

## Author

Gugha

Aspiring DevOps Engineer focused on Linux, AWS, Docker, Kubernetes, Terraform, GitHub Actions, and Argo CD.
