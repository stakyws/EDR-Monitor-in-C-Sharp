Design and development of a program to monitor system performance and operations to enhance security and track activities in a Windows environment.

The program is designed using the XAML markup language and programmed using C#.

This program contains several programming interfaces, and the main interfaces are five.

<p align="center">
  <img src="1.png" alt="Main interface">
</p>

The first interface is the file monitoring interface, where file events are monitored and recorded, such as deletion, modification, creation of new files or folders, or renaming files.

<p align="center">
  <img src="2.png" alt="Main interface">
</p>

The second interface is the device performance monitoring interface, such as monitoring CPU, RAM, GPU, KD, Total Sent Data, Total Receive Data, DISK (Hertz), and generating reports saved in files for each day of monitoring.

<p align="center">
  <img src="3.png" alt="Main interface">
</p>

The third interface is the system process monitoring interface, where a cybersecurity technician can choose the processes they want to monitor.
All processes on the device are displayed in this program, which is a feature distinct from the Task Manager's details list, where not all processes are displayed, while our program shows all processes.
<p align="center">
  <img src="4.png" alt="Main interface">
</p>

<p align="center">
  <img src="5.png" alt="Main interface">
</p>

The fourth interface is the user monitoring interface, which tracks logins and logouts, as well as records of incorrect password entries during system login.
<p align="center">
  <img src="6.png" alt="Main interface">
</p>

The fifth interface is the network performance and operations monitoring interface, where the following is displayed and monitored:
<p align="center">
  <img src="7.png" alt="Main interface">
</p>

Upload and download speed.

Maximum upload and download speed.

Volume of data uploaded and downloaded.

Network interfaces with data transfer and those without.

Volume of data sent and received on each internet interface.

Display of the user's active and private IP.

Display of internet strength and quality.

Scanning and displaying open and closed ports using the internet.

Displaying active connections and some network data using the TCP protocol.

Displaying system processes using the network.

Recording these data events in log files.

Only the basic features of the program have been mentioned, and I am continuing to develop this program, designing and innovating graphical interfaces that are easier and less complex than the current graphical interfaces in the program.

Developing software and performance and adding many features to it.

Technologies Used:
1- .NET Framework / .NET Core.

2- Windows Presentation Foundation (WPF).

3- System.IO.

4- PerformanceCounter.

5- TCP/IP Sockets.

6- Windows Management Instrumentation (WMI).

7- NetworkInterface.

8- EventLog.

9- Task Scheduler.

10- NLog.
