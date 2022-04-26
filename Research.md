
#   Linux System Monitoring Fundamentals

Monitoring Tools can be divided into various categories like Linux Network Monitoring Tools, Linux Server Monitoring Tools, Linux System Monitoring Tools, Linux Performance Monitoring Tools, Linux Resource Monitor, Linux Bandwidth Monitor, and a different set of command line tools that can perform all in one Linux system monitoring and analyze tasks.

##    Linux Monitoring Tools: A Giant All in One List

###  1. Command Line Tools

It’s a difficult task for every network or system administrator to monitor, analyze and debug Linux system performance problems frequently.
This command line tools come handy when you keep an eye and want to know what’s going on inside your Linux system.

#### Top – Linux Process Monitor

"Top” command is a Linux performance monitoring tool which comes pre-installed in many Linux or Unix system.
“Top” command comes handy when you need to have an overview of all the threads or process running in the system.

It displays various system information including Memory usage, CPU usage, Swap Memory, Buffer Size, Cache Size, Process PID, etc.
It also shows the excessive use of memory and CPU of a system running process.



#### Mytop

Mytop is a MySQL thread and performance monitoring tool which let you have a close look into the database and queries that’s processing in the real times.

####  Htop – Linux Process Monitor

Htop is an advanced Linux process monitoring tool which is similar to “Top” but offers some rich features like interactive process viewer, vertical and horizontal process viewer, shortcut keys, etc
 
It’s a third-party Linux monitoring tool that doesn’t come pre-installed in Linux or Unix system. You need to download and install it in the system.

#### Atop – Performance Monitor for Linux

Atop is a Linux performance monitoring tool which provides reporting of all system threads or process, daily system logging, process activity for long-term data analysis, overloaded system resources, etc. 
It also shows the system activity on CPU, memory, swap, disks (including LVM) and network layers.

#### PowerTOP

If you want a simple tool that diagnoses issues with Linux systems power consumption and power management, then PowerTOP is the right tool. 
Moreover, it has an interactive mode where you can run the experiment with the various system-wide setting to get the best power management setting for the server.

####  Apachetop

Apachetop is a command line tool for monitoring the performance of Apache web server. It’s based on the “mytop” tool.

#### iotop – Monitor Linux Disk I/O

Like “Top” command and “Htop” program, iotop is a python program to show you I/O usages data through “Top” like interface. 
This tool lets you monitor real-time disk I/O and process. Moreover, you can also check the high used disk read and write time for the threads or process.

#### ftptop – File Transfer Protocol Monitor

If you want to know the current FTP connection in your server with total secession, then ftptop is the right tool for you. 
It helps you to show the basic information about total FTP connection; who are the clients; and how many download and upload threads are currently active etc.

#### iftop – Network Bandwidth Monitoring

iftop is another open source and free Linux system monitoring tool that shows important information on network bandwidth utilization on a selected network interface. 
It’s a handy tool comes from “Top” tool family, but instead of only checking CPU usages, it displays a table of current usages on a system network channel.

#### Monit – Linux Process and Services Monitoring

Monit is a free and open source web-based Linux process monitoring tool.
It has an intuitive user interface through which it manages and monitors system threads, files, permissions, directories, programs, filesystems, and checksums. 
Its monitoring services support MySQL, FTP, Mail, Apache, ProFTP, SSH, Nginx, and much more. You can see the data either from a command line or via its default web interface.


###  2. Linux Network Monitoring Tools

Ensuring a healthy and smooth running system is one of the priority tasks to any Linux administrator. 
Here is a generic list of best Linux network monitoring tools:

#### jnettop – Linux Bandwidth Monitor

Jnettop is a helpful tool for monitoring Linux network traffic and bandwidth usages. 
It provides a display of statistics comprising all the online traffic coming across the network. 
This Linux monitoring tool lets the administrator of routers see a list of communication on a network by host and port.

#### ntopng – A Network Traffic Monitor

