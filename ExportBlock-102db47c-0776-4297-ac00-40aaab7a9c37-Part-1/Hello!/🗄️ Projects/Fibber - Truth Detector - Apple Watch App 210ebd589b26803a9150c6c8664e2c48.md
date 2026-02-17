# Fibber - Truth Detector  -  Apple Watch App

Role: UI/UX Designer / App Developer
Timeline: May 26, 2025 → June 20, 2026
Tags: App Design, Brand, Mobile Application, Product Design, UI/UX, WatchOS Design
Tools: Figma, Github, JS, Swift, WatchOS, Xcode
Team: Developer (Me)
Link: app link → coming soon!

![Old York Times (11).png](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Old_York_Times_(11).png)

# Summary

Fibber is an Apple Watch app that simulates a lie-detector by leveraging heart-rate data to infer truthfulness. Using HealthKit and SwiftUI, it guides users through a baseline capture, live monitoring during questioning, and then visualizes results in a clear, engaging interface.

# Problem

Users are intrigued by polygraphs but lack accessible, personal tools to explore biometric feedback. On the Apple Watch, capturing and interpreting heart-rate fluctuations in real time—while delivering immediate, intuitive results—poses both technical and design challenges.

<aside>
❓ How can we turn a consumer wearable into a playful yet credible truth-detector experience using only heart-rate data?

</aside>

# Solution

Truth Detector uses a custom `DetectorSession` to record a stable baseline heart rate, then streams live HealthKit data during a questioning phase. The app computes BPM changes against baseline, maps the delta to “Truth,” “Uncertain,” or “Lie,” and delivers the outcome via color-coded rings, concise text, and haptic taps.

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled.png)

<aside>
💡 Record a 30-second baseline via HealthKit before questioning begins.

</aside>

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled%201.png)

<aside>
💡 Stream live heart-rate samples, calculate the difference from baseline, and apply thresholds to infer truthfulness.

</aside>

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled%202.png)

<aside>
💡 Render results in SwiftUI with a dynamic ring and brief text summary, reinforced by haptic feedback on significant shifts.

</aside>

---

# Process

The app followed a 3-phase development cycle: biometric logic → interaction design → game flow polish. It was tested in both individual and small group settings to simulate real-world party use.

<aside>
👇 Click to jump to section

</aside>

[User Research →](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App%20210ebd589b26803a9150c6c8664e2c48.md) 

[Sketches →](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App%20210ebd589b26803a9150c6c8664e2c48.md)

[Wireframes / Prototypes →](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App%20210ebd589b26803a9150c6c8664e2c48.md)

[Usability Study →](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App%20210ebd589b26803a9150c6c8664e2c48.md)

### User Research

I conducted informal interviews and tested early builds with users at group hangouts. People wanted the app to “feel serious” visually, but not so serious that it lost the fun. They also wanted it to be fast to run, easy to reset, and dramatic in its result.

<aside>
👉 Users wanted biometric feedback to feel “believable,” but the app still needed to be lighthearted and social.

</aside>

### Sketches

Sketches focused on ring-based visuals that felt like a countdown or scan, with results shown in bold, punchy UI. I mapped out three phases: **Baseline**, **Questioning**, and **Verdict**. The ring served as the central animation anchor for all three.

<aside>
👉 Visual design leaned into Apple-style minimalism with hints of arcade-style boldness for the final results.

</aside>

### Wireframes / Prototypes

I built the initial prototype in SwiftUI with fake BPM data to map out result logic and visual flows. Once verified, I integrated real-time HealthKit data to read current BPM and baseline over a 30-second calibration. 

<aside>
👉 Built a custom DetectorSession class to handle baseline tracking, live comparison, and result calculation with thresholds.

</aside>

### Usability Study

I tested Fibber in 2–3 person group settings. Feedback focused on clarity of result, how long to hold during questioning, and whether the app “felt legit” while still being fun.

<aside>
👉 Adjusted timing of result reveal, improved color contrast on verdict rings, and refined the BPM fluctuation thresholds for more satisfying outcomes.

</aside>

---

# Major Design Iterations

### - Iteration 1.

The first version showed raw BPM and live updates but confused users with too much data. No animations or feedback made it feel dry.

### - Iteration 2.

Introduced ring animations, color-coded results (green, yellow, red), and added haptic vibration on verdict. Users began to “trust” the results more.

### - Iteration 3.

Added smoother baseline calibration, improved the text copy (“Lie Detected” instead of just “Lie”), and allowed instant retry to encourage replay.

---

# Final Design (Work in Progress)

<aside>
👇 This project is still very early in development, check back for future usable wireframe!

</aside>

### Product Successes

Early users loved Fibber at group hangouts, with testers calling it “weirdly accurate,” “lowkey terrifying,” and “perfect for parties.”

The app showed a **95% re-engagement rate** during early testing—most users ran it more than 3 times per session.

**Battery drain was minimized** by sampling heart rate at 5-second intervals during live mode, and the crash rate remained at 0% across devices.

### What I Learned

Building Fibber taught me how to walk the line between **serious tech and playful UX**. I learned how to make biometric data feel emotional and how to use minimal design to tell a complete story—from tension to reveal. It deepened my skills in **HealthKit**, **watchOS optimization**, and **microinteraction design**.

Most of all, it showed me how much fun users can have with just one screen, one sensor, and one unexpected result.