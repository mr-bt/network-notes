# TCP/IP

## Tools

### tcpdump
> dump traffic on a network.

man: http://www.tcpdump.org/tcpdump_man.html

### tcpflow
The tcpflow command makes it much easier to debug high-level protocols. For example, if you're debugging an HTTP client, you can run the following command.

### tcptrace
> tcptrace is a tool written by Shawn Ostermann at Ohio University, for analysis of TCP dump files. It can take as input the files produced by several popular packet-capture programs, including tcpdump, snoop, etherpeek, HP Net Metrix, and WinDump. tcptrace can produce several different types of output containing information on each connection seen, such as elapsed time, bytes and segments sent and received, retransmissions, round trip times, window advertisements, throughput, and more. It can also produce a number of graphs for further analysis.

src: [http://tcptrace.org/](http://tcptrace.org/)

### tcpdive
A TCP performance profiling tool.

:information_source: Good documentation on Loss and Retransmission and Congestion Control.

src: [https://github.com/fastos/tcpdive](https://github.com/fastos/tcpdive)

### xplot
> The program xplot was written in the late 1980s to support the analysis of TCP packet traces. 

src: http://www.xplot.org/

## Libraries
### Go
* [gopacket](https://github.com/google/gopacket): Provides packet processing capabilities for Go
* [gopcap](https://github.com/akrennmair/gopcap): A simple wrapper around libpcap for the Go programming language

## Articles/docs/presentations
* [Linux TCP Tuning](http://www.linux-admins.net/2010/09/linux-tcp-tuning.html)
* [Using TCPDump, TCPTrace, & XPlot to Debug Network Problems](./assets/20131016-TCPDumpTracePlot)
* [Tuning the Linux Kernel and TCP Parameters with Sysctl
](http://www.queryadmin.com/1654/tuning-linux-kernel-tcp-parameters-sysctl/)
