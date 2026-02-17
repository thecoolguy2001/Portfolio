# Safe Browsing+  -  Web App

Role: UI/UX Designer / Web Developer Intern
Timeline: February 12, 2023 → May 20, 2023
Tags: Brand, Product Design, UI/UX, Web Design, Website
Tools: API, CSS, Chrome, Figma, Github, HTML, JS, Web Extenstion
Team: Developer (Me)

![QuickER (2).png](Safe%20Browsing+%20-%20Web%20App/QuickER_(2).png)

# Summary

Safe Browsing+ is a Chrome extension designed to enhance online safety by selectively blurring harmful or offensive words on web pages. Combining an intuitive UI with powerful background scripting, it preserves full website functionality while giving users control over their browsing experience.

# Problem

Users frequently encounter distressing or inappropriate language online, but blanket content blockers can break site layouts or hide too much information. The challenge was to create a fine-grained filter that removes only the problematic text without disrupting page design or functionality.

<aside>
❓ How can we provide real-time, context-aware word filtering in Chrome that keeps sites fully operational and the user experience seamless?

</aside>

# Solution

Safe Browsing+ injects a lightweight content script that scans page text, matches against a customizable word list, and applies CSS blur effects to just the offending terms. A floating toolbar lets users toggle filtering on or off, edit their block list, and adjust blur intensity—all without reloading the page.

![Empowering Secure Web Experience.png](Safe%20Browsing+%20-%20Web%20App/Empowering_Secure_Web_Experience.png)

<aside>
💡 Use a content script to traverse the DOM, identify target words, and wrap them in blur-enabled

</aside>

![Empowering Secure Web Experience (1).png](Safe%20Browsing+%20-%20Web%20App/Empowering_Secure_Web_Experience_(1).png)

<aside>
💡 Leverage the Chrome Runtime API for bi-directional messaging between the popup UI and background script, ensuring instant updates.

</aside>

![Empowering Secure Web Experience (2).png](Safe%20Browsing+%20-%20Web%20App/Empowering_Secure_Web_Experience_(2).png)

<aside>
💡 Implement a responsive, minimal UI with HTML, CSS, and JavaScript that gracefully overlays on any website without affecting layout.

</aside>

---

# Process

The project followed a lean, user-centered cycle: research → prototyping → testing → iteration.

<aside>
👇 Click to jump to section

</aside>

[User Research →](Safe%20Browsing+%20-%20Web%20App%20210ebd589b2680ff8ab4dc244fbfa3b9.md) 

[Sketches →](Safe%20Browsing+%20-%20Web%20App%20210ebd589b2680ff8ab4dc244fbfa3b9.md)

[Wireframes / Prototypes →](Safe%20Browsing+%20-%20Web%20App%20210ebd589b2680ff8ab4dc244fbfa3b9.md)

[Usability Study →](Safe%20Browsing+%20-%20Web%20App%20210ebd589b2680ff8ab4dc244fbfa3b9.md)

### User Research

User research involved looking to current 

<aside>
👉

</aside>

### Sketches

Preliminary sketches in

<aside>
👉

</aside>

### Wireframes / Prototypes

Wireframes .

<aside>
👉

</aside>

### Usability Study

Usability testing involved

<aside>
👉

</aside>

---

# Major Design Iterations

### - Iteration 1.

![Empowering Secure Web Experience (3).png](Safe%20Browsing+%20-%20Web%20App/Empowering_Secure_Web_Experience_(3).png)

### - Iteration 2.

![Empowering Secure Web Experience (4).png](Safe%20Browsing+%20-%20Web%20App/Empowering_Secure_Web_Experience_(4).png)

### - Iteration 3.

![Empowering Secure Web Experience (5).png](Safe%20Browsing+%20-%20Web%20App/Empowering_Secure_Web_Experience_(5).png)

---

# Final Design

<aside>
👇 Click to play with demo video

</aside>

[Safe Broswing  Demo.mp4](Safe%20Browsing+%20-%20Web%20App/Safe_Broswing__Demo.mp4)

### Product Successes

### What I Learned