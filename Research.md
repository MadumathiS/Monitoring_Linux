All server monitoring programs have a few things in common. They set a goal of ensuring that a server is performing optimally, they provide information that lets Linux administrators understand what’s going on, and sometimes automate their responses to those situations. The Linux system monitor tools accomplish this by gathering data on each server’s key performance indicators (KPIs), network connectivity, and application availability.

Specifically, you use Linux system monitoring programs to ensure that:

The hardware is working.

The server is up and running.

The server resources are sufficient for mission-critical applications and services to work at peak performance.

No resource bottlenecks are slowing things down.

System administrators are alerted when a KPI fails to meet its specified metric.

Data is presented in a visual manner – such as dashboards, graphs, and weather maps — to visualize trends that aren’t obvious in raw data.


These programs do this by tracking:

The server’s real-time status

Data collected over time to enable analysis of long-term trends.

Data collected to determine the best use of server resources for mission-critical applications. For example, does InnoDB or MyISAM work best for the database storage engine?


Specifically, Linux system monitors look at:

Memory usage

CPU usage

Storage usage, including disk space and Input/Output Operations per Second (IOPS)

Network usage

A server’s system load – a term we hear often in the discussions – usually encompasses the usage of memory, CPU, and storage.

Dozens of Linux server system monitoring commands are built into the operating system. They include very simple commands like top, which by default displays Linux processes in CPU activity order. These tools also can be highly complex, such as sar, which collects, reports, and saves a wide variety of system activity information.

There are, of course, many higher-level system monitoring programs for all distributions that permit you to monitor any Linux server. These include Glance, a Python-based cross-platform system monitoring tool; htop, another cross-platform system monitor, which uses ncurses for its display; and Netdata, a distributed server system monitoring program. However, as useful as these can be, they all rely on lower-level programs.

Four important Linux system monitoring tools are worthwhile to examine in more detail.

Sar: System Activity Reporter (sar) is part of the Sysstat system resource utilities package. Sar is a do-it-all monitoring tool. It measures CPU activity; memory/paging; interrupts; device load; network; process and thread allocation; and swap space utilization. Sar can be used interactively, but its real value is that it keeps data logs over a long period of time, which you can use to troubleshoot recurring problems and produce reports. To learn more, read our How to Use the System Activity Reporter (sar) guide.

Vmstat: This virtual memory statistics reporter is a built-in Linux command-line tool. In addition to reporting in detail on virtual memory usage, vmstat also gathers information on memory usage, memory paging, processes, I/O, CPU, and storage scheduling. Unlike sar, vmstat starts on boot. It’s used to report on cumulative activity since the last reboot. Our Use vmstat to Monitor System Performance guide includes more information about getting started with this monitoring tool.

Monitorix: Monitorix is a free, open-source tool that monitors multiple Linux services and system resources. Monitorix, from version 3.0 on, comes with its own web server. This makes it useful for remote Linux system monitoring. Originally designed for the Red Hat Enterprise Linux (RHEL) operating system family, Monitorix now works on all major Linux server distributions. Read our How to use Monitorix for System Monitoring guide to learn more.

Nethogs: This free and open-source program extends the net top tool that tracks bandwidth by process. For example, you might discern that the amount of outbound traffic has increased on your Linux server, but Nethogs helps you identify which process is generating the usage spikes. Other network monitoring utilities only break down the traffic by protocol or subnet. Read our Get Started Using Nethogs for Network Usage Monitoring guide to learn more about this tool.

