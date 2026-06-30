---
layout: page
permalink: /startup/
title: 
description: 
nav: false
nav_order: 21
---


<style>
  /* Full-page background image, extending from below the navbar to the footer */
  .full-page-image {
    position: absolute;
    top: 0; /* Adjust based on navbar height */
    left: 0;
    width: 100vw;
    height: 100%; /* Ensures it doesn't overlap the footer */
    background: url('/assets/img/cs.jpg') no-repeat center center fixed;
    background-size: cover;
    z-index: -1;
  }

  /* Transparent overlay to improve text readability */
  .full-page-image::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.35); /* Adjust transparency */
  }

  /* Flexbox container to center content while maintaining equal spacing */
  .launch-container {
    display: flex;
    flex-direction: column;
    justify-content: center; /* Center text vertically */
    align-items: center;
    min-height: 100vh; /* Ensures it fills entire viewport */
    text-align: center;
    margin: 0; /* Remove any margin */
    padding: 0; /* Remove any padding */
  }

  /* Ensure footer starts immediately after the image */
  main {
    display: flex;
    flex-direction: column;
    min-height: 100vh; /* Make sure it fills the entire viewport */
  }

  /* Push footer up so it starts right after content */
  .footer {
    margin-top: auto !important; /* Removes any extra space above footer */
  }  

  /* Force white text in both light and dark mode */
  .launch-container h1, 
  .launch-container p {
    color: white !important;
  }
</style>

<!-- Background Image -->
<div class="full-page-image"></div>

<!-- Main Content -->
<main>
    <div class="launch-container">
        <h1>🚀 Launching Soon</h1>
        <p>Exciting updates are on the way. Stay tuned!</p>
    </div>
</main>