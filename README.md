# NXP FTP Server Example
Common to Any MCU, Easy to Add-on. Internet Offload co-Processor, HW TCP/IP chip, 
best fits for low-end Non-OS devices connecting to Ethernet for the Internet of Things. These will be updated continuously.

<!-- W5500 EVB pic -->
<p align="center">
  <img width="50%" src="http://wizwiki.net/wiki/lib/exe/fetch.php?media=products:w5500:w5500_evb:w5500-evb_side.png" />
</p>

## How to use a data flash on FatFs
- You must have the initialization process of data flash at least once.
- When SW1 is pressed, the data flash is initialized by FatFs. And reset a target.
- You must copy the web page to a data flash by FTP client tool.([ALFTP](http://www.altools.com/ALTools/ALFTP.aspx))
- Refer to W5500EVB+FatFs+FTPServer Project Tutorial. http://youtu.be/-4OCb7YWzlI
- Refer to WIZ550web+WindowsFTP Tutorial. http://youtu.be/kelGSGj3kOQ
- Refer to WIZ550web+LinuxFTP Tutorial. http://youtu.be/6qsPZA5QKEI

## Related Project GitHub Repositories
- [W5500-EVB Main](https://github.com/Wiznet/W5500_EVB)
- [Loopback Test](https://github.com/Wiznet/Loopback_LPC11E36_LPCXpresso): Loopback test example project (TCP server / TCP client / UDP)
- [HTTP Server](https://github.com/Wiznet/HTTPServer_LPC11E36_LPCXpresso): Web server example project
- [SNMPv1 Agent](https://github.com/Wiznet/SNMP_LPC11E36_LPCXpresso): SNMPv1 agent example project (Get/Set/Trap)
- [TFTP Client](https://github.com/Wiznet/TFTP_LPC11E36_LPCXpresso): TFTP example project

## How to add a submodule of ioLibrary in project
- $ git submodule add git@github.com:Wiznet/ioLibrary_Driver.git project_src/ioLibrary
- $ git commit -m "description"
- $ git push

## How to clone a submodule of ioLibrary
- $ git clone git@github.com:Wiznet/FTP_LPC11E36_LPCXpresso.git
- $ git submodule init
- $ git submodule update

## How to add an ioLibrary on project
  - Refer to https://www.youtube.com/watch?v=mt815RBGdsA
 
## Revision History
Last release : Jan. 2015
