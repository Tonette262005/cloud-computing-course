# 💻 System Information

This document contains the system information collected from the Ubuntu 24.04 environment provided by KillerCoda during **Laboratory 01 – Welcome to the Cloud**.

The information was collected using Linux commands in the KillerCoda terminal.

---

## 🐧 Operating System

### Command Used

cat /etc/os-release

### Output

PRETTY_NAME="Ubuntu 24.04.4 LTS"
NAME="Ubuntu"
VERSION_ID="24.04"
VERSION="24.04.4 LTS (Noble Numbat)"
VERSION_CODENAME=noble
ID=ubuntu
ID_LIKE=debian
UBUNTU_CODENAME=noble
```

### Operating System Details

| Information | Details |
|---|---|
| Operating System | Ubuntu |
| Version | Ubuntu 24.04.4 LTS |
| Version ID | 24.04 |
| Codename | Noble Numbat |
| Version Codename | noble |
| System Family | Debian-based Linux |

---

## 🖥️ CPU Information

### CPU Information Collected

Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Address sizes:       39 bits physical, 48 bits virtual
Byte Order:          Little Endian
CPU(s):              1
On-line CPU(s) list: 0
Vendor ID:           GenuineIntel
Model name:          Intel Xeon E312xx (Sandy Bridge, IBRS update)
CPU family:          6
Model:               42
Thread(s) per core:  1
Core(s) per socket:  1
Socket(s):            1
Stepping:             1

### CPU Summary

| Information | Details |
|---|---|
| Architecture | x86_64 |
| CPU Modes | 32-bit, 64-bit |
| CPU(s) | 1 |
| CPU Vendor | GenuineIntel |
| CPU Model | Intel Xeon E312xx (Sandy Bridge, IBRS update) |
| CPU Family | 6 |
| Model Number | 42 |
| Threads per Core | 1 |
| Cores per Socket | 1 |
| Sockets | 1 |
| Byte Order | Little Endian |

---
##

### Memory Summary

| Information | Amount |
|---|---:|
| Total Memory | 1.9 GiB |
| Used Memory | 426 MiB |
| Free Memory | 822 MiB |
| Shared Memory | 1.1 MiB |
| Buffer/Cache | 822 MiB |
| Available Memory | 1.4 GiB |
| Total Swap | 1.0 GiB |
| Used Swap | 0 B |
| Free Swap | 1.0 GiB |

### Notes

The KillerCoda environment has approximately **1.9 GiB of RAM**.

At the time the command was executed:

- **426 MiB** of memory was used.
- **822 MiB** of memory was free.
- **1.4 GiB** of memory was available.
- The system had **1.0 GiB of swap space**.
- **0 B** of swap space was being used.

---

## 💾 Disk Space Information

Filesystem      Size  Used Avail Use% Mounted on
tmpfs           191M  1020K  190M   1% /run
/dev/vda1        19G   5.4G   13G  30% /
tmpfs           952M    84K  952M   1% /dev/shm
tmpfs           5.0M     0B  5.0M   0% /run/lock
/dev/vda16      881M   117M  703M  15% /boot
/dev/vda15      105M   6.2M   99M   6% /boot/efi
tmpfs           191M   8.0K  191M   1% /run/user/1001

### Main Disk Summary

| Filesystem | Size | Used | Available | Use | Mount Point |
|---|---:|---:|---:|---:|---|
| `/dev/vda1` | 19G | 5.4G | 13G | 30% | `/` |
| `/dev/vda16` | 881M | 117M | 703M | 15% | `/boot` |
| `/dev/vda15` | 105M | 6.2M | 99M | 6% | `/boot/efi` |

### Notes

The main filesystem is mounted at `/` and has a total size of approximately **19 GB**.

At the time of checking:

- **5.4 GB** was used.
- **13 GB** was available.
- Disk usage was approximately **30%**.

The system also contains separate boot and EFI partitions.

---

# 📌 Notes

- The system information was collected from the **Ubuntu 24.04 KillerCoda Playground**.
- The environment is a **virtualized Linux environment**.
- The operating system is **Ubuntu 24.04.4 LTS**.
- The system uses the **6.8.0-136-generic** Linux kernel.
- The CPU information reports an **Intel Xeon E312xx (Sandy Bridge, IBRS update)** processor.
- The system reports **1.9 GiB of RAM**.
- The system has **1.0 GiB of swap space**.
- The main filesystem has approximately **19 GB of storage**.
- At the time of checking, approximately **5.4 GB** of the main filesystem was used.
- Approximately **13 GB** was available on the main filesystem.
- The environment uses **KVM** for virtualization.
- The commands used in this activity demonstrate basic Linux system administration and system monitoring.
- The displayed resource values represent the state of the KillerCoda environment when the commands were executed and may change in another session.

---

# 🎯 Learning Reflection

Through this activity, I learned how to use basic Linux commands to inspect and document a cloud-based computing environment.

I learned how to identify the operating system, kernel version, CPU architecture, processor information, memory usage, disk space, and virtualization configuration of a Linux environment.

The activity also helped me understand how cloud computing environments can provide virtual machines with allocated computing resources such as processing power, memory, storage, and virtualization.

The commands `cat`, `grep`, `uname`, `lscpu`, `free`, and `df` are useful for gathering system information. These commands can help cloud computing students and system administrators monitor and understand the resources available in a Linux environment.

---

# ✅ Conclusion

The system information collected from KillerCoda demonstrates the basic characteristics of a virtualized Ubuntu cloud environment. The environment uses **Ubuntu 24.04.4 LTS**, an **x86_64 architecture**, an **Intel Xeon E312xx processor**, approximately **1.9 GiB of RAM**, and approximately **19 GB of main disk storage**.

This activity provided practical experience in using Linux terminal commands to inspect system resources and document technical information in Markdown.
