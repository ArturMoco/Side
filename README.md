# 🧪 **Technical QA Guide — Side (Mobile Puzzle Game)**

---

## 🎯 Objective

This document outlines my practical and structured approach to functional QA for mobile puzzle games using match-3 mechanics. It reflects the mindset I apply when validating gameplay features, user experience, and platform stability, in line with Side’s expectations.

---

## 📱 Target Platforms

* Android (various screen sizes and versions)
* iOS (iPhone/iPad)
* PC (Windows)
* Console (Nintendo Switch)

---

## 🔍 Types of Tests Performed

* Functional Testing
* Cross-Platform Compatibility Testing
* UI and Layout Validation
* Save State and Progression Testing
* Basic Performance and Responsiveness
* Smoke and Sanity Testing per build

---

## 🧩 Key Functional Areas to Validate

* Core match-3 logic (valid moves, blockers, boosters)
* Energy/lives and monetization system (simulated in-app purchases)
* Animation flow and response time after actions
* Autosave of player progress (levels, coins, boosters)
* Daily rewards and limited-time events
* Language localization and text accuracy
* HUD consistency (score, coins, hearts, etc.)
* Offline functionality and reconnection handling
* App-switching behavior (multitasking)

---

## 🛠️ Suggested Tools

* **TestRail / Xray** — Test documentation
* **Jira** — Bug tracking and ticket management
* **Google Sheets / Excel** — Manual evidence tracking
* **Charles Proxy / Postman** — API inspection (if applicable)
* **ADB / Xcode** — Physical device debugging and logs

---

## 📋 Sample Test Case

**Functionality:** Match-3 movement mechanics

**Scenario:** Player performs a valid move that triggers a match

**Steps:**

1. Launch the game and start the first available level
2. Make a move to align 3 identical tiles
3. Observe animation, score update, and tile replacement

**Expected Result:**

* Tiles are cleared correctly
* Smooth animations without freezing
* Score is updated accurately
* New tiles drop and fill correctly

**Environment:**

* Android 13, iPhone iOS 17, Switch Lite, Windows 11

---

## 🔁 Cross-Platform Testing

* Compare loading times and responsiveness across devices
* Ensure UI scales well on small and large screens
* Validate progress sync between devices (if supported)
* Confirm HUD does not overlap game content on limited screen space

---

## 📊 Reports and Evidence

Report quality is critical in my QA workflow. For every tested build, I provide well-documented evidence in the following formats:

* **Bug Reports (Jira)**: Clear descriptions, reproduction steps, affected platforms, and media evidence.
* **Execution Reports (Excel or TestRail)**: Status table (Pass/Fail/Blocked), duration, comments, links to evidence.
* **Visual Reports (PDF/Slides)**: Shared during checkpoints, including critical bugs and mitigation suggestions.
* **Short Video Captures**: For intermittent bugs or animation errors.
* **Platform Comparison Summaries**: To highlight platform-specific issues.

All reports follow a priority system based on impact, frequency, and user-facing relevance.

---

## 🧮 Bug Classification and Prioritization

When I encounter a bug, I apply the following 3-step logic:

1. **Controlled Reproduction**: Confirm consistency of the issue across environments or scenarios.

2. **Severity Classification**:

   * **High**: Breaks gameplay or logic, blocks progression, corrupts data
   * **Medium**: Partial functionality loss, misbehavior, or distracting visuals
   * **Low**: Cosmetic, text errors, non-blocking glitches

3. **Priority Assessment**:

   * Based on project phase, visibility to players, frequency, and regression risk

This method ensures that reports are relevant, actionable, and technically informative.

---

## ⚠️ Known Risks and Edge Cases

* Softlock after invalid move
* Lost progress after force-closing the app
* Unresponsive buttons on specific resolutions
* Missing events after reconnecting to the internet
* Corrupted UI after switching language mid-session

---

## 🧠 Testing Mindset

* Test as an advanced player who seeks inconsistencies
* Observe animations frame-by-frame for lags or visual breaks
* Combine boosters or edge interactions to trigger unusual behavior
* Focus on the real player experience, not only technical requirements

---

## 📎 Final Notes

This guide reflects how I approach QA from a player-centric, detail-oriented perspective. I believe QA is not only about finding bugs, but ensuring that every interaction in the game feels smooth, fair, and immersive.

What sets me apart is my ability to combine structured reporting with an exploratory mindset, adapting quickly to new tools and platforms. I’m ready to contribute to the QA team at Side with consistency, technical clarity, and commitment to delivering polished mobile experiences.

---

**Artur Felipe Albuquerque Portela**  
QA Tester · Manual & Automation  
GitHub: github.com/ArturMoco  
LinkedIn: Artur Albuquerque  
Email: [arturengqa@gmail.com](mailto:arturengqa@gmail.com)
