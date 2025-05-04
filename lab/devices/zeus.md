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

<div class="gallery">
    <div class="gallery-item">
        <a href="/assets/images/zeussideview.png" target="_blank">
            <img src="/assets/images/zeussideview.png" alt="Side view of Zeus">
        </a>
    </div>

    <div class="gallery-item">
        <a href="/assets/images/zeusnastopview.png" target="_blank">
            <img src="/assets/images/zeusnastopview.png" alt="Top view of Zeus">
        </a>
    </div>

    <div class="gallery-item">
        <a href="/assets/images/zeuslaidover.jpeg" target="_blank">
            <img src="/assets/images/zeuslaidover.jpeg" alt="Laid over view of Zeus">
        </a>
    </div>
</div>

<style>
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 20px;
    margin: 20px 0;
}

.gallery-item {
    text-align: center;
}

.gallery-item img {
    max-width: 100%;
    height: auto;
    border: 1px solid #ccc;
}

.gallery-item a:hover img {
    filter: brightness(1.1);
    transform: translateY(-1px);
    transition: all 0.15s ease;
}
</style>
