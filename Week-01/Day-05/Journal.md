# Day 5 – Ubuntu Server Installation & First Linux Server

## Objective
Set up the first Ubuntu Server virtual machine that will serve as the foundation for my cybersecurity lab.

---

## What I Learned

### Virtualization
- Installed Ubuntu Server 24.04.4 LTS on Oracle VirtualBox.
- Understood the difference between a Virtual Machine, VDI, and ISO image.
- Organized my CyberLab directory structure for future labs.

### Installation Decisions
- Chose Ubuntu Server instead of the minimized installation.
- Disabled LVM to keep the storage layout simple while learning.
- Used the default network configuration (DHCP).
- Skipped Ubuntu Pro for now.
- Enabled OpenSSH Server to allow remote administration later.
- Skipped featured server snaps because I want to install tools manually as I learn.

### User & Host Configuration
- Full Name: GaanaSree
- Hostname: soc-lab-01
- Username: cyberadmin

I intentionally chose `cyberadmin` because I want to learn Linux administration, permissions, privilege escalation concepts, and server management.

---

## First Login

Successfully logged into the server and verified the installation.

Commands practiced:

```bash
pwd
whoami
hostname
ls
uname -a
```

---

## Understanding

I learned the purpose of:

- Username vs Hostname
- Why SSH is important
- Why LVM was disabled
- Why Ubuntu Pro wasn't required for my learning lab
- How Ubuntu Server boots after installation

---

## CyberLab Structure

```
CyberLab/
├── Downloads/
├── ISOs/
├── Labs/
├── Notes/
├── Scripts/
├── Snapshots/
├── Tools/
└── VirtualMachines/
```

---

## Key Takeaways

- Built my first Linux server successfully.
- Learned how a server is configured during installation.
- Created the foundation for my cybersecurity home lab.
- Began thinking like a system administrator instead of simply following installation steps.

---

## Reflection

Today was a milestone in my 365-day cybersecurity journey.

Rather than just installing Ubuntu, I built the first server in what will eventually become a complete cybersecurity lab including Wazuh, Active Directory, Splunk, Docker, Elastic, Kali Linux, and many more security tools.