If you have liked ntop, then you are going to love ntopng also. 
It’s a next-generation version of ntop. 
This tool will provide you with a web-based graphical user interface to monitor network usages and traffic. 
It’s a cross-platform tool which runs on every Unix platform, MacOSX and Windows as well.

#### EtherApe

EtherApe is a free and open source graphical network monitor for Unix system. 
It can show you live network traffic or capable of reading it from tcpdump. 
It supports Ethernet, token ring, PPP, FDDI, WLAN devices, and several encapsulation formats.

#### BandwidthD

BandwidthD is one of the best network monitoring tools for Linux, Unix system, and Windows. 
BandwidthD tracks usages of TCP or IP network subnets and provides a visualized graph image based on an HTML web page. 
It has a DB driven system that supports filtering, searching, custom reports, multiple sensors, etc.

#### ethtool – Linux Network Drivers and Hardware Controller

ethtool is a fantastic Linux utility tool that controls wired Ethernet devices. 
It can be used to get identification and diagnostic information, extended device information, etc. ethtool can control speed, duplex, auto-negotiation, and flow of Ethernet devices.

#### ngrep

ngrep is a PCAP-based tool and like GNU grep but applicable for the network layer that let you dictate hexadecimal or an extended expression to match against data payloads of network packets. 
It supports various network protocols including ICMPv4/6, IPv4/6, UDP, TCP, IGMP, RAW, etc. 
Moreover, It also understands BPF filter logic just like various packet sniffing tools such as Snoop and tcpdump.

#### IPTraf – Real-Time IP LAN Monitoring

IPTraf is one of the best free and open source CLI based Linux Monitor Network Traffic Tools available in the market. 
It collects and displays various useful information including IP traffic passing over the network, packet and bytes count, TCP flag information, OSPF packet types, ICMP details, TCP/UDP traffic breakdowns, etc. 
It supports various interface like local loopback, Ethernet and FDDI interfaces, SLIP, PPP, Parallel Line IP and much more.

####  NetHogs – Linux Bandwidth Monitor

NetHogs is an open source network monitoring software similar to Linux Top command but a small “net top” tool which helps you to monitor Linux Network traffic and bandwidth not breaking the traffic down per subnet or protocol rather grouping it by the network bandwidth process. 
This network monitoring software is helpful to find out which PID is suddenly taking a lot of network traffic and bandwidth and gone wild a bit.

#### MRTG – Router Traffic Monitor

If you are using a network router and wants to know what it does, then MRTG monitoring tool is for you. 
Though initially, the main aim was to monitor only router traffic, now it can do multiple network monitoring tasks as well.

It can monitor SNMP network devices and let you know how much traffic has passed using each thread. 
It provides the stats in an easily understandable picture and HTML pages. 
MRTG is a free, open source software written in Perl programming language and works on Windows, Linux/BSD system, and even Netware systems.

#### Traceroute

Traceroute is a built-in system tool for understanding the network route and estimating the delay of packets throughout the network interface.

#### bmon – Linux Bandwidth Monitor

bmon is a network monitoring and debugging tool to get various stats related to networking and prepare them in an easily understandable way. It supports various output methods like a programmable text output for scripting and an interactive curses user interface.

#### netstat – Network Statistics

Netstat – Network Statistics is one of the best command line tools for monitoring network incoming and outgoing packets and interface statistics. 
This network monitoring software is very useful and handy for a system administrator to identify or troubleshoot network related issues and monitor Linux network performance as well.

#### IPTState

IPTState – IP Tables State is a top-like tool that let you get an interactive session to watch where traffic is crossing your iptables firewall/Netfilter connection. 
You can sort this data and limit the view by various criteria.

#### darkstat – Linux Monitor Network Traffic

darkstat is a small, single threaded, portable, and efficient open source network monitoring software that capture network traffic, calculates usages stats, and display reports over HTTP. 
It supports IPv6 and asynchronous reverse DNS resolution using a child process.


#### tcpdump – Network Packet Analyzer
Tcpdump is a network packet analyzer or packets sniffer software which runs on almost all the dominant Linux distributions. It’s one of the widely used and recommended command line Linux monitoring tools which is used to filter or capture TCP/IP packets that transferred or received on a specific network connection. You can also export or save captured packages in a file for further advanced analysis.

