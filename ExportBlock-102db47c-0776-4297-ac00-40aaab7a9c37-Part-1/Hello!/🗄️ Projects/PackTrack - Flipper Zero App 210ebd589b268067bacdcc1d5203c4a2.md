# PackTrack  -  Flipper Zero App

Role: UI/UX Designer / App Developer
Timeline: June 2, 2025 → November 28, 2025
Tags: App Design, Product Design, UI/UX
Tools: API, CSS, Figma, Flipper Zero, Github, HTML, JS
Team: Developer (Me)
Link: github link → coming soon!

![Old York Times (5).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(5).png)

# Summary

The development of the Flipper Zero Package Tracker app aims to bring seamless parcel tracking to the Flipper Zero device, allowing users to check package statuses and receive updates directly with no smartphone needed!

# Problem

Traditional package tracking requires a smartphone or computer to constantly go online to check their provider site for delivery information, creating friction when users just want a quick status glance. While this can be solved on the Flipper Zero, the limited screen space, lack of native browser support, and intermittent connectivity make real-time tracking a challenge. 

<aside>
❓ How can we deliver accurate, scheduled package status updates on an embedded device with minimal UI and connectivity constraints?

</aside>

# Solution

The solution was to create a application for the Flipper Zero that connects to your shipping provider to display delivery information at a push of a button! The app leverages the Flipper Zero Wi-Fi board to fetch tracking information from carrier APIs, presents statuses in a clean menu-driven interface, and uses the device’s RTC for scheduled checks with visual and haptic alerts. The app UX ensures that the screen space is actually perfectly to display the information that users want to be updated on when dealing with a shipment.

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3).png)

<aside>
💡 Implement a lightweight HTTP client and JSON parser on the Wi-Fi board to retrieve and process package status data.

</aside>

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3)%201.png)

<aside>
💡 Design a simple, scrollable list UI optimized for the Flipper Zero’s directional pad, supporting entry and review of multiple tracking numbers.

</aside>

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3)%202.png)

<aside>
💡 Use real-time clock scheduling with LED backlight color changes and vibration alerts to notify users when package statuses change.

</aside>

---

# Process

The development process uses a agile, hardware-focused workflow emphasized rapid prototyping and real-device testing at every step.

<aside>
👇 Click to jump to section

</aside>

[User Research →](PackTrack%20-%20Flipper%20Zero%20App%20210ebd589b268067bacdcc1d5203c4a2.md) 

[Sketches →](PackTrack%20-%20Flipper%20Zero%20App%20210ebd589b268067bacdcc1d5203c4a2.md)

[Wireframes / Prototypes →](PackTrack%20-%20Flipper%20Zero%20App%20210ebd589b268067bacdcc1d5203c4a2.md)

[Usability Study →](PackTrack%20-%20Flipper%20Zero%20App%20210ebd589b268067bacdcc1d5203c4a2.md)

### User Research

The user research was done by researching on  frequent online shoppers and logistics professionals to pinpoint frustrations with existing mobile tracking solutions and prioritize features like offline caching and automated checks. Also looking to other competitors and their offerings for the services to ensure our product has optimal design for users.

<aside>
👉  Identified a desire for real-time notifications, clear carrier status, and multi package viewing without draining the Flipper’s battery.

</aside>

### Sketches

Currently sketches involve early mockups that explored different list layouts, entry flows, and notification indicators, ensuring clarity within the Flipper Zero’s monochrome LCD constraints.

<aside>
👉 Sketched UI flows for adding, viewing, and scheduling checks for up to five tracking numbers.

</aside>

### Wireframes / Prototypes

Using QFlipper and C++ firmware, I am currently building working prototype that fetches dummy JSON data, parsed it, and rendered status updates on the device screen.

<aside>
👉 Developed and validated full API request flow, JSON parsing, and real-time updates with user input for manual refresh.

</aside>

### Usability Study

Currently development has not gotten to the point for usability testing.

<aside>
👉 Testing will involve users entering their information to test the connection with package.

</aside>

---

# Major Design Iterations

### - Iteration 1.

Laid down the core menu system for entering and viewing tracking numbers, using placeholder data to validate navigation and display.

### - Iteration 2.

Connected to the Flipper Wi-Fi board and fetched real data from a custom server. UI was fully functional but still bulky.

### - Iteration 3.

Refined status display to use minimalist icons and compressed tracking information. Reduced request size for faster refreshes. Added haptic buzz and optional backlight pulse on delivery updates.

---

# Final Design (Work in Progress)

<aside>
👇 This project is still very early in development, check back for future updates!

</aside>

### Current Product Successes

Early prototypes show strong promise with successful Wi-Fi integrations and mock data rendering smoothly on-device. Internal testers and community peers have expressed excitement for a minimal, real-time tracker that doesn’t require pulling out a phone. The design direction and backend setup have positioned PackTrack to be one of the first functional logistics utilities on Flipper Zero.

### What I Am Learning

PackTrack is teaching me how to balance embedded constraints with real-world utility. I’m refining skills in low-overhead HTTP communication, device-level UI design, and memory-efficient JSON parsing. This project is also pushing me to think about offline-first design, data caching, and building software that feels cohesive with Flipper’s native OS.

As I continue development, I’m focused on keeping the app simple, fast, and functional, while exploring the broader potential of utility tools in unconventional platforms like Flipper Zero.