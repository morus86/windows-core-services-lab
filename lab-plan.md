\# Lab plan (Windows Core Services)



\## Host

\- Hyper-V on Windows 11 Pro

\- Default paths:

&nbsp; - VMs: D:\\Maszyny\\olimp\\VMs

&nbsp; - VHDX: D:\\Maszyny\\olimp\\VHDX



\## Domain

\- FQDN: olimp.com

\- NetBIOS: OLIMP

\- Primary DC: ZEUS (DC01)



\## Network

\- vSwitch: vSwitch-External (External)

\- Subnet (planned): 192.168.10.0/24

\- DC01 IP (planned): 192.168.10.10

\- DNS: DC01



\## VMs (planned)

1\) ZEUS (Windows Server) - AD DS, DNS (later DHCP)

2\) CL01 (Windows client) - domain joined

