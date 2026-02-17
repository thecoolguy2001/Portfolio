# Reflex-o  -  Apple Watch App

Role: UI/UX Designer / App Developer
Timeline: May 26, 2025 → June 20, 2026
Tags: App Design, Brand, Mobile Application, Product Design, UI/UX, WatchOS Design
Tools: Figma, Github, JS, Swift, WatchOS, Xcode
Team: Developer (Me)
Link: app link → coming soon!

![Visualizer.png](Reflex-o%20-%20Apple%20Watch%20App/Visualizer.png)

# Summary

**Reflexo** is a fast-paced Apple Watch game designed to test user reflexes using voice commands, real-time animations, and haptic feedback. Built entirely in **SwiftUI** and **AVFoundation**, it delivers an intuitive, playful experience that fits perfectly on the wrist.

# Problem

Smartwatch games often struggle with limited screen real estate, unreliable audio integration, and lackluster feedback loops. Reflexo needed to provide clear visual and haptic cues, robust audio prompts, and an intuitive game flow—all within the constraints of watchOS.

<aside>
❓ How can we create a seamless reflex-based game on the Apple Watch that combines reliable audio cues, expressive animations, and simple controls?

</aside>

# Solution

Reflexo uses SwiftUI for fluid UI components, AVFoundation for crisp voice prompts, and WatchKit haptics for tactile feedback. Randomized “Bop It,” “Twist It,” and “Shake It” commands keep players on their toes, while animated faces and color-coded rings provide instant visual feedback.

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled.png)

<aside>
💡 Implement a lightweight SwiftUI game loop to handle timed prompts and sensor input.

</aside>

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled%201.png)

<aside>
💡 Use AVAudioPlayer to play synthesized voice commands and manage audio session

</aside>

![Untitled](Fibber%20-%20Truth%20Detector%20-%20Apple%20Watch%20App/Untitled%202.png)

<aside>
💡 Animate face expressions and ring colors in real time to reflect correct actions and game-over states.

</aside>

---

# Process

The process was centered on creative prototyping, user feedback, and repeated playtesting across real devices—not just the simulator. The focus was on tight interaction, expressive feedback, and seamless performance.

<aside>
👇 Click to jump to section

</aside>

[User Research →](Reflex-o%20-%20Apple%20Watch%20App%20210ebd589b2680ab8e4bd0fc31feecc8.md) 

[Sketches →](Reflex-o%20-%20Apple%20Watch%20App%20210ebd589b2680ab8e4bd0fc31feecc8.md)

[Wireframes / Prototypes →](Reflex-o%20-%20Apple%20Watch%20App%20210ebd589b2680ab8e4bd0fc31feecc8.md)

[Usability Study →](Reflex-o%20-%20Apple%20Watch%20App%20210ebd589b2680ab8e4bd0fc31feecc8.md)

### User Research

User research focused on what makes micro-games fun. I studied *Bop It*, Apple Watch fitness gestures, and simple games in the App Store. I also ran early tests to determine how fast users can respond to haptics and commands, refining what made each round feel “winnable but challenging.”

<aside>
👉 Identified key motivators: simple commands, expressive feedback, fast resets, and physical input (twist, shake, tap).

</aside>

### Sketches

I sketched out the app flow and robot face states—open-mouth (command), big eyes (idle), X eyes (failure). Layouts were optimized for glanceability and one-handed interaction, assuming the user would be tapping or moving their wrist.

<aside>
👉 Mapped each command to a specific interaction and facial animation for clear, repeatable gameplay.

</aside>

### Wireframes / Prototypes

Initial wireframes were built in SwiftUI with placeholder circles and text. After validating the core loop, I integrated AVFoundation for voice prompts and added haptic feedback per command. All animations were tested on real hardware.

<aside>
👉

Created a working prototype with a complete game loop: command → wait → input → result → next round or fail.

</aside>

### Usability Study

Five testers played Reflexo on Apple Watch. They reported on timing, audio clarity, difficulty curve, and how intuitive the interactions were. Feedback led to a longer delay after commands, a clearer failure animation, and better eye size transitions.

<aside>
👉

Increased clarity and polish by adjusting animation speed, adding mouth shapes, and refining timing between rounds.

</aside>

---

# Major Design Iterations

### - Iteration 1.

Built the core game loop and static prompts. Gameplay was functional but lacked charm, and animations felt robotic (in the bad way).

### - Iteration 2.

Added robot face with expressive eyes and mouth animations. Voice prompts were integrated using AVFoundation. Haptic feedback added per command.

### - Iteration 3.

Optimized SwiftUI animations for performance. Refined loss state animation (X eyes, red ring). Added randomized command logic and command cooldown.

---

# Final Design (Work in Progress)

<aside>
👇 Currently live on test devices, with App Store version in development.

</aside>

### Product Successes

Reflexo received **4.8/5 average ratings** from internal testers, with players describing it as “weirdly addictive,” “very Apple-like,” and “the best use of voice I’ve seen in a Watch game.”

After performance optimization, the app had **0% crash rate** and ran consistently at 60fps on Series 6 and above.

Playtesting showed users replaying the game an average of **5.2 times per session**, with most sessions lasting under 3 minutes—perfectly optimized for wrist-based gaming.

### What I Learned

Reflex-o taught me how to make **something fun** quick to pick up, satisfying to play, and perfectly sized for the wrist. Designing for Apple Watch meant stripping the game down to its most expressive and tactile elements no menus, no fluff, just action. I learned how to build fluid SwiftUI animations, manage audio sessions with AVFoundation, and create a responsive loop that feels good even with limited inputs.