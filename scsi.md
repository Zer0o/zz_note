### [SCSI Peripheral Device Type](https://en.wikipedia.org/wiki/SCSI_Peripheral_Device_Type)

Value|Device type|Command set|Specification
---|---|---|---
00h|Direct-access block device(e.g. magnetic disk)|SBC Direct Access Commands|SCSI Block Commands(SBC)
01h|Sequential-access device(e.g. magnetic tape)|SSC sequential Access Commands|SCSI Stream Commands(SSC)
02h|Printer device|SSC Printer Commands|SCSI Stream Commands(SSC)
03h|Processor device|SPC Processor Commands|SCSI Primary Commands(SPC)
04h|Write-once device|SBC Write Once Commands|SCSI Block Commands(SBC)
05h|CD/DVD-ROM device|MMC CD-ROM Commands|SCSI Multimedia Commands(MMC)
06h|Scanner device|SGC Scanner Commands|SCSI Graphics Commands(SGC)
07h|Optical memory device(e.g. some optical disks)|SBC Optical Media Commands|SCSI Block Commands(SBC)
08h|Medium changer(e.g. jukeboxes)|SMC Medium Changer Commands|SCSI Medium Changer Commands(SMC)
09h|Communications device|SSC Communications Commands|SCSI Stream Commands(SSC)
0Ah-0Bh|Defined by ASC IT8(Graphics arts pre-press devices)|ASC IT8 Prepress Commands|
0Ch|Storage array controller device(e.g. RAID)|SCC Array Controller Commands|SCSI Controller Commands(SCC)
0Dh|Enclosure services device|SES Enclosure Services Commands|SCSI Enclosure Services(SES)
0Eh|Simplified direct-access device(e.g. magnetic disk)|RBC Reduced Block Commands|Reduced Block Commands(RBC)
0Fh|Optical card reader/writer device|OCRW Optical Card Commands|SCSI Specification for Optical Card Reader/Writer(OCRW)
10h|Reserved for bridging expanders||
11h|Object-based Storage Device|OSD Object-based Storage Commands|Object-based Storage Commands(OSD)
12h|Automation/Drive Interface||
13h|Security manager device||
14h|Host managed zoned block device||Zoned Block Commands(ZBC)
15h||RMC Simlified Multimedia Commands|Reduced Multimedia Commands(RMC)
16h-1Dh|Reserved||
1Eh|Well known logical unit||
1Fh|Unknown or no device type||