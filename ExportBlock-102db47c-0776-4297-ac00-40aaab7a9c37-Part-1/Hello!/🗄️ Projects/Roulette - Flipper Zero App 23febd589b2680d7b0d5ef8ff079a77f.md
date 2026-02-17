# Roulette  -  Flipper Zero App

Role: UI/UX Designer / App Developer
Timeline: June 2, 2025 → November 28, 2025
Tags: App Design, Product Design, UI/UX
Tools: API, CSS, Figma, Flipper Zero, Github, HTML, JS
Team: Developer (Me)
Link: github link → coming soon!

![Old York Times (9).png](Roulette%20-%20Flipper%20Zero%20App/Old_York_Times_(9).png)

# Summary

Roulette is a dramatic, sound-enhanced party game for the Flipper Zero, inspired by classic Russian Roulette but reimagined with digital suspense. Using the Flipper’s button input, audio cues, and haptic feedback, the app creates tension and excitement through randomized outcomes, making it one of the first *purely experiential* apps built for the device.

# Problem

The Flipper Zero is widely known for its tools and hacking modules—but it lacks playful, high-stakes games that utilize the device’s buzzer, screen, and input in a theatrical way. I wanted to explore the idea of creating a **party-style experience** on a hacker tool that feels emotional, suspenseful, and fun to pass around.

<aside>
❓ How can we build a social, suspense-driven game for Flipper Zero using limited hardware inputs and a black-and-white screen?

</aside>

# Solution

The solution is **Roulette**, a minimal game where each player “pulls the trigger” by pressing the center button. A sound plays, tension builds… and either silence (survival) or a dramatic buzzer (you’re out!) delivers the outcome. All actions are randomized but weighted for maximum suspense. The game is designed to be easy to restart and pass around between players.

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3).png)

<aside>
💡 Use the Flipper’s built-in buzzer and LED to simulate game tension and “explosive” feedback.

</aside>

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3)%201.png)

<aside>
💡 Implement pseudo-random outcomes with an adjustable bullet count to scale difficulty or player count.

</aside>

![Old York Times (3).png](PackTrack%20-%20Flipper%20Zero%20App/Old_York_Times_(3)%202.png)

<aside>
💡 Build the UI using bold text animations and delay logic to increase anticipation before revealing each outcome.

</aside>

---

# Process

This project followed an experimental development flow, focused on creating **emotional timing**—not just functionality. Prototyping focused heavily on playtesting for feel: when to pause, how to build suspense, and how to make the outcome feel *visceral* using only a buzzer and basic UI.

<aside>
👇 Click to jump to section

</aside>

[User Research →](Roulette%20-%20Flipper%20Zero%20App%2023febd589b2680d7b0d5ef8ff079a77f.md) 

[Sketches →](Roulette%20-%20Flipper%20Zero%20App%2023febd589b2680d7b0d5ef8ff079a77f.md)

[Wireframes / Prototypes →](Roulette%20-%20Flipper%20Zero%20App%2023febd589b2680d7b0d5ef8ff079a77f.md)

[Usability Study →](Roulette%20-%20Flipper%20Zero%20App%2023febd589b2680d7b0d5ef8ff079a77f.md)

### User Research

I researched traditional Russian Roulette game mechanics, mobile game timing loops, and user feedback from Flipper game forums. Players want games that are **quick to pick up, easy to pass around**, and dramatic enough to create reactions—even in silence.

<aside>
👉  Found that unpredictability, tension pacing, and sound are more important than graphics for building immersion on Flipper

</aside>

### Sketches

Initial sketches were focused on simulating a revolver chamber—either as an animation or simplified text sequence. I also planned sound states and LED flashes tied to survival or “death” triggers.

<aside>
👉 Sketched a 6-bullet animation loop, a countdown tension delay, and bold text reveal (“CLICK” vs “BOOM”) for impact.

</aside>

### Wireframes / Prototypes

The first prototype used only random outcomes on button press with simple text results. I then layered in buzzer feedback and delay logic. Buzz delay length became key to pacing.

<aside>
👉 Prototyped with a 1-in-6 outcome engine, randomized per game, and buzzer tone assigned only to “BOOM” result.

</aside>

### Usability Study

Early testers played in groups and passed the Flipper around. Feedback focused on the need for **build-up tension**, **more randomness per round**, and ways to make the “loss” moment more dramatic and satisfying.

<aside>
👉 Added suspense delay, countdown dots, and varied buzzer tones. Explored LED color flashes for future hardware expansions.

</aside>

---

# Major Design Iterations

### - Iteration 1.

Static random result + text message. No pacing or sound—felt too fast and forgettable.

### - Iteration 2.

Added buzzer feedback, randomized round count, and delayed reveals. Players began to *anticipate* and laugh after losses.

### - Iteration 3.

Working on customizable modes (1 bullet, 2 bullets, custom chamber sizes), better screen animations, and multi-round logic for competitive scoring.

---

# Final Design (Work in Progress)

<aside>
👇 Internal prototype working on Flipper Zero. GitHub release and mod support planned post-launch.

</aside>

### Current Product Successes

The app is already showing strong appeal in early play sessions. Testers described it as “genuinely suspenseful,” “fun to lose,” and “the most dramatic thing I’ve ever done with a Flipper.”

The simple interaction loop and universal concept have made it extremely **replayable** during group testing—and it’s currently one of the most fun Flipper apps in my toolset.

### What I Am Learning

Roulette is teaching me how to build **emotional feedback systems with almost no UI**. The app has pushed my thinking on **timing, pacing, and physical feedback**—proving that even with a tiny screen and buzzer, it’s possible to deliver **drama**.

From buzzer tone shaping to delay management, I’m learning how to tune reactions *without graphics*. It’s making me a better embedded designer and opening up possibilities for future party apps on unconventional devices like Flipper Zero.