#### ss

“ss” is a Linux command tool which is alternative to the “netstat” network monitoring program. This command is faster and gives more system stats than netstat.

#### Justniffer – Network TCP Packet Sniffer

Justniffer is a network protocol analyzer and TCP packet sniffer tool that captures both low level and high-level network traffic data and produces a customized log from Apache web server log f

#### MTR

mtr is a network diagnostic tool which combines the functionality of both ‘traceroute’ and ‘ping’ programs. 
When mtr gets its first run on a system, It checks the network connection the host that mtr runs on and a user-specified host service.

#### Mpstat

Mpstat is one of the Linux network monitoring tools that collects and shows the information on CPU utilization and performance statistics. 
Without using any option, it will display the Global Average Activities. 
With option ‘-p’ and ‘ALL’ displays statistics one by one that starts from 0. 
To get all the information in a single command, put ‘-u-I ALL -p ALL’. in a word, this command system reports overall processor related data.

#### Pmap

Pmap is a kind of open source network monitoring software that helps to find the complete address space of a process. 
It displays the memory usage map of single or multiple processes. To run the process, you need a unique process ID. 
As a result, you will able to know the total address, bytes, mapping, and mode.

#### collectl – Linux Performance Monitoring Tool

Collectl is another open-source Linux performance monitoring tool helps to know the current system status by collecting performance data. 
This command line tool can play the role of some important utilities like ps, top, vmstat, and more. 
It is able to record and playback the captured data. To process its operation, collectl uses less than 0.1% CPU.

#### DTrace

DTrace is an open source network monitoring software works as a user-level tool, operating system kernel, and device driver. 
Like C and awk, it provides a language ‘D’. This command line can reduce the overhead of gathering and processing data. With this tool, the performance of the production environment increases.

###  3. Linux Server Monitoring Tools

Setting up a server is not a difficult task nowadays, but maintaining a server for optimum performance is a quite tricky and challenging job for every sysadmin. 
As a server administrator, every day you have to keep track of each host and networks; and need to find out the performance and maintenance issues for keeping the server up to date. 
Keeping this scenario in mind, here I am going to share a list of some best Linux server monitoring tools which will ultimately help you to maintain and observe the highest infrastructure performance.

#### Linux Dash – Linux Server Performance Monitoring

Linux Dash is a free and open source server monitoring program that displays important data about your server system like running processes, CPU and Memory usage, file systems, bandwidth usages in real-time through a nice looking web dashboard.

#### Nagios – Linux Server Monitoring Tool

Nagios is a powerful and one of the best leading Linux monitoring tools available out there. 
It’s an all in one Linux performance monitoring tool that is used as an open source network monitoring software, Linux server monitoring tool, and network analyzer.

It helps the system administrator to identify the server related problem and also let you monitor remote Linux, Windows, routers, switches, printers, etc. on a single terminal. 
Nagios indicates and warns you about the critical problem on your server or network that ultimately helps you to necessary remedies before any major problem.

#### Ps

Though Ps is not a complete task manager but still a useful barebones command-line system monitoring tool that helps you to show various running programs. 
It’s a scriptable tool that runs and works well in collaboration with other commands in the terminal which is effective and useful for any system admin.

#### ps

The user need not to install it in the system as it comes prepacked with every Linux distros. Ps has some useful and handy commands arguments which help to sort the processes and IDs.

#### vmstat – Virtual Memory Statistics

vmstat is a Linux command tool which collects and analyze data about your system’s memory, swap, kernel threads, disks, system processes, I/O blocks, CPU activity and much more in real time. 
With the help of this Linux performance tool, you can find out the cause of the problem and issue related to system memory.

#### Wireshark

Wireshark A Free Open Source Network Packet Analyzer for Ubuntu Linux

Wireshark is the most excellent tool that will help you to analyze your network protocol. 
It supports various network protocol. It’s an open source application which allows the users to understand the system of networks and communication protocols. 
Moreover, users can do a troubleshooting network analysis and observe the data on a network.

 
#### Conky

