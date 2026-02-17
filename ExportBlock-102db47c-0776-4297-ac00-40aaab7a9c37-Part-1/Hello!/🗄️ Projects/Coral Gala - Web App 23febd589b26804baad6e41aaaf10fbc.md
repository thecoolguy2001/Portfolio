# Coral Gala  -  Web App

Role: Founder / Web Developer / UI/UX Designer
Timeline: June 23, 2025 → October 3, 2025
Tags: App Design, Brand, Human Computer Interaction, Mobile Application, Product Design, UI/UX, Web Design, Website
Tools: API, CSS, Figma, Github, HTML, JS, Xcode
Team: Demonte Walker (Me)
Link: website link → https://www.coralgala.live

![Visualizer (4).png](Coral%20Gala%20-%20Web%20App/Visualizer_(4).png)

# Summary

Coral Gala is a virtual fish tank experience built as a live, browser-based aquarium that users can interact with in real time. Designed with playful animation, atmospheric sounds, and multiplayer persistence, the site blends nostalgia with modern web interactivity—serving as both a digital toy and a social experiment.

# Problem

Despite the popularity of ambient apps and screensavers, most virtual fish tanks are static, single-user, or tied to outdated software. There’s a gap in fun, lightweight web-based experiences that users can visit casually—but return to often. I wanted to create something **alive**, beautiful, and community-driven, where everyone shares the same tank.

<aside>
❓ How can we build a real-time, interactive virtual aquarium that feels alive, reacts to multiple users, and keeps people coming back?

</aside>

# Solution

The solution was to develop **Coral Gala** as a real-time fish tank website where users can add fish, customize them, and watch them swim in a shared environment. Fish movement is animated using JavaScript, and persistent data is stored via Firebase. The site includes gentle background music, customizable fish color, and soon-to-launch features like petting and feeding.

![Visualizer (2).png](Visualizer%20-%20Web%20App/Visualizer_(2)%201.png)

<aside>
💡 Use lightweight canvas/WebGL rendering for smooth, responsive animations on all devices.

</aside>

![Visualizer (3).png](Visualizer%20-%20Web%20App/Visualizer_(3).png)

<aside>
💡 Store fish data in Firebase to ensure all users see the same live tank, regardless of location or session.

</aside>

![Visualizer (4).png](Visualizer%20-%20Web%20App/Visualizer_(4).png)

<aside>
💡 Allow users to customize fish with color, speed, and size—building a personal connection with their virtual creatures.

</aside>

---

# Process

Coral Gala was built in the spirit of creative coding balancing artistic expression with technical challenge. The process followed a design → prototype → test loop, with a focus on playability and aesthetic.

<aside>
👇 Click to jump to section

</aside>

[User Research →](Vosyn%20-%20AI%20Startup%20Website%20c9fa107d5fb44d939c639f8bb4c67e85.md) 

[Sketches →](Vosyn%20-%20AI%20Startup%20Website%20c9fa107d5fb44d939c639f8bb4c67e85.md)

[Wireframes / Prototypes →](Vosyn%20-%20AI%20Startup%20Website%20c9fa107d5fb44d939c639f8bb4c67e85.md)

[Usability Study →](Vosyn%20-%20AI%20Startup%20Website%20c9fa107d5fb44d939c639f8bb4c67e85.md)

### User Research

Research began with looking at existing aquarium apps and screensavers, as well as ambient websites and live cam experiences. I asked users what would make them return to a fish tank and what makes digital “pets” feel alive.

![Screenshot 2025-03-07 at 5.29.44 AM.png](Visualizer%20-%20Web%20App/Screenshot_2025-03-07_at_5.29.44_AM.png)

<aside>
👉 Identified the need for personalization, shared environments, and whimsical charm to make the experience feel less like a toy—and more like a space.

</aside>

### Sketches

Early sketches included wild ideas like fish with personalities, virtual “coral club nights,” and music-reactive visuals. These eventually grounded into a design focused on **soft motion, user input**, and a sense of calm.

![Screenshot 2025-03-07 at 5.29.50 AM.png](Visualizer%20-%20Web%20App/Screenshot_2025-03-07_at_5.29.50_AM.png)

<aside>
👉 Sketched playful fish styles, layered backgrounds, and floating elements to create a stylized but lightweight underwater world.

</aside>

### Wireframes / Prototypes

The first prototype was built in vanilla JavaScript and HTML canvas, animating a few fish sprites in loops. After proving it could run smoothly on web and mobile, I wired in Firebase to handle fish entries and track each user’s additions.

![Screenshot 2025-03-07 at 5.30.02 AM.png](Visualizer%20-%20Web%20App/Screenshot_2025-03-07_at_5.30.02_AM.png)

<aside>
👉 Validated real-time database syncing and live fish creation across multiple users and devices.

</aside>

### Usability Study

I invited friends and creators to test the tank on both desktop and mobile and asked them how it made them feel. Feedback centered around wanting **more personalization**, emotional feedback from the fish, and ways to make the tank more interactive over time.

<aside>
👉

Based on feedback, I added color sliders, fish name saving, and began designing the pet/feed system for future updates.

</aside>

---

# Major Design Iterations

### - Iteration 1.

Initial version featured fish that spawned randomly on load and swam in simple loops. It had no persistent data, and fish vanished on refresh.

### - Iteration 2.

Integrated Firebase so that fish stayed in the tank across all users and sessions. Added custom sliders for speed, size, and color selection.

### - Iteration 3.

Introduced multi-user awareness, better fish physics, and a roadmap for petting, feeding, and seasonal fish drops. Began planning integration with AR and mobile app portals.

---

# Final Design

<aside>
👇 Visit the aquarium!

</aside>

[www.coralgala.live](http://www.coralgala.live)

### Product Successes

Coral Gala received overwhelmingly positive feedback in early access. Users described it as “peaceful,” “charming,” and “weirdly addictive.”. Average session time is over **4 minutes**—a strong sign of engagement for a passive experience. The real-time sharing mechanic, combined with personalization, has helped Coral Gala become both a visual toy and a low-key community space.

### What I Learned

Coral Gala taught me how to blend ambient design with multiplayer systems. I learned the power of shared digital spaces and how to give users just enough control to make them feel connected. From technical decisions like syncing Firebase and optimizing animation loops, to design decisions around color, pacing, and charm—I grew in both my coding and creative direction.

This project reminded me that sometimes, building a space that feels good is more powerful than building something that solves a problem. And that’s a principle I plan to carry forward.