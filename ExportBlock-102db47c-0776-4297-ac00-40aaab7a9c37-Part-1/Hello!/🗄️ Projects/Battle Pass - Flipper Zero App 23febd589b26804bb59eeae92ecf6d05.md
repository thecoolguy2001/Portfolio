# Battle Pass  -  Flipper Zero App

Role: UI/UX Designer / App Developer
Timeline: June 2, 2025 → November 28, 2025
Tags: App Design, Product Design, UI/UX
Tools: API, CSS, Figma, Flipper Zero, Github, HTML, JS
Team: Developer (Me)
Link: github link → coming soon!

![Old York Times (10).png](Battle%20Pass%20-%20Flipper%20Zero%20App/Old_York_Times_(10).png)

# Summary

Battle Pass is a Flipper Zero app that turns passive encounters into live, stats-based battles—bringing a nostalgic, Nintendo-inspired twist to real-world interactions. Designed for Wi-Fi devboard scanning, the app detects nearby Flipper devices running the same app, initiates a randomized battle based on pre-loaded player stats, and displays the outcome on-screen in seconds.

# Problem

The Flipper Zero community thrives on interaction and creativity—but most peer-to-peer activity requires active input or hacking modules. There’s no playful, automatic way for Flipper owners to recognize and “battle” each other in the wild. Inspired by the Nintendo StreetPass concept, I wanted to create a passive handshake mechanic that triggers when two devices get close—adding fun and surprise to Flipper meetups.

<aside>
❓ How can we create a spontaneous, stat-driven battle experience between Flipper users using only local Wi-Fi detection and minimal device interaction?

</aside>

# Solution

Battle Pass turns every Wi-Fi scan into a chance for a quick-flash Flipper duel. Each user sets a nickname and hidden stats (strength, speed, defense), which are broadcast via the Wi-Fi devboard. When another Flipper detects it, the app compares stats, simulates a short battle, and shows the winner on both devices. It’s quick, passive, and fun—built for casual interaction on the go.

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3).png)

<aside>
💡 Leverage the Flipper’s Wi-Fi board to scan for known SSID or broadcast signatures from other StreetPass players.

</aside>

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3)%201.png)

<aside>
💡 Assign randomized or user-created stats to each player and create a local match engine to determine winner using weighted comparisons.

</aside>

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3)%202.png)

<aside>
💡

Display outcomes using animated text sequences and optional buzzer tones to announce wins, losses, and critical hits.

</aside>

---

# Process

Battle Pass was built from the intersection of **wireless experimentation** and **nostalgic game mechanics**. The design process focused on minimal setup, fast interactions, and scalable battle logic.

<aside>
👇 Click to jump to section

</aside>

[User Research →](Battle%20Pass%20-%20Flipper%20Zero%20App%2023febd589b26804bb59eeae92ecf6d05.md) 

[Sketches →](Battle%20Pass%20-%20Flipper%20Zero%20App%2023febd589b26804bb59eeae92ecf6d05.md)

[Wireframes / Prototypes →](Battle%20Pass%20-%20Flipper%20Zero%20App%2023febd589b26804bb59eeae92ecf6d05.md)

[Usability Study →](Battle%20Pass%20-%20Flipper%20Zero%20App%2023febd589b26804bb59eeae92ecf6d05.md)

### User Research

Research was based on classic StreetPass behavior and modern Flipper usage. I polled Flipper owners, many wanted **social, passive apps** that could create moments of surprise and connection without heavy interaction.

<aside>
👉  Discovered strong interest in "Flipper encounters" that happen in the background, especially ones tied to usernames, avatars, and player stats.

</aside>

### Sketches

I sketched battle screens, stat menus, and imagined RPG-style results in text form. 

<aside>
👉 Designed battle result sequences that feel like retro turn-based combat—text-based, dramatic, and over in seconds.

</aside>

### Wireframes / Prototypes

Early prototypes used dummy devices and mock stat sheets to simulate matchups. I implemented the Wi-Fi board scan trigger and tested broadcast ranges to ensure that passive detection could happen reliably without draining the battery.

<aside>
👉 Created a stat engine that weighs attributes in simulated combat rounds, factoring in randomness for surprise victories.

</aside>

### Usability Study

Early testers loved seeing their nickname and stat sheet used in battle outcomes. Feedback focused on wanting more dramatic win/lose effects and faster feedback after a scan.

<aside>
👉 Added buzzer tones, flashing icons, and a “battle found” screen when nearby opponents are detected.

</aside>

---

# Major Design Iterations

### - Iteration 1.

Basic device detection and mock battles with hardcoded stats. No feedback on scan success or encounter.

### - Iteration 2.

Introduced customizable nickname and stat profiles. Added Wi-Fi scan triggers, battle logic, and randomized win messaging.

### - Iteration 3.

Currently building real-time scanning detection, result animations, and an optional battle log. Planning multiplayer leaderboard and rare stat unlocks for future updates.

---

# Final Design (Work in Progress)

<aside>
👇 Internal prototype working. External release expected after full Wi-Fi detection and stat balancing is complete.

</aside>

### Current Product Successes

Even in early builds, StreetPass Battle has generated buzz among testers for its nostalgic feel and **low-friction fun**. It’s an app that surprises users when they least expect it—making Flipper meetups and conventions feel more connected. One tester said it “makes walking around with your Flipper feel like carrying a Tamagotchi warrior in your pocket.”

### What I Am Learning

This project is teaching me how to turn **background wireless scanning into interactive storytelling**. I’m learning about peer device detection, collision logic, and how to create *meaningful feedback loops* with minimal UI and no user input.

More than anything, I’m learning how to bring **fun and identity** into a tool usually used for hacking making Flipper Zero feel more like a digital companion.