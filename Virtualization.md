# Virtualization

What is Virtualization ? <br />
Process of creating a virtual version of something, including virtual computer hardware platforms, storage devices and network resources. <br />

Why virtualization ? <br />
 Cost reduction - as virtualization reduces need of physical machine <br />
 Increased uptime – virtual servers helps with business continuity <br />
 Easy backup – you can create backup of VM within minutes <br />
 Testing environment – virtual servers offer programmers isolated, independent system in which they can test new applications or operating system. <br />
 No need of manpower for manage hardware <br />


What is hypervisor ? <br />

It is thin layer of software that runs your virtual machine



Types :
Type 1 hypervisor/ HW virtualization:
It is also called  as “bare metal
   hypervisor”
 It run directly on physical hardware
 It gives better performance than 
   Type-2 hypervisor
 e.g. VMware ESXi,  Microsoft Hyper-V, Citrix XenServer and Linux KVM

Type 2 hypervisor/ SW virtualization
 It is also called as “Hosted hypervisor”
 It is installed on top of Host OS
 Guest OS access HW through Host OS
 Host OS stability decides the stability of Guest OS
 e.g. VMware workstation, Virtual box and MS-VPC

Some interesting facts !
 AWS 1st generation SW is based on XenServer
 AWS 2nd generation SW is based on Nitro virtualization  developed by them own
 Google cloud uses KVM in backend.
 Snapshot includes :
  save’s state of all VM’s disk
  Content of VM memory
  All VM setting
  
 VM files:
 
 
![image](https://user-images.githubusercontent.com/29200717/117650767-be4bda00-b1ae-11eb-98dc-0b02695d851a.png)



# Storage Protocols
The most efficient protocol for a particular data center depends on factors such as the size of the data center, types of servers used, and available budget. For example, some protocols ensure faster data transmission speeds but cost more to implement.

| Protocol                                     |                   Application                       |
| -------------------------------------------- |:---------------------------------------------------:|
| SCSI (Small Computer System Interface)       | Medium- sized blade servers, Enterprise servers, DAS|
| SATA (Serial Advanced Technology Attachment) | Small-sized tower server, DAS                       |
| eSATA (external SATA)                        | Small-sized tower server, DAS                       |
| SAS (Serial Attached SCSI)                   | Medium-sized blade servers, Enterprise servers, DAS |
| FC (Fiber Channel) (single-mode) (SMF)       |	Enterprise servers, SAN                            |
| FC (Fiber Channel) (multi-mode) (MMF)	       | Enterprise servers, SAN                             |
| FCoE (Fiber Channel over Ethernet)	         | Enterprise servers, SAN                             |
| iSCSI (internet Small Computer System Interface)| Enterprise servers, NAS                          |


