# My homelab
Here i will describe how my homelab looks and what type of hardware i'm using.

## Main workstation
My main workstation that i have built by my selfe.

* Processor: AMD Ryzen 3700x
* MB: Asus x370 prime pro
* Memory: 4x8gb DDR4 3000mhz Corsair
* GPU: RTX 2070
* OS: Dualbooting Manjaro linux and Windows 10

This PC is used for VMs, programming, gaming and everyday tasks. Really like the possibility that i can run several VMs and not run in to performence issues. 

## Network

* Edgerouter lite3 
* Ubiquiti Networks UniFi Switch 8-150W
* Ubiquiti Networks UniFi AP AC Lite
* x2 D-Link DGS-105

This is the base of my network at home. I have l2tp ipseec running on the Edgerouter, this way i can remote in to my local network.

## Lab servers

* HPE ProLiant DL380 G6
* x4 Lenovo thinkpad t450
* Asustor as1002t v2 NAS

On my HPE i have Proxmox installed as a host OS. Under that i have a lot of VMs and containers running, This include Plex, Unifi controller, PiHole, transmission, webserver, Nextcloud.

I use my laptops as testing nodes with proxmox installed.