Conky is a free and cross-platform system monitor software for the X Window System. 
Users can install it on any Linux distros as it doesn’t depend on any specific Linux desktop environment. 
It shows various important system information like system temperature, disk usage, CPU and memory usage, network resource stream, download and upload, system notifications and so on.

#### Glances – Real-time Linux System Monitor

“Glances” is responsive, cross-platform and one of the best Linux performance monitoring tools available in the market. 
It smoothly runs on Windows, BSD, MacOS and all the major Linux distros. The user interface is responsive and provides as much information as possible through the web interface or a curses.
This Linux system monitor also works in client/server mode where remote monitoring could be possible through the terminal, Web interface or API (XML-RPC and RESTful). You can also export all those stats as external files or database.

#### nmap

Nmap – “Network Mapper” is an open source and free Linux Server Monitoring Tool which is used for security auditing and network discovery. 
This tool is useful to network and Sysadmin for various network and server related task like managing service upgrade schedules, network inventory, and monitoring server service and host uptime.

#### Monit – Linux Process and Services Monitoring

Monit is a free and open source Unix/Linux server monitoring tool. 
You can use it through both the command line interface and a web interface. 
Monit is an effective server monitoring program that allows you to monitor the server system and services including CPU and RAM usage, file permissions, file hashes, etc.

#### Icinga – Next Generation Server Monitoring

Icinga is a free and open source network monitoring software which can show information on your network devices, processes, and connections. It’s a complete Linux monitoring software that gives real-time monitoring access a simple and interactive web interface. It supports MySQL and PostgreSQL, and functionality can be increased using extensions and modules.

#### IoStat – Input/Output Statistics
iostat

IoStat is a simple command line tool which is used to get various system stats like CPU stats, input and output stats for devices. Moreover, a user can trace storage device performance issues including file system partitions, network file system, devices, and local disks.

 
#### Munin
munin

Munin can be used as both network and system performance monitoring tool. This system resource monitoring tool analyzes the network threads and alerts the sysadmin when any metric kills the server performance. It creates a graph using RRDtool, and you can access those graph data via a web interface.

#### OpenNMS

OpenNMS is an open source network monitoring solution which offers four main functional areas including event management and notifications; discovery and provisioning; service monitoring and data collection.

#### SysUsage
sysusage

SysUsage monitors the server or system information and display an interactive graph reports using rrdtool or javascript jqplot library. This Linux server monitoring tool always grabs system activities using Sar and system commands which seem useful for resource management and performance analysis.

#### Zenoss

Zenoss is one of the mentionable Linux server monitoring tools which offers an intuitive web interface where you can monitor all the important system and network metrics. Moreover, It alerts you about any changes in network configuration, and you can take action accordingly. It also supports Nagios plugins.

#### brainypdm
brainypdm is a web-based Linux system performance and data management monitoring tool. It creates a custom graph using various important performance data from Nagios or generic source.

#### Cacti – Network and System Monitoring
Cacti is a free, open-source and cross-platform network graphing solution that uses the web interface for RRDtool data storage. It provides a lot of features including advanced graph templating, a fast poller, user management, and multiple data acquisition methods.

#### PCP – Performance Co-Pilot
pcp

PCP is one of the best Linux server monitoring tools available in the market that can collect various important or specific data metrics from multiple host services. Moreover, It can make graph data report based on specific metrics using plugin framework which, later on, you can access through a web interface or GUI.

 
#### Zabbix
Zabbix is a complete Linux monitoring tool which provides multiple services like network monitoring, server monitoring, cloud monitoring, service monitoring, and KPI / SLA monitoring. It’s an all in one open source monitoring solution for any IT infrastructure.

Saidar – Displays Live System Statistics
saidar is a very small curses-based application which provides a bunch of basic system information including CPU, processes, load, memory, swap, network I/O and disks I/O.

Uptime
This simple command gives you a handful of information about how long the system has been running, system load average, users currently logged in, etc.

Linux process explorer
Linux process explorer

