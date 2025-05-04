---
layout: default
---

### Overview

*Device Name:* Apollo

*Role:* Main Workstation

*Case:*

Cooler Master ATC-201

*Specs:*

>CPU: AMD Ryzen 7 7700X (16) @ 5.58 GHz

>GPU: NVIDIA GeForce RTX 2080 SUPER [Discrete]

>4x 16gb DDR5 DIMMs, gskill flare


*IP:* 192.168.1.100/24

*Storage:*

>1x 500gb m.2 ssd containing OS and files

>1x 500gb m.2 ssd containing misc items, mostly unused

*OS:*

Arch Linux, XFCE, XFWM


<div class="gallery">
    <div class="gallery-item">
        <a href="/assets/images/apollofrontview.jpeg" target="_blank">
            <img src="/assets/images/apollofrontview.jpeg" alt="Front view of Apollo">
        </a>
    </div>

    <div class="gallery-item">
        <a href="/assets/images/apollothreequarterview.jpeg" target="_blank">
            <img src="/assets/images/apollothreequarterview.jpeg" alt="Three quarter view of Apollo">
        </a>
    </div>

    <div class="gallery-item">
        <a href="/assets/images/2080super.jpeg" target="_blank">
            <img src="/assets/images/2080super.jpeg" alt="RTX 2080 Super GPU">
        </a>
    </div>

    <div class="gallery-item">
        <a href="/assets/images/apollomotherboard.jpeg" target="_blank">
            <img src="/assets/images/apollomotherboard.jpeg" alt="Apollo motherboard">
        </a>
    </div>
</div>

<style>
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 20px;
    padding: 10px;
    width: 100%;
}

.gallery-item {
    position: relative;
    overflow: visible;
    border: 1px solid #000;
    aspect-ratio: 16/9;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 150px;
    margin: 0 auto;
}

.gallery-item img {
    width: 100%;
    height: 100%;
    display: block;
    object-fit: contain;
    background: #000;
    transition: all 0.3s ease;
}

.gallery-item:hover img {
    transform: scale(2.5);
    position: relative;
    z-index: 1000;
}

.overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: #000;
    padding: 5px;
    display: none;
}

.gallery-item:hover .overlay {
    display: block;
}

</style>