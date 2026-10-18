# Day 29 — Linux File System

## Goal
Understand the Linux directory structure and identify where system files, configuration files, logs, user directories, and essential commands are located.

## Topics Covered
- Root directory (`/`)
- `/home`
- `/etc`
- `/var`
- `/bin`
- SSH configuration file location

## 1. Root Directory (`/`)
The root directory is the starting point of the Linux filesystem. Other directories are organized under it.

Commands practised:
```bash
cd /
ls -la
pwd
```

Expected `pwd` output:
```text
/
```

## 2. Home Directory (`/home`)
The `/home` directory contains personal directories for regular users.

Commands practised:
```bash
cd /home
ls -la
pwd
```

My Ubuntu system displayed the `marvan` and `user` directories.

## 3. Configuration Directory (`/etc`)
The `/etc` directory contains system and service configuration files.

Commands practised:
```bash
cd /etc
ls -la
pwd
```

Expected `pwd` output:
```text
/etc
```

## 4. Variable Data (`/var`)
The `/var` directory stores variable data, including system logs.

Commands practised:
```bash
cd /var
ls -la
ls -la /var/log
```

Examples observed in `/var/log`:
- `kern.log` — kernel-related messages
- `syslog` — general system messages
- `dpkg.log` — package management activity

## 5. Essential Commands (`/bin`)
The `/bin` directory contains essential command programs. On Ubuntu, `/bin` may be linked to `/usr/bin`.

Commands practised:
```bash
cd /bin
ls -la
pwd
```

## 6. SSH Configuration File Check
I checked whether the SSH server configuration file exists:

```bash
ls -l /etc/ssh/sshd_config
```

The file was not found at that path.

I then checked the SSH directory:

```bash
ls -la /etc/ssh
```

The directory contained `ssh_config`, `ssh_config.d`, and SSH host key files. The `sshd_config` file was not listed.

**Observation:** The SSH client configuration file `ssh_config` is different from the SSH server configuration file `sshd_config`.

No installation or configuration changes were made.

## Linux Filesystem Map

```text
/
├── bin/      Essential command programs
├── etc/      System configuration files
├── home/     Regular users' personal directories
├── var/      Variable data, including logs
└── usr/      Many user applications and utilities
```

## Key Commands Learned

| Command | Purpose |
|---|---|
| `cd /` | Move to the root directory |
| `cd /home` | Move to `/home` |
| `cd /etc` | Move to `/etc` |
| `cd /var` | Move to `/var` |
| `cd /bin` | Move to `/bin` |
| `ls -la` | List files, details, and hidden entries |
| `pwd` | Display the current directory |
| `ls -la /var/log` | List log files and directories |
| `ls -la /etc/ssh` | Inspect the SSH configuration directory |

## Day 29 Summary
I explored five important Linux directories using my Ubuntu virtual machine and practised basic navigation and listing commands. I also checked the SSH configuration directory and documented my findings.
