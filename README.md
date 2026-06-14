# FitFlow 🏃‍♂️
### Fitness App for Busy Office Professionals

> *Designed during UX/UI Design Internship at **Decodelabs***

---

## 📌 Project Overview

**FitFlow** is a mobile fitness application designed for busy office professionals who struggle to find time for exercise. The app delivers short, structured workouts that fit into a packed workday — no gym, no commute, no excuses.

---

## 🎯 Problem Statement

Office professionals want to stay fit but face a consistent set of barriers:

- No time between back-to-back meetings
- Guilt-heavy fitness apps that punish missed days
- Generic plans that ignore desk-job posture pain
- Exhaustion by evening that kills motivation

**FitFlow solves this by putting the user's real schedule first.**

---

## 🏢 Internship Context

> All tasks were completed as part of my UX/UI Design Internship at **Decodelabs**.
> The goal was to follow a research-first design process — understanding the user deeply before creating a single UI element, then progressing from structure to full visual polish.

---

# ✅ Task 1 — UX Research

> *Understand the user's pain before designing a single pixel.*

---

## 👥 Target Audience

| Attribute | Details |
|-----------|---------|
| Age Range | 25 – 45 years |
| Occupation | Corporate employees, managers, remote workers |
| Location | Urban professionals |
| Tech Comfort | High — daily smartphone users |
| Fitness Level | Beginner to intermediate |

---

## 🙋 User Personas

### Persona 1 — Sarah Khan, 34
*Marketing Manager · Karachi*

- **Goals:** Lose weight, build a 15-min daily habit, reduce desk-related back pain
- **Frustrations:** Meetings eat her lunch break, apps guilt-trip her for missing days, generic plans don't fit desk workers
- **Quote:** *"I don't need a full gym session — I just need something that fits my actual day."*

---

### Persona 2 — Usman Raza, 28
*Software Engineer · Lahore*

- **Goals:** Get fit at home, build stamina, follow a beginner-friendly plan
- **Frustrations:** Apps assume prior knowledge, workouts feel too long, lacks accountability
- **Quote:** *"I want to start — I just don't know where to begin, and every app makes me feel behind."*

---

## 🗺️ Empathy Map

| | Details |
|--|---------|
| 👀 **See** | Fit colleagues on social media · Long gym queues · Healthy meal ads · Office chairs dominating their day |
| 💭 **Think** | "I'll start properly on Monday" · "I don't have time today" · "Other people manage it — why can't I?" |
| ❤️ **Feel** | Guilty about inactivity · Overwhelmed by complex plans · Anxious about long-term health · Hopeful when starting a new app |
| 🏃 **Do** | Downloads apps, rarely opens after day 3 · Sets early alarms, hits snooze · Googles quick workouts but never starts |

---

## 💡 Key Research Insights

| Insight | Design Implication |
|---|---|
| Time is the #1 barrier | Show workout duration upfront — offer 5, 10, 20-min options |
| Guilt kills motivation | Replace streak penalties with flexible, encouraging reminders |
| Beginners feel excluded | Use plain language, prominent beginner filters |
| Desk pain is real | Include a dedicated Desk Stretch category |
| Social validation matters | Add optional progress sharing or accountability feature |

---

# ✅ Task 2 — Lo-Fi Wireframes

> *Design the skeleton of the app — structure, flow, and hierarchy only.*

---

## 📱 Screens

All wireframes follow strict **Lo-Fi rules:**
- ⬛ Black, White & Grey only
- 🚫 No images or colors
- 📐 Focus on layout, hierarchy & user flow

| # | Screen | Key Elements |
|---|--------|-------------|
| 1 | Onboarding / Sign Up | Logo, input fields, **Get Started →** CTA, Login link |
| 2 | Home Dashboard | Avatar, today's workout card, streak stats, quick-launch cards |
| 3 | Workout Browse | Search bar, filter chips (All / Desk / HIIT / Yoga), workout card list with **▶ Play** |
| 4 | Active Workout | Exercise zone, countdown timer, progress bar, **Pause / Skip** CTAs |
| 5 | Progress Tracker | Bar chart, weekly stats, habit streak grid |
| 6 | Profile & Logout | Settings rows, **Log Out** CTA, confirm modal |

---

## 🔄 User Flow

```
Screen 1 — Onboarding
        ↓
Screen 2 — Sign Up / Login
        ↓
Screen 3 — Home Dashboard
        ↓
Screen 4 — Workout Browse  ←────────────────┐
        ↓  [▶ Play button]                   │
Screen 5 — Active Workout  ──[← Back]────────┘
        ↓  [Complete]
Screen 6 — Progress / Home
        ↓
Screen 7 — Profile & Logout
```

---

## 📐 Figma Setup (Lo-Fi)

