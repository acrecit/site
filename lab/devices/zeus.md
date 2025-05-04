---
layout: default
---

### Overview

*Device Name:* Zeus

*Role:* Main Proxmox Host, most VMs and Docker CTs

*Case:*

Rosewill Thor v2

*Specs:*

>CPU: 2 x Intel(R) Xeon(R) E5-2630 v4 (40) @ 3.10 GHz

>GPU: NVIDIA GeForce GT 430 [Discrete]

>8x 16GB DDR4 ECC DIMMs - 128GB total memory


*IP:* 192.168.1.222/24

*Storage:*

>1x WD Blue 2tb 3.5 in HDD for cold VM storage. Mounted in proxmox as cold-vm. /mnt/disk1

>1x WD Blue 2tb 3.5 in HDD, not being used, NTFS, was used as old media drive. /mnt/media

>1x WD Blue 1tb 2.5 in HDD, not being used. /mnt/disk2

>1x Kingston 256gb 2.5 in SATA SSD, used as boot drive for Proxmox + local-lvm for faster VMs.

>1x 256gb m.2 nvme drive, used for docker container storage, mounted at /mnt/nvmedocker

>1x ZFS pool in RAIDZ1, consisting of

>>3x 12tb Seagate Exos 3.5 in HDDs, used as main media and archive storage. Roughly 22tb usable with one parity drive. Mounted at /vault

*OS:*

Proxmox VE

<div class="row">
  <div class="column">
    <img src="/assets/images/zeussideview.png" alt="zeussideview" style="width:100%">
  </div>
  <div class="column">
    <img src="/assets/images/zeusnastopview.png" alt="zeusnastopview" style="width:100%">
  </div>
  <div class="column">
    <img src="/assets/images/zeuslaidover.jpeg" alt="zeuslaidover" style="width:100%">
  </div>
</div>
