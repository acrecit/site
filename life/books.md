---
layout: default
title: Books
---

# My Book Collection

A running catalog of my physical book collection. Click on any book to read my thoughts and reviews. This is by no means complete, I have hundreds and they take a little while to add to the site. 

<div class="book-grid">
    <div class="book-item">
        <a href="/life/books/sun-and-steel.html">
            <img src="/assets/images/books/sun-and-steel.jpg" alt="Sun and Steel">
            <span class="book-title">Sun and Steel</span>
        </a>
    </div>
    <div class="book-item">
        <a href="/life/books/seveneves.html">
            <img src="/assets/images/books/seveneves.jpg" alt="Seveneves">
            <span class="book-title">Seveneves</span>
        </a>
    </div>
    <div class="book-item">
        <a href="/life/books/cryptonomicon.html">
            <img src="/assets/images/books/cryptonomicon.jpg" alt="Cryptonomicon">
            <span class="book-title">Cryptonomicon</span>
        </a>
    </div>
    <div class="book-item">
        <a href="/life/books/anathem.html">
            <img src="/assets/images/books/anathem.jpg" alt="anathem">
            <span class="book-title">Anathem</span>
        </a>
    </div>
</div>

<style>
.book-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 20px;
    padding: 20px;
}

.book-item {
    text-align: center;
}

.book-item img {
    width: 150px;
    height: 225px;
    object-fit: cover;
    border: 1px solid #ccc;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
    border-radius: 0;
}

.book-title {
    display: block;
    margin-top: 10px;
    font-size: 14px;
}
</style> 