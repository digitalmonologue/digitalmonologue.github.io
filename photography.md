---
layout: page
title: Photography
permalink: /photography/
---

<style>
  /* Global Page Override */
  html, body, .site-credits {
    background-color: #fdf012 !important; 
    color: #111 !important;
    margin: 0;
    padding: 0;
  }

  .photography-container {
    max-width: 800px;
    margin: 0 auto;
    padding: 40px 20px;
    font-family: "EB Garamond", serif;
    text-align: center;
  }

  /* 4. Polaroid Border Design */
  .polaroid-hero {
    background: white;
    padding: 20px 20px 60px 20px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    display: inline-block;
    transform: rotate(-1deg);
    margin-bottom: 50px;
    border: 1px solid #ddd;
  }

  .polaroid-content {
    background: #eee; /* Light gray "empty" photo area */
    width: 300px;
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    border: 1px solid #ccc;
  }

  .polaroid-content h1 {
    margin: 0;
    font-size: 1.8rem;
    letter-spacing: 2px;
    text-transform: uppercase;
  }

  /* 3. Skeleton Loading Grid */
  .skeleton-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 40px;
    opacity: 0.6;
  }

  .skeleton-item {
    background: #e0e0e0;
    aspect-ratio: 1 / 1;
    border: 1px solid #ccc;
    position: relative;
    overflow: hidden;
  }

  /* Shimmer Animation */
  .skeleton-item::after {
    content: "";
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