Linux process explorer is a process monitoring tool similar to the activity monitor for OSX or the Windows system. If you like “top” and “ps,” then I suggest you use the Linux process explorer as it’s more usable and effective to get the system process and resource information.

nmon – Monitor Linux Performance
nmon

nmon which stands for Nigel’s Performance Monitor tool. This tool is used to monitor all sort of Linux resources like CPU and memory usage, disk usage, Top processes, NFS, network, kernel and much more. You can get output data on screen or save it in a separate file which you can export into an RRD database for further analysis.

RRDtool
rrdtool

RRDtool is an open source data logging and graphing system for managing time-series data like CPU load, temperatures, etc. You can extract RRD data using this tool for an easily understandable graphical format.

Df – Disk Free
df

 
df is a pre-installed app in all the Linux or Unix system which is used to know all the available disk space in the file system and the users; it has access to.

Xosview
Xosview is simple and easy to use system monitoring tool for Linux, BSD, IRIX, Solaris and GNU. It offers various information about all the different parts of the including IRQ.

Dstat
dstat

Dstat is the best alternative to iostat, netstat, vmstat, and ifstat. Dstat comes handy for monitoring system resources and performance in real time. It combines all the important data from vmstat, iostat, ifstat, netstat into one single file which also can be exported as CSV file.

Net-SNMP
Net-SNMP is a simple toolset for the collection of accurate information about the server system using SNMP-simple network management protocol.

Free
free

It’s a built-in command that gives information about the total amount of used and free disk space on the system, and the buffers used by the kernel at that given moment.

/Proc file system
The Proc file system displays kernel stats which ultimately let you know about the different hardware devices on your system.

GKrellM
GKrellM is a GUI based Linux monitoring program that displays the status of the system hardware including hard disk, CPU, main memory, network threads, and so on.

Monitorix – System and Network Monitoring
Monitorix is an open source, free and blazing fast Linux system monitoring program. It works smoothly on Linux/Unix system and embedded devices as well. This Linux monitoring tool is suitable for a small server and lets you have a wide range of data metrics through various effective graph and reporting mechanism.

 
Sar
Sysstat is a complete package of Linux Performance Monitoring Tools and sar is a part of this. You can use different commands to collect, report and save different system metrics including memory, CPU and I/O usage.

4. Log Monitoring Tools
Find out the actual cause of any software error, server or system log plays a vital role. Though text mode log is quite difficult to deal with for finding the cause and solution, there are many log management monitoring tools to help you out from the difficult situation. This list of Linux log monitoring tools or program will help you a lot for effective log management.

Sarg – Squid Analysis Report Generator
Sarg is an HTTP proxy log analyzer tool that let you know what and where the users are roaming on the Internet. It’s a free and open source Linux monitoring tool that provides stats and information about Squid proxy server users, IP addresses, sites and times, bytes usages, etc. It’s effortless to install, use and generate outputs in HTML format.

vnStat – Network Traffic Monitor
vnStat is a free, open source, simple to install and use terminal-based BSD/Linux network traffic monitor that keeps a stats log of network traffic for the chosen interfaces. All those stats and information will be collected from the system kernel that ensures light use of system resources and doesn’t sniff any traffic data.

MultiTail
multitail-konsole

Managing and understanding the server log file is always difficult and time-consuming. To overcome this difficulty, MultiTail helps you to see the system log files in a single window. Moreover, you can also merge multiple log files into one single unified file for easy analysis. You can also use various colors for making it easily understandable with the help of regular expression.

GoAccess
GoAccess is ultra fast, open source and Terminal based real-time web access log analyzer. It can analyze web access log from Apache, Nginx, Amazon S3, Elastic Load Balancing, CloudFront, etc. The sysadmin can output the data into JSON, HTML or CSV file format. It can give you valuable HTTP stats, 404s, geolocation, top visitors and much more.

Simple Log Watcher
Like Logwatch, Simple Log Watcher is also designed to monitor systems logs. In spite of creating reports, it watches logs for the regular expression and notifies the sysadmin through the mail or the terminal.

