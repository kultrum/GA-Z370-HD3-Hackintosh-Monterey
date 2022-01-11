# GA-Z370-HD3-Hackintosh-Monterey
Monterey hackintosh in: Mobo Gigabyte Z370-HD3 Intel i5 8400 iGPU

This is not a guide to make a Hackintosh, but my experience making one with opencore

I followed this guide: https://www.olarila.com/topic/20908-guide-easy-fast-and-perfect-hackintosh-vanilla-step-by-step-clover-and-opencore-bootloader/

From the genius of MaLd0n

I made the USB for install MacOS Montery following the guide, previously downloading the macos image frome Olarila

Some important tip: it is necessary to add boot argument in opencore config file -igfxvesa for the install works

After installation and put the correct EFI folder, it is necessary to remap USB ports (guide is in Olarila web)

I leave the EFI repository that works with my PC (dsdt.aml made by MaLd0n!)[EFI.zip](https://github.com/kultrum/GA-Z370-HD3-Hackintosh-Monterey/files/7847201/EFI.zip)
... specs:

Motherboard Gigabyte Z370-HD3
Intel i5 8400
iGPU (Intel Graphics UHD 630)
Nvme SSD WD 250 GB
WIFI TP-Link TL-WDN4800 N900 (PCI)

Fill in PlatformInfo in config.plist to iMac19,2

