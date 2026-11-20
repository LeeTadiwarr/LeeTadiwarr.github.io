# 🕊️ The Apology App

"I don't study code for the sake of theory; I master technology to build solutions for real-world scenarios."

A full-stack, interactive platform designed to facilitate reconciliation and emotional expression. This project combines front-end animations and a personalized photo gallery to create a meaningful digital space.

### 🌟 Project Overview
The **Apology App** is a custom-built website designed to help users reconnect with loved ones. It features a tabbed interface for sharing a personal story and reminiscing over a photo gallery.

### 🚀 Key Features
* **Immersive Visuals:** CSS-based heart animations and dynamic backgrounds to convey emotion visually.
* **Interactive Tabs:** * **Our Story:** A narrative section to share relationship history.
    * **Memories:** A curated photo gallery to relive happy moments.
* **Dark Theme:** The page uses a dark theme by default.
* **Personalized Soundtrack:** Integrated `<audio>` element for a custom background soundtrack.

### 🛠️ Technical Stack
* **Frontend:** HTML5, CSS3, JavaScript (DOM Manipulation)



### How to Use


Open the website: Open the HTML file in any modern web browser.

Interact with Tabs: Click on the tab buttons to navigate between "Our Story" and "Memories".

Adding Music



### To add custom background music:

Place your MP3 file at `audio/song.mp3` relative to `index.html`. The player has no visible controls.

<audio id="backgroundMusic" loop autoplay>

    <source src="audio/song.mp3" type="audio/mpeg">

    Your browser does not support the audio element.</audio>



### Adding Memories



You can update the images in the "Memories" section by modifying the following part of the HTML code:

<div id="memories" class="tab-content">

    <h2>Memories</h2>

    <div class="memory-gallery">

        <img src="https://www.example.com/photo1.jpg" alt="Memory 1">

        <!-- Add more photos here -->

    </div></div>



Replace the src attributes with links or local paths to your own images.
