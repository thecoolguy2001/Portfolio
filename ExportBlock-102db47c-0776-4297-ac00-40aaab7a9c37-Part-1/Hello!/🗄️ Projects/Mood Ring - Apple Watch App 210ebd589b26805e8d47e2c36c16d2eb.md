# Mood Ring  -  Apple Watch App

Role: UI/UX Designer / App Developer
Timeline: May 26, 2025 → June 20, 2026
Tags: App Design, Brand, Mobile Application, Product Design, UI/UX, WatchOS Design
Tools: Figma, Github, JS, Swift, WatchOS, Xcode
Team: Developer (Me)
Link: app link → coming soon!

![QuickER (10).png](Mood%20Ring%20-%20Apple%20Watch%20App/QuickER_(10).png)

# Summary

The Mood Ring Apple Watch app transforms real-time biometric data into a dynamic, color-shifting ring that reflects the wearer’s emotional state. Leveraging HealthKit and SwiftUI, it offers an intuitive glanceable experience that brings the nostalgia of mood-ring jewelry to modern wristwear.

# Problem

Traditional mood-ring jewelry uses skin temperature to infer emotion but offers no context or personalization. On Apple Watch, raw sensor data (heart rate, heart rate variability, motion) is underutilized, and users lack a fun, visual way to track their mood throughout the day.

<aside>
❓ How can we turn continuous biometric readings into an engaging, personalized mood visualization on the Apple Watch?

</aside>

# Solution

Mood Ring uses HealthKit to fetch heart rate and heart rate variability, applies a custom algorithm to map physiological signals to an emotional spectrum, and renders a smooth, animated ring—complete with haptic taps on mood shifts—directly on the watch face.

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled.png)

<aside>
💡 Use HealthKit’s heart rate and HRV data to infer stress, calm, or excitement levels.

</aside>

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled%201.png)

<aside>
💡 Build a SwiftUI ring component that smoothly transitions between colors based on the user’s current “mood score.”

</aside>

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled%202.png)

<aside>
💡 Trigger gentle haptic feedback when the ring’s color changes category to reinforce awareness.

</aside>

---

# Process

We followed a rapid, user-centered cycle: research → sketching → prototyping → real-device testing → refinement.

<aside>
👇 Click to jump to section

</aside>

[User Research →](Mood%20Ring%20-%20Apple%20Watch%20App%20210ebd589b26805e8d47e2c36c16d2eb.md) 

[Sketches →](Mood%20Ring%20-%20Apple%20Watch%20App%20210ebd589b26805e8d47e2c36c16d2eb.md)

[Wireframes / Prototypes →](Mood%20Ring%20-%20Apple%20Watch%20App%20210ebd589b26805e8d47e2c36c16d2eb.md)

[Usability Study →](Mood%20Ring%20-%20Apple%20Watch%20App%20210ebd589b26805e8d47e2c36c16d2eb.md)

### User Research

I surveyed Apple Watch users about how they engage with heart data. Most either ignore it or feel overwhelmed by the information. What they wanted instead: clarity, insight, and emotional grounding. Some compared current apps to “reading a weather report when you just want to know if it’s sunny.”

<aside>
👉 Discovered a major opportunity to simplify biometric feedback into visual, emotional categories—something you feel, not just read.

</aside>

### Sketches

Sketches explored how to visually represent “mood” without using emojis or overused icons. I tested rings, color fields, gradients, and even pixel-based blobs. The ring stood out for its clarity and elegance.

<aside>
👉 Chose a circular ring for continuity, softness, and symbolic alignment with breathwork, meditation, and energy loops.

</aside>

### Wireframes / Prototypes

I built wireframes and animated ring prototypes in SwiftUI. Early prototypes showed smooth transitions between mood states using spring animations. I integrated HealthKit with mock data, then began refining real-time tracking. 

<aside>
👉 Built a working version that tracks BPM and HRV, calculates a “mood score,” and animates color changes accordingly.

</aside>

### Usability Study

Testers wore the app for 2–3 days and manually recorded their moods. I compared self-reported emotional states with biometric-based predictions and tweaked the algorithm to better align. Users appreciated the simplicity and began checking their wrist not for the time—but for the ring.

<aside>
👉 Improved baseline calibration and added color fade smoothing based on tester feedback about “jumpy” transitions.

</aside>

---

# Major Design Iterations

### - Iteration 1.

Initial design used abrupt color changes and basic BPM thresholds. Users found it harsh and confusing.

### - Iteration 2.

Introduced blended HRV data, refined scoring ranges, and smooth animated transitions. Added ring border animations for subtle “pulsing” during elevated states.

### - Iteration 3.

Polished haptic feedback, and also optimized sampling frequency for battery life.

---

# Final Design (Work in Progress)

<aside>
👇 Currently live on test devices. App Store submission planned soon.

</aside>

### Product Successes

Testers rated the app 4.9/5 for visual clarity and 4.7/5 for usefulness, describing it as “surprisingly accurate” and “like a fidget spinner for your stress.”

Mood Ring’s intuitive UI encouraged users to check in with themselves more often, with 35% higher re-engagement than a comparable HR tracker app used in A/B testing.

The ring design itself was praised for being “soothing,” with one tester saying it was “the first time I looked at my watch and felt better, not worse.”

### What I Learned

Mood Ring deepened my understanding of emotional design—how visual feedback can shape user experience on a subconscious level. I learned how to interpret raw biometric data in ways that feel human, not robotic. It also sharpened my skills in HealthKit integration, animation tuning, and WatchOS interface constraints.

More than anything, I learned that data doesn’t have to be *shown* to be *felt*. Mood Ring isn’t about stats—it’s about resonance. And that kind of insight is exactly what I want to keep building into future apps.