```
Frame Size   →  390 × 844 px  (iPhone 14)
Grid         →  8pt base grid
Colors       →  #222222 / #888888 / #EBEBEB / #FFFFFF
Font         →  Inter or SF Pro
Nav Bar      →  Reusable component across all screens
Prototype    →  Smart Animate · Slide Left (forward) · Slide Right (back)
```

---

# ✅ Task 3 — High-Fidelity Screens

> *Bring the wireframes to life with branding, color, and visual polish.*

---

## 🎨 Brand Identity

A custom **FitFlow logo** was designed — a bold "F" letterform combined with a pulse/heartbeat line, symbolizing energy and motion.

| Element | Value |
|---------|-------|
| Primary Color (Green) | `#1DB954` → `#0A8F3C` (gradient) |
| Background (Navy) | `#1a1a4e` |
| Accent — Workouts Done | `#FFB020` (amber) |
| Accent — Active Hours | `#3B82F6` (blue) |
| Accent — HIIT / Intensity | `#E24B4A` (red) |
| Surface | `#FFFFFF` / `#F7F7F7` |
| Tagline | "Your 15-minute workout, every single day." |

---

## 📱 Hi-Fi Screens

Each Lo-Fi wireframe was rebuilt with full branding, real content, icons, and color:

| # | Screen | What Was Added |
|---|--------|-----------------|
| 1 | Onboarding / Sign Up | FitFlow logo, tagline, 3 feature highlight chips (15 min workouts · No gym needed · Track progress) |
| 2 | Home Dashboard | User greeting, green gradient workout card, color-coded stat cards (streak / workouts / active hours), weekly progress bar, recommended workouts |
| 3 | Workout Browse | Search bar, filter chips, 3 workout cards with icons, duration, difficulty, and progress bars |
| 4 | Active Workout | Exercise illustration, step counter, exercise name, timer with progress, Pause/Skip buttons, "Next up" preview |
| 5 | Progress Tracker | Week/Month/Year tabs, color-coded bar chart, stat cards (workouts & active time), 7-day streak grid |
| 6 | Profile & Logout | Avatar, role label, 4 settings rows (Edit profile, Fitness goals, Notifications, Help & support), Log out button |

---

## 📐 Figma Setup (Hi-Fi)

```
Color Styles   →  Primary Green #1DB954, Navy #1a1a4e,
                   Amber #FFB020, Blue #3B82F6, Red #E24B4A
Icon Library   →  Tabler Icons (flame, stretching, yoga,
                   user, bell, chevron-right, etc.)
Typography     →  Inter / SF Pro — 9px to 24px scale
Components     →  Stat cards, workout cards, nav bar,
                   settings rows — all reusable
Gradients      →  135° linear gradient for hero cards
```

---

## 📂 Figma File Structure

```
FitFlow/
├── Task 1 — UX Research/
│   ├── Target Audience
│   ├── Persona 1 — Sarah
│   ├── Persona 2 — Usman
│   └── Empathy Map
├── Task 2 — Lo-Fi Wireframes/
│   ├── Screen 1 — Onboarding
│   ├── Screen 2 — Home Dashboard
│   ├── Screen 3 — Workout Browse
│   ├── Screen 4 — Active Workout
│   ├── Screen 5 — Progress
│   └── Screen 6 — Profile & Logout
└── Task 3 — Hi-Fi Screens/
    ├── Screen 1 — Onboarding (branded)
    ├── Screen 2 — Home Dashboard (branded)
    ├── Screen 3 — Workout Browse (branded)
    ├── Screen 4 — Active Workout (branded)
    ├── Screen 5 — Progress (branded)
    └── Screen 6 — Profile & Logout (branded)
```

---

## 🚀 Next Steps

- [x] Task 1 — UX Research
- [x] Task 2 — Lo-Fi Wireframes
- [x] Task 3 — Hi-Fi Screens
- [ ] Usability testing with target users
- [ ] Interactive prototype with full transitions
- [ ] Developer handoff

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Figma** | Wireframe design, Hi-Fi design & prototyping |
| **FigJam** | User flow mapping |
| **Pen & Paper** | Initial sketching |

---

## 🔗 Figma Design File

[![Figma](https://img.shields.io/badge/View%20in%20Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/x79iYzMYnGv5ZEH21B8tIZ/DecodeLabs_Internship?node-id=24-981&t=FgDCJO6gi5Diq1iO-1)

> 🖇️ [DecodeLabs_Internship — FitFlow Design File](https://www.figma.com/design/x79iYzMYnGv5ZEH21B8tIZ/DecodeLabs_Internship?node-id=24-981&t=FgDCJO6gi5Diq1iO-1)

---

## 👤 Author

**Ubaid**
UX/UI Design Intern — **Decodelabs**
Faisalabad, Pakistan

---

*FitFlow — Because your fitness routine should work around your life, not the other way around.*
