# Linux Mastery: Study Notes

## 1. Linux Learning Roadmap
Step 1: Linux Essentials
Step 2: LPIC-1
Step 3: LPIC-2
Step 4: LPIC-3

---

## 2. The Linux Ecosystem & History

### What is Linux?
Linux: Technically refers only to the Kernel.
GNU/Linux: The complete Operating System (Linux kernel + GNU tools/libraries).

### Historical Context
Linus Torvalds (1991): Created the Linux kernel.
Richard Stallman: Leader of the GNU Project.
Open Source Philosophy: The freedom to use, study, modify, and redistribute software.
UNIX Legacy: Linux is inspired by UNIX; modern graphical systems like X.org/X11 evolved from the UNIX X Window system.

---

## 3. Operating System Architecture & Internals

### The Core: The Kernel
The Kernel is the "glue of the system". Its main tasks:
Hardware Interfacing: Managing NICs, disk drives, and peripherals.
Memory Management: Handling RAM allocation.
CPU Scheduling: Managing CPU time for processes.
Inter-Process Communication (IPC): Allowing processes to communicate.

### Kernel Space vs. User Space
1. Kernel Space: A protected zone for the kernel to manage hardware and resources.
2. User Space: A restricted zone where user applications, shells, and libraries run.

---

## 4. Linux Distributions & Components

### Distribution Families
Debian Family: Ubuntu, Linux Mint, Kali Linux, BackTrack.
Fedora/RedHat Family: RHEL, CentOS, Fedora, Oracle Linux.
SUSE Family: openSUSE, SLES.

### Key System Components
Shell: Command-line interface (e.g., Bash).
GUI & Display Servers: Graphical layer (e.g., X.org/X11).
Desktop Environments: Visual interfaces (e.g., GNOME, KDE).
System Libraries: Code (like libc) for software-to-kernel communication.
Daemons: Background services for networking, security, and system tasks.

