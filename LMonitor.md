#          20 Command Line Tools to Monitor Linux Performance


## 1. Top – Linux Process Monitoring


Linux Top command is a performance monitoring program that is used frequently by many system administrators to monitor Linux performance and it is available under many Linux/Unix-like operating systems.

The top command is used to display all the running and active real-time processes in an ordered list and updates it regularly. It displays CPU usage, Memory usage, Swap Memory, Cache Size, Buffer Size, Process PID, User, Commands, and much more.

It also shows high memory and cpu utilization of running processes. The top command is much useful for system administrators to monitor and take corrective action when required. Let’s see the top command in action.


## 2. VmStat – Virtual Memory Statistics

Linux VmStat command is used to display statistics of virtual memory, kernel threads, disks, system processes, I/O blocks, interrupts, CPU activity, and much more.

Install VmStat in Linux
By default vmstat command is not available under Linux systems you need to install a package called sysstat (a powerful monitoring tool) that includes a vmstat program.

$ sudo yum install sysstat      [On Older CentOS/RHEL & Fedora]
$ sudo dnf install sysstat      [On CentOS/RHEL/Fedora/Rocky Linux & AlmaLinux]
$ sudo apt-get install sysstat  [On Debian/Ubuntu & Mint]
$ sudo pacman -S sysstat        [On Arch Linux]
The common usage of vmstat command format is.

#vmstat

## 3. Lsof – List Open Files

The lsof command is used in many Linux/Unix-like systems to display a list of all the open files and the processes. The open files included are disk files, network sockets, pipes, devices, and processes.

One of the main reasons for using this command is when a disk cannot be unmounted and displays the error that files are being used or opened. With this command, you can easily identify which files are in use.

The most common format for lsof command is.

#lsof

## 4. Tcpdump – Network Packet Analyzer

The tcpdump command is one of the most widely used command-line network packet analyzer or packets sniffer programs that is used to capture or filters TCP/IP packets that are received or transferred on a specific interface over a network.

It also provides an option to save captured packages in a file for later analysis. tcpdump is almost available in all major Linux distributions.

#tcpdump -i enp0s3


## 5. Netstat – Network Statistics

The netstat is a command-line tool for monitoring incoming and outgoing network packets statistics as well as interface statistics. It is a very useful tool for every system administrator to monitor network performance and troubleshoot network-related problems.

#netstat -a | more

While in present-day netstat has been deprecated in favor of the ss command, you may still discover netstat in your networking toolkit.

## 6. Htop – Linux Process Monitoring

htop is a much advanced interactive and real-time Linux process monitoring tool, which is much similar to Linux top command but it has some rich features like a user-friendly interface to manage processes, shortcut keys, vertical and horizontal views of the processes, and much more.

#htop

htop is a third-party tool, which doesn’t come with Linux systems, you need to install it using your system package manager tool. 

## 7. Iotop – Monitor Linux Disk I/O

iotop is also much similar to top command and htop program, but it has an accounting function to monitor and display real-time Disk I/O and processes.

iotop tool is much useful for finding the exact process and high used disk read/writes of the processes.

Install Iotop in Linux
By default, the iotop command is not available under Linux and you need to install it as shown.

$ sudo yum install iotop      [On Older CentOS/RHEL & Fedora]
$ sudo dnf install iotop      [On CentOS/RHEL/Fedora/Rocky Linux & AlmaLinux]
$ sudo apt-get install iotop  [On Debian/Ubuntu & Mint]
$ sudo pacman -S iotop        [On Arch Linux]
The common usage of iotop command format is.

#iotop

## 8. Iostat – Input/Output Statistics

iostat is a simple tool that will collect and show system input and output storage device statistics. This tool is often used to trace storage device performance issues including devices, local disks, remote disks such as NFS.

Install Iostat in Linux
To get the iostat command, you need to install a package called sysstat as shown.

$ sudo yum install sysstat      [On Older CentOS/RHEL & Fedora]
$ sudo dnf install sysstat      [On CentOS/RHEL/Fedora/Rocky Linux & AlmaLinux]
$ sudo apt-get install sysstat  [On Debian/Ubuntu & Mint]
$ sudo pacman -S sysstat        [On Arch Linux]
The common usage of iostat command format is.

#iostat

## 9. IPTraf – Real-Time IP LAN Monitoring

