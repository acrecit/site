---
layout: default
---

### Overview

*Device Name:* iPhone

*Role:* [Role]

*Specs:*

>Model: [Model]

>iOS Version: [Version]

>Storage: [Storage]

*Features:*

[Features]

<div class="gallery">
    <div class="gallery-item">
        <a href="/assets/images/iphone/[image1].jpg" target="_blank">
            <img src="/assets/images/iphone/[image1].jpg" alt="[Description]">
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