Logwatch
Logwatch is one of the best customizable Linux monitoring tools which analyzes the system log and creates a custom report basing on user-specific areas. This log analyzer can also provide you with a daily report of the activities taking place in the server system. It’s easy to use and works on all the major Linux distros.

5. Linux Network Manager
Now I will discuss the four most recommended Linux network manager which provides a complete network package for every Linux users.

 
ifconfig
ifconfig is one of the best and fundamental Network Management Tools for Linux system. Users can use it as a standalone network management software through CLI or Linux Terminal Emulator. Moreover, many network tools are used as part of this Linux, network manager.

Despite being a command line tool, it becomes more efficient and easy to use, when you came to know what you are doing. It offers you a list of various useful functions, let you do customization, and ensures overall security and privacy.

GNOME Network Manager
Gnome Linux network manager is a prepacked default network management tool which comes with Ubuntu and Gnome desktop environment. Gnome network manager is a simplified network connections manager that is well integrated within the Gnome system which comes very handy when basic network system handling comes into the focus.

Network Tools
“Network Tools” is a much more advanced Linux network manager found in Ubuntu system. This “network tools” is a counterpart of the Gnome network manager where users can perform advanced level network detection task and sorting out the problems. This network management software let you know about various network activities and problems as well.

Wicd
Wicd is the best Linux network manager available in the market now. It’s now a default network manager on a wide range of Linux distros. It provides all the advanced settings that a user need to configure IP settings, network ID, individual network connection, low- level systems connect and interact, etc. Wicd also ensures privacy when you use it in conjunction with Tor.

6. Linux Performance Monitoring Tools
Are you responsible for maintaining Linux infrastructure? Here I have discussed some best Linux performance monitoring tools which will help you to monitor, understand and manage the health and performance of each Linux system elements including CPU, memory, storage, and network.

Gnome System Monitor
Gnome system monitor is lightweight and minimalistic, but powerful Linux task manager for the Gnome shell desktop environment. This Linux system monitoring tool shows you various important information about hard drive space, RAM/SWAP usage, running process and time, network activity, etc. in an easily understandable display.

Gnome System Monitor

Sysstat – All-in-One System Performance Monitoring
sysstat - tcgraph

Sysstat is another one of the best Linux monitoring tools which are a combo package comprising many Linux performance monitoring tools like pidstat, sadf, iostat, etc. This all in one performance solution displays various useful stats about your Linux system. It’s available on all the major Linux distros. Sysstat shows data about CPU, RAM, and SWAP usage; monitors system kernel activity, sockets, TTY, NFS server, and file systems.

 
VnStat PHP – Monitoring Network Bandwidth
As vnStat is a console-based network traffic logger, so it will be tricky for the beginners to use or analyze the data. In this case, vnStat PHP helps you to understand the vnStat data through a nice looking web-based frontend. You can use this GUI to check network traffic usages based on hourly, daily, monthly and full summary report.

Nload – Linux Bandwidth Monitor
Nload is a command line Linux monitoring tool to observe network traffic and bandwidth in real time. This network traffic monitoring tool lets you visualize the in- and outgoing traffic through two interactive graphs. It also provides some additional but important information about total data transferred using any specific network channel and min/max network usages.

Observium – Network Management and Monitoring
Observium is yet another useful network management software designed to manage your server network easily. There are both free and paid versions with the support of MySQL DB. It’s a cross-platform network monitoring software which works on Windows, Linux, FreeBSD and more. It can handle and monitor hundreds of host services around the world via an intuitive web interface to output various information.

SmokePing
SmokePing is a free and open source network monitoring software. It helps you to keep track of your network latency. It offers a wide range of latency measurement plugins which ultimately let you do a various task like configure an alert system, slave system for distributed measurement, latency visualization, etc. through interactive GUI and graphs.

KSysGuard
KSysGuard is the default Linux task and system performance monitor for KDE desktop environment. One of the notable features of this Linux task manager is it supports client/server architecture that let you allows monitor both remote and localhost.

ksysguard

