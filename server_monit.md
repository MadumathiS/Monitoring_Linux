#                  3. Linux Server Monitoring Tools

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

#### Saidar – Displays Live System Statistics

saidar is a very small curses-based application which provides a bunch of basic system information including CPU, processes, load, memory, swap, network I/O and disks I/O.

![saidar.jpg](/saidar.jpg)

#### Uptime

This simple command gives you a handful of information about how long the system has been running, system load average, users currently logged in, etc.

`madhu@INNERG:~/github/Monitoring_Linux$ uptime
 16:20:04 up  3:56,  0 users,  load average: 0.52, 0.58, 0.59
madhu@INNERG:~/github/Monitoring_Linux$`


#### Linux process explorer

Linux process explorer

Linux process explorer is a process monitoring tool similar to the activity monitor for OSX or the Windows system. If you like “top” and “ps,” then I suggest you use the Linux process explorer as it’s more usable and effective to get the system process and resource information.

#### nmon – Monitor Linux Performance


nmon

nmon which stands for Nigel’s Performance Monitor tool. This tool is used to monitor all sort of Linux resources like CPU and memory usage, disk usage, Top processes, NFS, network, kernel and much more. You can get output data on screen or save it in a separate file which you can export into an RRD database for further analysis.

![nmon.jpg](/nmon.jpg)


#### RRDtool

rrdtool

RRDtool is an open source data logging and graphing system for managing time-series data like CPU load, temperatures, etc. You can extract RRD data using this tool for an easily understandable graphical format.

#### Df – Disk Free

df

`madhu@INNERG:~/github/Monitoring_Linux$ df
Filesystem     1K-blocks      Used Available Use% Mounted on
rootfs         487725052 201442088 286282964  42% /
none           487725052 201442088 286282964  42% /dev
none           487725052 201442088 286282964  42% /run
none           487725052 201442088 286282964  42% /run/lock
none           487725052 201442088 286282964  42% /run/shm
none           487725052 201442088 286282964  42% /run/user
tmpfs          487725052 201442088 286282964  42% /sys/fs/cgroup
C:\            487725052 201442088 286282964  42% /mnt/c`
 
df is a pre-installed app in all the Linux or Unix system which is used to know all the available disk space in the file system and the users; it has access to.

#### Xosview

Xosview is simple and easy to use system monitoring tool for Linux, BSD, IRIX, Solaris and GNU. It offers various information about all the different parts of the including IRQ.

#### Dstat

dstat

Dstat is the best alternative to iostat, netstat, vmstat, and ifstat. Dstat comes handy for monitoring system resources and performance in real time. It combines all the important data from vmstat, iostat, ifstat, netstat into one single file which also can be exported as CSV file.

`--total-cpu-usage-- -net/total- ---paging-- ---system--
usr sys idl wai stl| recv  send|  in   out | int   csw
 33  11  56   0   0|   0     0 |   0     0 |  51    28
 31   4  65   0   0|   0     0 |   0     0 |   0     0
 25   2  72   0   0|   0     0 |   0     0 |   0     0
 26   1  73   0   0|   0     0 |   0     0 |   0     0
 28   8  64   0   0|   0     0 |   0     0 |   0     0
 26   3  72   0   0|   0     0 |   0     0 |   0     0
 25   2  73   0   0|   0     0 |   0     0 |   0     0
 25   0  74   0   0|   0     0 |   0     0 |   0     0
 28   7  66   0   0|   0     0 |   0     0 |   0     0
 27   2  71   0   0|   0     0 |   0     0 |   0     0
 25   2  73   0   0|   0     0 |   0     0 |   0     0

 27   3  71   0   0|   0     0 |   0     0 |   0     0

 29   6  65   0   0|   0     0 |   0     0 |   0     0
 40   2  59   0   0|   0     0 |   0     0 |   0     0
 32   3  65   0   0|   0     0 |   0     0 |   0     0
 26   1  73   0   0|   0     0 |   0     0 |   0     0
 27   5  67   0   0|   0     0 |   0     0 |   0     0
 27   1  72   0   0|   0     0 |   0     0 |   0     0
 26   1  73   0   0|   0     0 |   0     0 |   0     0
 30   4  66   0   0|   0     0 |   0     0 |   0     0
 33  14  52   0   0|   0     0 |   0     0 |   0     0
 27   3  69   0   0|   0     0 |   0     0 |   0     0
 29   3  68   0   0|   0     0 |   0     0 |   0     0
 29   6  65   0   0|   0     0 |   0     0 |   0     0
 27   1  72   0   0|   0     0 |   0     0 |   0     0
 28   4  68   0   0|   0     0 |   0     0 |   0     0
 26   2  73   0   0|   0     0 |   0     0 |   0     0
 29   5  66   0   0|   0     0 |   0     0 |   0     0
 27   3  70   0   0|   0     0 |   0     0 |   0     0
 27   1  72   0   0|   0     0 |   0     0 |   0     0
 28   2  70   0   0|   0     0 |   0     0 |   0     0
 29   6  65   0   0|   0     0 |   0     0 |   0     0
 28   4  68   0   0|   0     0 |   0     0 |   0     0
 27   2  71   0   0|   0     0 |   0     0 |   0     0
 27   3  70   0   0|   0     0 |   0     0 |   0     0
 29   7  64   0   0|   0     0 |   0     0 |   0     0
 29   2  69   0   0|   0     0 |   0     0 |   0     0`


#### Net-SNMP

Net-SNMP is a simple toolset for the collection of accurate information about the server system using SNMP-simple network management protocol.


#### Free

free

It’s a built-in command that gives information about the total amount of used and free disk space on the system, and the buffers used by the kernel at that given moment.

`madhu@INNERG:~$ free
              total        used        free      shared  buff/cache   available
Mem:        8265556     6410652     1625552       17720      229352     1721172
Swap:      25165824      551012    24614812`

#### /Proc file system

The Proc file system displays kernel stats which ultimately let you know about the different hardware devices on your system.

GKrellM
GKrellM is a GUI based Linux monitoring program that displays the status of the system hardware including hard disk, CPU, main memory, network threads, and so on.

Monitorix – System and Network Monitoring
Monitorix is an open source, free and blazing fast Linux system monitoring program. It works smoothly on Linux/Unix system and embedded devices as well. This Linux monitoring tool is suitable for a small server and lets you have a wide range of data metrics through various effective graph and reporting mechanism.

 
#### Sar

Sysstat is a complete package of Linux Performance Monitoring Tools and sar is a part of this. You can use different commands to collect, report and save different system metrics including memory, CPU and I/O usage.
