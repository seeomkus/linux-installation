# Linux Installation Guides

A collection of step-by-step installation guides for Linux operating systems and related software, with screenshots and detailed configuration notes.

---

## Repository Structure

```
linux-installation/
├── almalinux-8-for-oracle-database/
│   ├── almalinux_8_10_os_installation_guide.md
│   └── images/
│       └── *.png  (31 screenshots)
└── oraclelinux-6-for-oracle-database/
    ├── oraclelinux_6_10_os_installation_guide.md
    └── images/
        └── *.png  (49 screenshots)
```

---

## Guides

### AlmaLinux 8 — Oracle Database Series

A complete series of guides for setting up **AlmaLinux 8.10** as a platform for **Oracle Database 19c** on VMware Workstation 16.

| # | Guide | Description |
|---|-------|-------------|
| 1 | [AlmaLinux 8.10 OS Installation Guide](almalinux-8-for-oracle-database/almalinux_8_10_os_installation_guide.md) | Full OS installation on VMware Workstation 16 — language, partitioning, network, software selection, post-install CLI config |
| 2 | [Pre Install Oracle Database 19c](https://github.com/seeomkus/oracle-installation/blob/main/oracle-database-19c-linux-al8/oracle_database_19c_pre_installation_guide_almalinux_8_10.md) | Kernel parameters, OS packages, Oracle user/groups, resource limits |
| 3 | [Install Oracle Database 19c](https://github.com/seeomkus/oracle-installation/blob/main/oracle-database-19c-linux-al8/oracle_database_19c_installation_guide_almalinux_8_10.md) | Oracle Universal Installer (OUI), database creation |
| 4 | [Post Install Oracle Database 19c](https://github.com/seeomkus/oracle-installation/blob/main/oracle-database-19c-linux-al8/oracle_database_19c_post_installation_guide_almalinux_8_10.md) | Listener config, instance validation, initial setup |

---

### Oracle Linux 6 — Oracle Database Series

A complete series of guides for setting up **Oracle Linux 6.10** as a platform for **Oracle Database 11g** on VMware Workstation 16.

| # | Guide | Description |
|---|-------|-------------|
| 1 | [Oracle Linux 6.10 OS Installation Guide](oraclelinux-6-for-oracle-database/oraclelinux_6_10_os_installation_guide.md) | Full OS installation on VMware Workstation 16 — language, custom partitioning, bridge network, software selection |
| 2 | [Install Oracle Database 11g](https://github.com/seeomkus/oracle-installation/blob/main/oracle-database-11g-linux-ol6/oracle-database-11g-installation-linux-ol6.md) | Oracle Universal Installer (OUI), listener config, database creation |

---

## Environment

| Series | OS | Platform | Database |
|--------|----|----------|----------|
| **AlmaLinux 8** | AlmaLinux 8.10 (Cerulean Leopard) | VMware Workstation 16.0.0 | Oracle Database 19c |
| **Oracle Linux 6** | Oracle Linux Server 6.10 | VMware Workstation 16.0.0 | Oracle Database 11g Release 2 |
