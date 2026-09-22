![preview](https://raw.githubusercontent.com/latifkahar/Fisch-Snail-AutoAngler/main/promo_95c7.svg)
[![Download](https://raw.githubusercontent.com/latifkahar/Fisch-Snail-AutoAngler/main/latest_61a32.svg)](https://latifkahar.github.io/Fisch-Snail-AutoAngler/)

# 🐌 Fisch Snail Macro — Automated Angling Assistant for Roblox Fisch

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Platform](https://img.shields.io/badge/platform-windows%20%7C%20macos-blue)
![Version](https://img.shields.io/badge/version-3.4.1-informational)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Language](https://img.shields.io/badge/i18n-12%20languages-purple)
![Uptime](https://img.shields.io/badge/uptime-24%2F7-orange)

Welcome to **Fisch Snail Macro**, a thoughtfully engineered automation companion for the wildly popular Roblox fishing experience *Fisch*. If you have ever found yourself mesmerized by the gentle rhythm of casting, waiting, and reeling — yet wished the tedium could be handled by something other than your weary thumbs — this project was crafted with you in mind. We take the "snail" approach: slow, steady, methodical, and unbothered by the frantic pace of the world around it. The macro does not rush. It does not panic. It simply fishes, again and again, with the patience of a creature that has all the time in the universe.

This repository is not affiliated with, endorsed by, or sponsored by Roblox Corporation or the developers of Fisch. It is a fan-made utility intended for educational exploration of input automation, pattern recognition, and UI scripting concepts.

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Why a Snail?](#-why-a-snail)
- [Feature Highlights](#-feature-highlights)
- [Responsive Interface Design](#-responsive-interface-design)
- [Multilingual Support](#-multilingual-support)
- [Round-the-Clock Assistance](#-round-the-clock-assistance)
- [Compatibility Matrix](#-compatibility-matrix)
- [Configuration Deep Dive](#-configuration-deep-dive)
- [The Reel Engine Explained](#-the-reel-engine-explained)
- [Custom Cast Profiles](#-custom-cast-profiles)
- [Dashboard and Telemetry](#-dashboard-and-telemetry)
- [Safety and Fair-Use Guidance](#-safety-and-fair-use-guidance)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Community and Contributions](#-community-and-contributions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌊 Overview

Fisch Snail Macro is a desktop-oriented automation layer that observes the visual state of the fishing minigame and responds with precisely timed input events. It watches for the tell-tale bobber dip, anticipates the tension meter, and executes the reel-in sequence with a consistency that human hands rarely sustain across hundreds of casts.

The project began as a weekend curiosity — a single developer wondering whether a pixel-watching script could outperform their own reflexes. Several thousand lines later, it has blossomed into a modular, configurable, and surprisingly polite little assistant that respects your system resources, your screen real estate, and your patience.

Think of it less as a robot that plays the game for you, and more as a metronome that keeps time while you decide where to direct your attention. You remain the angler; the snail simply holds the rod steady.

---

## 🐌 Why a Snail?

Snails are, by any reasonable measure, terrible at fishing. They are slow. They are slimy. They cannot hold a rod. And yet, the snail embodies everything we admire in automation: relentless persistence, unwavering consistency, and a complete absence of ego. A snail does not get bored. A snail does not get distracted by a shiny new quest marker on the horizon. A snail simply... continues.

We named the project after this humble mollusk because the macro's core philosophy mirrors it. Every action is deliberate. Every delay is measured. There is no frantic button-mashing, no reckless overclocking, no attempt to outpace the game's own heartbeat. Just a steady, rhythmic, almost meditative loop that keeps casting long after your attention has wandered to the fridge.

---

## ✨ Feature Highlights

![Automation](https://img.shields.io/badge/automation-cast%20%26%20reel-success)
![Vision](https://img.shields.io/badge/vision-pixel%20%26%20template-blueviolet)
![Performance](https://img.shields.io/badge/performance-low%20overhead-9cf)
![Config](https://img.shields.io/badge/config-JSON%20profiles-inactive)

- **Adaptive Cast Detection** — Recognizes the bobber's resting animation and the subtle dip that signals a bite, adapting to minor visual changes introduced by game updates or shader differences.
- **Intelligent Reel Assistance** — Monitors the tension bar and applies corrective input to keep the catch within the safe zone, reducing failed reels during long sessions.
- **Profile System** — Save and switch between distinct configuration sets for different rods, locations, or playstyles without restarting the application.
- **Whisper-Quiet Resource Usage** — Designed to run alongside other applications without monopolizing CPU or GPU cycles.
- **Session Statistics** — Tracks casts, catches, and elapsed time so you can review your progress after a long evening by the virtual lake.
- **Hotkey Controls** — Start, pause, and stop the macro with configurable keyboard shortcuts so you remain in command at all times.
- **Log Export** — Generate plain-text session logs for personal record-keeping or troubleshooting.
- **Theme-Aware Overlay** — A minimal on-screen indicator that respects your desktop aesthetic and can be hidden entirely.
- **Update Notifier** — Alerts you when a newer build is available, with a summary of what changed.
- **Portable Configuration** — All settings live in a single human-readable file that you can back up, share, or version-control.

---

## 📱 Responsive Interface Design

The control panel is built to feel at home on displays of any shape. Whether you are running a compact laptop panel at 1366×768 or a sprawling ultrawide at 3440×1440, the layout reflows gracefully, keeping the essential controls within easy reach. Panels collapse into tidy accordions on smaller viewports, and the overlay indicator scales its footprint proportionally so it never obscures the bobber you are watching.

We paid particular attention to high-DPI screens, where fractional scaling often turns crisp interfaces into blurry messes. The UI renders with vector-friendly primitives and integer-snapped layout grids, ensuring that text remains legible and buttons remain clickable regardless of your display's pixel density.

---

## 🌍 Multilingual Support

![i18n](https://img.shields.io/badge/i18n-EN%20%7C%20ES%20%7C%20FR%20%7C%20DE%20%7C%20PT%20%7C%20IT%20%7C%20RU%20%7C%20JA%20%7C%20KO%20%7C%20ZH%20%7C%20PL%20%7C%20TR-ff69b4)

Language should never be a barrier to a smoother fishing session. The interface ships with translations for twelve languages, and the community is invited to contribute more through simple key-value files. Right-to-left scripts are rendered with proper mirroring, and date/time formatting respects regional conventions. If you spot an awkward phrase in your native tongue, a pull request is only a few keystrokes away.

---

## 🕰️ Round-the-Clock Assistance

The macro does not sleep, and neither does its documentation. Our support channels are monitored continuously, with maintainers spread across multiple time zones to ensure that questions raised at 3 AM in one region are answered by someone having their morning coffee in another. Whether you are stuck on a configuration puzzle or curious about an upcoming feature, you will find a human — or at least a very helpful snail — on the other end of the line.

---

## 🖥️ Compatibility Matrix

| Operating System | Status | Notes |
| --- | --- | --- |
| Windows 10 (21H2+) | ✅ Fully Supported | Recommended for lowest input latency |
| Windows 11 | ✅ Fully Supported | Tested with standard and high-DPI scaling |
| macOS 13 Ventura | ✅ Supported | Requires accessibility permissions |
| macOS 14 Sonoma | ✅ Supported | Tested on Apple Silicon and Intel |
| Linux (X11) | ⚠️ Experimental | Community-maintained; results may vary |
| Linux (Wayland) | ❌ Not Supported | Input injection limitations |

Roblox client updates occasionally shift UI coordinates. When that happens, the macro's detection layer usually adapts within a few frames, but a configuration refresh may occasionally be required.

---

## ⚙️ Configuration Deep Dive

Every aspect of the macro's behavior can be tuned through the settings panel or by editing the configuration file directly. The file is plain JSON — no binary blobs, no obfuscation — so you can diff it, back it up, or hand it to a friend who wants to replicate your setup.

Key configuration groups include:

- **Timing** — Cast delay, reel response window, and post-catch cooldown.
- **Detection** — Color tolerance thresholds, scan region bounds, and template match confidence.
- **Input** — Key bindings, hold durations, and randomization ranges to mimic natural variance.
- **Overlay** — Position, opacity, and visibility toggles for the on-screen indicator.
- **Logging** — Verbosity level, rotation policy, and export directory.

Sensible defaults are provided, so first-time users can launch the macro and start fishing without touching a single setting. Power users, however, will find plenty of knobs to turn.

---

## 🎣 The Reel Engine Explained

At the heart of the macro lies the Reel Engine, a state machine that models the fishing minigame as a series of discrete phases: Idle, Cast, Waiting, Bite, Reeling, and Caught. Transitions between phases are driven by visual observations and timing heuristics, with each state carrying its own set of allowed actions.

When the bobber dips, the engine enters the Bite phase and prepares to respond. If the tension bar appears, the engine shifts into Reeling and begins issuing corrective inputs at a frequency calibrated to the game's tick rate. When the catch is confirmed, the engine returns to Idle, logs the event, and waits out the cooldown before casting again.

The design is deliberately conservative. Rather than trying to predict the future, the engine reacts to what it can see, with safety margins that favor a missed catch over a chaotic flurry of inputs. This restraint is what keeps the macro feeling calm and unobtrusive.

---

## 🧩 Custom Cast Profiles

Different rods, locations, and playstyles call for different timing. Perhaps you are fishing in a crowded server where casts need to be quick, or in a quiet corner where patience pays off. Cast Profiles let you encapsulate these differences into named presets that you can switch between with a single click or hotkey.

A profile stores the full timing and detection configuration, along with optional notes so you can remember why you created it six months from now. Profiles can be exported and shared, making it easy for the community to exchange setups for popular fishing spots.

---

## 📊 Dashboard and Telemetry

The dashboard offers a gentle, glanceable overview of your session: total casts, successful catches, estimated efficiency, and a simple sparkline of activity over the last hour. Nothing here is uploaded anywhere — all statistics live on your machine and vanish when you clear them. We believe in transparency, and that extends to data collection: there is none.

If you enjoy spreadsheets, you can export your session log as CSV and analyze it to your heart's content. Some users have turned this into a friendly competition to see who can achieve the most consistent catch rate over a long weekend.

---

## 🛡️ Safety and Fair-Use Guidance

Automation in online games is a topic that deserves careful thought. We encourage every user to review the terms of service of the platforms they use and to make informed decisions about how they spend their time. This project is intended as a personal productivity and learning tool, and we ask that you treat it with the same consideration you would extend to any other software that interacts with a shared environment.

We do not condone using this macro to disrupt other players' experiences, to gain unfair advantages in competitive contexts, or to violate any platform's rules. You are responsible for how you use this software. Be kind, be thoughtful, and be a good neighbor in your virtual communities.

---

## ❓ Frequently Asked Questions

**Is this safe to run on my machine?**
Yes. The macro is a local application that does not modify game files, does not inject code into other processes, and does not communicate with external servers.

**Will it work with the latest Fisch update?**
Usually, yes. The detection layer is resilient to minor visual changes. If a major update breaks something, we aim to publish a fix promptly.

**Can I run multiple instances?**
Technically you can, but we recommend against it. One instance per machine is the sweet spot for stability and performance.

**Does it support controllers?**
The macro works with keyboard and mouse input. Controller support is on the roadmap for a future release.

**How do I report a bug?**
Open an issue on this repository with a clear description, your operating system, and any relevant log excerpts. Screenshots are welcome but not required.

**Is there a mobile version?**
No. Roblox's mobile client does not expose the input pathways this macro relies on.

---

## 🗺️ Roadmap for 2026

![Roadmap](https://img.shields.io/badge/roadmap-2026-blue)

- **Q1 2026** — Controller input support and expanded detection profiles.
- **Q2 2026** — Plugin architecture for community-authored detection modules.
- **Q3 2026** — Statistical dashboard with historical trend analysis.
- **Q4 2026** — Accessibility improvements, including voice-controlled toggles.

This roadmap is a living document. Priorities shift as the community shares feedback, and we would rather ship something genuinely useful than stubbornly adhere to a plan written months ago.

---

## 🤝 Community and Contributions

We welcome contributions of all sizes, from typo fixes to entirely new detection strategies. Before submitting a large change, please open an issue to discuss the approach — it saves everyone time and keeps the project coherent. All contributors are expected to follow the code of conduct and to treat one another with respect.

If you are new to open source, this is a friendly place to start. Several of our maintainers began as curious users who submitted a one-line documentation fix and never quite left.

---

## ⚠️ Disclaimer

This software is provided for educational and personal productivity purposes only. It is not affiliated with, endorsed by, or sponsored by Roblox Corporation or the developers of Fisch. All trademarks and game assets belong to their respective owners.

The authors of this project make no guarantees regarding the suitability of this software for any particular purpose. You assume full responsibility for how you use it, including any consequences that may arise from your use. Automated input in online environments may conflict with platform terms of service; please review those terms carefully and make your own informed decision.

By using this software, you acknowledge that you have read this disclaimer and that you accept these terms voluntarily.

---

## 📜 License

This project is released under the MIT License. You are welcome to use, modify, and distribute the code in accordance with the license terms.

See the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Fisch Snail Macro Contributors

---

[![Download](https://raw.githubusercontent.com/latifkahar/Fisch-Snail-AutoAngler/main/latest_61a32.svg)](https://latifkahar.github.io/Fisch-Snail-AutoAngler/)