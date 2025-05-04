---
layout: default
---

# Wallpaper Gallery

<div class="gallery">
    <div class="gallery-item">
        <a href="/downloads/wallpapers/arch.png" target="_blank">
            <img src="/downloads/wallpapers/arch.png" alt="Arch Linux Wallpaper">
            <div class="overlay">
                <div class="download-btn">
                    <a href="/downloads/wallpapers/arch.png" download>Download</a>
                </div>
            </div>
        </a>
    </div>

    <div class="gallery-item">
        <a href="/downloads/wallpapers/tokyoBackground.png" target="_blank">
            <img src="/downloads/wallpapers/tokyoBackground.png" alt="Tokyo Background">
            <div class="overlay">
                <div class="download-btn">
                    <a href="/downloads/wallpapers/tokyoBackground.png" download>Download</a>
                </div>
            </div>
        </a>
    </div>

    <div class="gallery-item">
        <a href="/downloads/wallpapers/1733724827744143.jpg" target="_blank">
            <img src="/downloads/wallpapers/1733724827744143.jpg" alt="Wallpaper 3">
            <div class="overlay">
                <div class="download-btn">
                    <a href="/downloads/wallpapers/1733724827744143.jpg" download>Download</a>
                </div>
            </div>
        </a>
    </div>

    <div class="gallery-item">
        <a href="/downloads/wallpapers/1696027779799763.png" target="_blank">
            <img src="/downloads/wallpapers/1696027779799763.png" alt="Wallpaper 4">
            <div class="overlay">
                <div class="download-btn">
                    <a href="/downloads/wallpapers/1696027779799763.png" download>Download</a>
                </div>
            </div>
        </a>
    </div>

    <div class="gallery-item">
        <a href="/downloads/wallpapers/wp5568820.png" target="_blank">
            <img src="/downloads/wallpapers/wp5568820.png" alt="Wallpaper 5">
            <div class="overlay">
                <div class="download-btn">
                    <a href="/downloads/wallpapers/wp5568820.png" download>Download</a>
                </div>
            </div>
        </a>
    </div>

    <div class="gallery-item">
        <a href="/downloads/wallpapers/092.png" target="_blank">
            <img src="/downloads/wallpapers/092.png" alt="Wallpaper 6">
            <div class="overlay">
                <div class="download-btn">
                    <a href="/downloads/wallpapers/092.png" download>Download</a>
                </div>
            </div>
        </a>
    </div>
</div>

<style>
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 10px;
    padding: 10px;
    width: 100%;
}

.gallery-item {
    position: relative;
    overflow: hidden;
    border: 1px solid #000;
    aspect-ratio: 16/9;
    display: flex;
    align-items: center;
    justify-content: center;
}

.gallery-item img {
    width: 100%;
    height: 100%;
    display: block;
    object-fit: contain;
    background: #000;
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

.download-btn a {
    display: block;
    padding: 5px 10px;
    background: #f0f0f0;
    color: #000;
    text-decoration: none;
    text-align: center;
    border: 2px outset #ccc;
    font-family: monospace;
    font-size: 14px;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
    box-shadow: 2px 2px 0px #666;
    transition: all 0.1s ease;
}

.download-btn a:hover {
    background: #e0e0e0;
    border: 2px inset #ccc;
    box-shadow: 1px 1px 0px #666;
    transform: translate(1px, 1px);
}

.download-btn a:active {
    background: #d0d0d0;
    border: 2px inset #999;
    box-shadow: none;
    transform: translate(2px, 2px);
}
</style>