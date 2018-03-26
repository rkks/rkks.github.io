
Open Source Contributions
-------------------------
- [Ethernet Channel Bonding Driver enhancements](https://www.kernel.org/doc/Documentation/networking/bonding.txt). Stock driver
consumes >18% bandwidth for keep-alives. The failover time is in order of several seconds. Attempt is to reduce total bandwidth
usage to less than 5% and improve failover time to 3msec. Also, enhance failure detection to identify external network failures.
- [OpenSAF bug-fixes](http://devel.opensaf.org/). During bringup and performance validation of Open-SAF in initial days of release,
had multiple bugs in the areas of tipc, sai, checkpoint and event services. Those issues are identified and fixed.
- [OpenSolaris bug-fixes](http://www.opensolaris.org/). Real-time mirroring FS and NIC-teaming driver is built around Solaris DDI/DKI API.
OpenSolaris announcement brings opportunity to study solaris kernel, harden our code, as well as fix bugs
found in OpenSolaris code. Bugs around DLPI metadata, raw socket mirroring, RX-ring scheduling fixed.

