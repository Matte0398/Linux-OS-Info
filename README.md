# Linux OS Info

Bash utility that collects and displays useful information about a Linux system.

## Collected Information

- Hostname
- Operating system name
- Kernel version
- CPU information
- Memory details
- Disk partitions
- Disk usage
- Network interfaces
- DNS configuration
- External IP address
- Package manager information

## Use Cases
- Linux troubleshooting
- System inventory
- Monitoring support activities

## Usage

``` bash
./GetLinuxOS.sh
```

## Output

``` bash
./GetLinuxOS.sh

Hostname = localhost.localdomain
Uptime = 1 hour, 37 minutes
Operating system = GNU/Linux
OS full name = Oracle Linux Server - Version: 9.6; Like: fedora
Kernel Name = Linux
Kernel release = 5.15.0-313.189.5.1.el9uek.x86_64
Machine architecture = x86_64
Package manager = RPM version 4.16.1.3
Memory = Total: 3.4G - Free: 681M (Swap total: 2.0G - Swap free: 1.7G) -> Tot: 5.5G - Free: 2.4G
CPU = 3 - Model: AMD Ryzen 7 6800H with Radeon Graphics
Load average =  0.02, 0.10, 0.15
Users connected = oracle
Disk partitions =
  NAME        FSTYPE       SIZE MOUNTPOINT                       LABEL
  sda                       20G                                  
  ├─sda1      vfat         600M /boot/efi                        
  ├─sda2      xfs            1G /boot                            
  └─sda3      LVM2_member 18.4G                                  
    ├─ol-root xfs         16.4G /                                
    └─ol-swap swap           2G [SWAP]                           
  sr0         iso9660     50.7M /run/media/oracle/VBox_GAs_7.2.0 VBox_GAs_7.2.0
Disk utilization =
  /: 8.3G/17G (51%)
  /boot: 561M/960M (59%)
  /boot/efi: 7.2M/599M (2%)
  /run/media/oracle/VBox_GAs_7.2.0: 51M/51M (100%)
DNS server =  10.20.30.1
Internet = connected
External IP address = 185.74.92.148
Network interfaces info =
  lo         IP address: 127.0.0.1
  enp0s3     IP address: 10.20.30.45