It’s called a no-nonsense task manager which allows you to kill/end the problematic program easily. KSysGuard can be used both from the graphical interface and Terminal mode.

Shinken monitoring
Shinken is a server monitoring framework which is a total rewrite of Python Nagios® Core for increasing flexibility, scalability and managing a large environment. It’s a featured-packed and ready to run monitoring packs which keeps your Nagios® configuration and plugins intact.

Lsof – List Open Files
Lsof is a great tool used in a Linux or Unix system to know about all the open files and system processes. It’s a built-in Linux system monitoring tool that you can use to see all the open files by processes and network connections. You can sort out the active process by names or users, and it let you kill all threads that are used by a specific user. This command tool will be helpful when it shows an error that the files are used, or disk can’t be unmounted. In this situation, Lsof will let you know which users are using files or system threads are in use.

Webmin
Webmin is a web-based system configuration tool for a Unix-like server. Though this tool is developed for the Linux system, still you can also install it on the Windows platform as well. It provides a simple, easy-to-use, and modern user interface for your server.

 
Webmin: A Web-based Control Panel For Unix-like System Administration

With the help of Webmin, you can configure the system’s internal components like users, disk quotas, and service files. Moreover, you can also control and modify the servers open source applications such as PHP, MySQL, and Apache HTTP server.

Arpwatch – Ethernet Activity Monitor
Arpwatch is a kind of Linux performance monitoring tools that help to monitor Address Resolution Protocol traffic on a computer network. With the help of Arpwatch, you can keep the database of all identified IP and MAC addresses pairings. It is a great computer security program written in the C programming language. To get installed, you have to use the apt-get command.

acct or psacct – Monitor User Activity
Acct and psacct are open source applications to monitor users activities on a system. Besides tracking the activity, it also checks what resources are being consumed. Acct or psacct allows observing how long the users connected to the system. In total, these tools help in various administrative tasks.

Whowatch
Whowatch is a popular and important console application to let you know about the different users with their activities. As it works in real time, you can get the up to date information from this program. It allows the data like login name, tty, user’s process, and more. Whowatch doesn’t need any command line options.

Suricata – Network Security Monitoring
Suricata is a free network security monitoring program that enables intrusion detection in real time, inline intrusion prevention, and offline pcap processing. With the help of its powerful signature language, it can inspect the network traffic. It takes care of security, usability, and efficiency of the system.

Stat
The stat is a useful command in Linux used to view file and file system status. It has its own custom format beside the default to display information. It enables the following of symbolic links and print information in a terse form.

Collectd
Collectd is a kind of command program for Linux that receives statistics of the system and makes them available in several ways. It mainly collects, transfers, and stores performance data from various network equipment. It is a daemon that comes with a huge collection of plug-ins into its default configuration file.

#### Strace

Strace is a useful Linux command line tool that can be used for diagnostic, instructional, and debugging operation. It’s a powerful application to capture and record the system calls made by a process and the signals received by the process. You can get the summary of Linux process and also can trace specific system calls.

#### Ulimit

Whether you want to change the number of open files in the Linux system, Ulimit is a great command line tool for this. You need to have the root access to your system. You can check and configure both the user level and global limits for the maximum quantity of opened files.

 
#### CPUlimit

Cpulimit is another useful utility of Linux system to solve some particular problems. 
It enables itself to the system load dynamically and fast. When any particular process consumes more CPU usage and affects the overall performance, Cpulimit helps to get rid of this. It controls the batch jobs when you don’t require to consume more CPU usage. The amount of the usage will be distributed and controlled by sending SIGSTOP and SIGCONT POSIX signals.

#### Lshw

Lshw is an open source Linux command which shows the detailed report about the hardware system. 
You will get complete information on a single screen with the help of this program. 
Lshw can provide you the report of firmware version, CPU version and speed, graphics card, bus speed, memory configuration, and more. 
It has also some special features are available to detect partial or full information.

#### W

W is one of the Linux basic command tools to show information about the users who are currently logged into a system. 
For an individual user, you will get the report on a login name, tty name, login time, JCPU, remote host, and more.