IPTraf is an open-source console-based real-time network (IP LAN) monitoring utility for Linux. It collects a variety of information such as 
IP traffic monitor that passes over the network, including TCP flag information, ICMP details, TCP/UDP traffic breakdowns, TCP connection packet, and byte counts.
It also gathers information of general and detailed interface statistics of TCP, UDP, IP, ICMP, non-IP, IP checksum errors, interface activity, etc.

## 10. Psacct or Acct – Monitor User Activity

psacct or acct tools are very useful for monitoring each user’s activity on the system. Both daemons run in the background and keep a close watch on the overall activity of each user on the system and also what resources are being consumed by them.

These tools are very useful for system administrators to track each user’s activity like what they are doing, what commands they issued, how much resources are used by them, how long they are active on the system etc.

## 11. Monit – Linux Process and Services Monitoring

Monit is a free open source and web-based process supervision utility that automatically monitors and manages system processes, programs, files, directories, permissions, checksums, and filesystems.

It monitors services like Apache, MySQL, Mail, FTP, ProFTP, Nginx, SSH, and so on. The system status can be viewed from the command line or using its own web interface.

## 12. NetHogs – Monitor Per Process Network Bandwidth

NetHogs is an open-source nice small program (similar to Linux top command) that keeps a tab on each process network activity on your system. It also keeps a track of real-time network traffic bandwidth used by each program or application.

## 13. iftop – Network Bandwidth Monitoring

iftop is another terminal-based free open source system monitoring utility that displays a frequently updated list of network bandwidth utilization (source and destination hosts) that passing through the network interface on your system.

iftop is considered for network usage, what ‘top‘ does for CPU usage. iftop is a ‘top‘ family tool that monitors a selected interface and displays a current bandwidth usage between two hosts.


## 14. Monitorix – System and Network Monitoring

Monitorix is a free lightweight utility that is designed to run and monitor system and network resources as many as possible in Linux/Unix servers.

It has a built-in HTTP web server that regularly collects system and network information and displays them in graphs. It Monitors system load average and usage, memory allocation, disk driver health, system services, network ports, mail statistics (Sendmail, Postfix, Dovecot, etc), MySQL statistics, and many more.

It is designed to monitor overall system performance and helps in detecting failures, bottlenecks, abnormal activities, etc.


## 15. Arpwatch – Ethernet Activity Monitor

Arpwatch is a kind of program that is designed to monitor Address Resolution of (MAC and IP address changes) of Ethernet network traffic on a Linux network.

It continuously keeps watch on Ethernet traffic and produces a log of IP and MAC address pair changes along with a timestamp on a network. It also has a feature to send email alerts to administrators, when a pairing is added or changes. It is very useful in detecting ARP spoofing on a network.

## 16. Suricata – Network Security Monitoring

Suricata is a high-performance open-source Network Security and Intrusion Detection and Prevention Monitoring System for Linux, FreeBSD, and Windows.

It was designed and owned by a non-profit foundation OISF (Open Information Security Foundation).

## 17. VnStat PHP – Monitoring Network Bandwidth

VnStat PHP is a web-based frontend application for the most popular networking tool called “vnstat“. VnStat PHP monitors network traffic usage in nicely graphical mode.

It displays a total IN and OUT network traffic usage in hourly, daily, monthly, and full summary reports.

## 18. Nagios – Network/Server Monitoring

Nagios is a leading open source powerful monitoring system that enables network/system administrators to identify and resolve server-related problems before they affect major business processes.

With the Nagios system, administrators can able to monitor remote Linux, Windows, Switches, Routers, and Printers on a single window. It shows critical warnings and indicates if something went wrong in your network/server which indirectly helps you to begin remediation processes before they occur.

## 19. Nmon: Monitor Linux Performance

Nmon (stands for Nigel’s performance Monitor) tool, which is used to monitor all Linux resources such as CPU, Memory, Disk Usage, Network, Top processes, NFS, Kernel, and much more. This tool comes in two modes: Online Mode and Capture Mode.

The Online Mode is used for real-time monitoring and Capture Mode is used to store the output in CSV format for later processing.

## 20. Collectl: All-in-One Performance Monitoring Tool

Collectl is yet another powerful and feature-rich command-line-based utility, that can be used to gather information about Linux system resources such as CPU usage, memory, network, inodes, processes, nfs, TCP, sockets, and much more.



