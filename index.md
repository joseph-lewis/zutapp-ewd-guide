---
tags: [project-doc, zutapp, ewd, user-guide, nhvr, fatigue-management]
date: 2026-04-16
status: complete
---

<div align="center">

# 📘 ZuTapp Electronic Work Diary (EWD)

### Complete User Guide & Reference

**For Drivers · Fleet Managers · Bus Companies · Internal Teams**

*NHVR-Compliant Electronic Work Diary System*

---

</div>

> **What is this document?** This is the complete guide to using the EWD (Electronic Work Diary) module within the ZuTapp mobile app. It covers every feature, every screen, and every workflow — from clocking on for your first shift to handling a roadside inspection by an NHVR authorised officer.

---

## 📑 Table of Contents

### Getting Started
- [1. What is an EWD?](#1-what-is-an-ewd)
- [2. Who Needs an EWD?](#2-who-needs-an-ewd)
- [3. EWD Home Page — Your Hub](#3-ewd-home-page--your-hub)

### Setting Up Your Profile
- [4. Driver Profile Setup](#4-driver-profile-setup)
- [5. Choosing Your Fatigue Plan (Ruleset)](#5-choosing-your-fatigue-plan-ruleset)

### Starting a Shift
- [6. Fit to Drive Declaration](#6-fit-to-drive-declaration)
- [7. Clocking On — Starting Your Shift](#7-clocking-on--starting-your-shift)
- [8. Evaluation Mode (Demo/Training)](#8-evaluation-mode-demotraining)

### During Your Shift
- [9. The On-Shift Dashboard](#9-the-on-shift-dashboard)
- [10. Switching Between Work and Rest](#10-switching-between-work-and-rest)
- [11. Changing Vehicles Mid-Shift](#11-changing-vehicles-mid-shift)
- [12. Understanding the Countdown Timer](#12-understanding-the-countdown-timer)
- [13. Breach Warnings & Notifications](#13-breach-warnings--notifications)

### Ending Your Shift
- [14. Clocking Off — Ending Your Shift](#14-clocking-off--ending-your-shift)

### Compliance & Fatigue Rules
- [15. Compliance Dashboard](#15-compliance-dashboard)
- [16. Understanding Breach Levels](#16-understanding-breach-levels)
- [17. Recovery Plan — Getting Back to Compliant](#17-recovery-plan--getting-back-to-compliant)
- [18. Breach History](#18-breach-history)

### Roadside Inspections
- [19. Compliance Lock Mode — Roadside Inspection](#19-compliance-lock-mode--roadside-inspection)
- [20. What an Authorised Officer Can See](#20-what-an-authorised-officer-can-see)
- [21. Annotations — Officer Notes](#21-annotations--officer-notes)

### Views & Reports
- [22. Graphical View (24-Hour Timeline)](#22-graphical-view-24-hour-timeline)
- [23. Tabular View (Event Table)](#23-tabular-view-event-table)
- [24. Work Diary History (28-Day Log)](#24-work-diary-history-28-day-log)
- [25. Report Transfer — PDF Export & Email](#25-report-transfer--pdf-export--email)

### Offline & Connectivity
- [26. Offline-First — How Your Data Stays Safe](#26-offline-first--how-your-data-stays-safe)
- [27. Sync & Communications Failure](#27-sync--communications-failure)

### Vehicle Walkaround Integration
- [28. Pre-Shift Vehicle Walkaround](#28-pre-shift-vehicle-walkaround)

### Administration
- [29. EWD Admin Tools (Internal)](#29-ewd-admin-tools-internal)

### Reference
- [30. NHVR Fatigue Rulesets — Full Reference](#30-nhvr-fatigue-rulesets--full-reference)
- [31. Glossary of Terms](#31-glossary-of-terms)
- [32. Frequently Asked Questions (FAQ)](#32-frequently-asked-questions-faq)
- [33. Support & Contact](#33-support--contact)

---

## 1. What is an EWD?

An **Electronic Work Diary (EWD)** is a digital replacement for the traditional paper-based Written Work Diary (WWD) used by heavy vehicle drivers in Australia. EWDs are regulated by the **National Heavy Vehicle Regulator (NHVR)** and must meet strict standards before they can be approved for use.

### Why use an EWD instead of paper?

| Feature | Paper Diary (WWD) | ZuTapp EWD |
|---|---|---|
| Time tracking | Manual entry | Automatic, real-time |
| Location recording | Written by driver | GPS auto-capture |
| Compliance checking | Manual calculation | Instant, automated |
| Breach detection | After the fact | Real-time warnings |
| Roadside inspection | Hand over paper book | Locked screen mode |
| Report generation | Photocopy pages | One-tap PDF export |
| Data backup | None (paper only) | Cloud sync + local storage |
| 28-day history | Carry physical book | Always on your phone |

### How ZuTapp's EWD works

ZuTapp's EWD module:

1. **Tracks your work and rest periods** in real-time with GPS location and timestamps
2. **Evaluates your compliance** against NHVR fatigue rules continuously
3. **Warns you** before you approach or breach fatigue limits
4. **Stores 28 days** of work diary records on your device (even offline)
5. **Syncs to the cloud** when connectivity is available
6. **Generates NHVR-compliant reports** for transfer or inspection
7. **Provides a locked inspection mode** for roadside checks by authorised officers

[↑ Back to Table of Contents](#-table-of-contents)

---

## 2. Who Needs an EWD?

Under Australian law, drivers of **fatigue-regulated heavy vehicles** must keep a work diary. This includes:

- **Heavy vehicle drivers** operating vehicles over 12 tonnes GVM (Gross Vehicle Mass)
- **Bus drivers** operating buses with more than 12 seats (including the driver)
- **Drivers operating beyond a 100km radius** from their base

ZuTapp's EWD supports **five NHVR-approved fatigue rulesets**:

| Ruleset | ID | Who It's For |
|---|---|---|
| Standard Hours — Solo Driver, Heavy Vehicle | RSID 1 | Solo truck/heavy vehicle drivers |
| Standard Hours — Solo Driver, Bus | RSID 2 | Solo bus/coach drivers |
| Standard Hours — 2-Up Driver, Heavy Vehicle | RSID 3 | Two-up (team) truck drivers |
| BFM Hours — Solo Driver, Heavy Vehicle | RSID 4 | Solo drivers under Basic Fatigue Management |
| BFM Hours — 2-Up Driver, Heavy Vehicle | RSID 5 | Two-up drivers under BFM |

> **💡 Tip:** If you're unsure which ruleset applies to you, check with your fleet manager or refer to the [NHVR fatigue management page](https://www.nhvr.gov.au/safety-accreditation-compliance/fatigue-management).

[↑ Back to Table of Contents](#-table-of-contents)

---

## 3. EWD Home Page — Your Hub

The EWD Home Page is the first screen you see when you open the EWD module. It's your central hub for everything.

### What you'll see

**Driver Status Banner** — A colour-coded banner at the top showing your current status:
- 🟢 **Working** — You are currently in a "Work" period
- 🔴 **Resting** — You are currently in a "Rest" period
- ⚫ **Off Shift** — You don't have an active shift
- 🟡 **Shift Expired** — Your shift has been running for more than 24 hours (see [Stale Shifts](#what-is-a-stale-shift))

**Quick Actions** — Large tap targets to get you where you need to go:
- **Start Shift** / **View Shift** — Begin a new shift or jump to your active shift
- **Work Diary** — View your 28-day work diary history
- **Compliance** — Check your current compliance status
- **Report Transfer** — Generate and send PDF reports

**Dashboard Stats** (when on shift):
- **Work Time** — Total work accumulated in the current period
- **Next Break In** — Time remaining before your next mandatory rest
- **Rest Remaining** — How much more rest you need
- **Breaches** — Number of active breaches
- **Shift Duration** — How long your current shift has been running

**EWD Pages Menu** — Quick links to all EWD features:
- Work Diary History
- Graphical View
- Tabular View
- Report Transfer
- Compliance View
- Fatigue Settings
- Driver Profile
- EWD Admin

[↑ Back to Table of Contents](#-table-of-contents)

---

## 4. Driver Profile Setup

Before you can start your first shift, you **must** complete your driver profile. The app will block clock-on until all mandatory fields are filled in.

### Required fields

| Field | Description | Example |
|---|---|---|
| **Full Name** | Your legal name as on your licence | John Smith |
| **Driver Unique ID** | Your company or NHVR-assigned driver ID | DRV-00142 |
| **Licence Number** | Your driver's licence number | 12345678 |
| **Licence State** | The state that issued your licence | QLD |
| **Licence Expiry** | When your licence expires | 15/03/2028 |
| **Base Location** | Your home depot/base address | 42 Industrial Ave, Eagle Farm QLD |
| **Home Timezone** | Your home timezone for calculations | Australia/Brisbane |

> **💡 Tip:** The Base Location field has **address autocomplete** powered by Google Places — start typing and select from the suggestions for accuracy.

### How to access your profile

1. From the EWD Home Page, tap **Driver Profile** in the pages list
2. Or while on shift, tap the **Profile tab** (3rd tab) in the bottom navigation

### NHVR Compliance

Your driver profile data is included in the **Compliance View** that authorised officers see during roadside inspections (per NHVR EWD Standards Section 27.1). This includes your name, unique ID, licence details, base location, and home timezone.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 5. Choosing Your Fatigue Plan (Ruleset)

Before each shift, you select which **fatigue ruleset** applies. Your default can be set in advance so you don't have to choose every time.

### How to set your default ruleset

1. From the EWD Home Page, tap **Fatigue Settings**
2. Browse the available rulesets — each shows its full period rules, work limits, and break requirements
3. Tap the dropdown to switch between rulesets for comparison
4. Set your preferred default

### What each ruleset controls

Each ruleset defines:
- **Rolling time windows** (e.g., 24 hours, 7 days, 14 days)
- **Maximum work hours** per window (e.g., max 12 hours work in 24 hours)
- **Minimum rest requirements** per window (e.g., min 7 hours continuous rest in 24 hours)
- **Break requirements** (e.g., 15-minute rest blocks, night rest rules)
- **Breach severity thresholds** (Minor, Substantial, Severe, Critical)

> **💡 Tip:** You can change your ruleset at clock-on time. The default just saves you a step. See [Section 30: Full Ruleset Reference](#30-nhvr-fatigue-rulesets--full-reference) for detailed breakdowns.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 6. Fit to Drive Declaration

Every time you start a shift, you **must** complete a Fit to Drive declaration. This is a legal requirement and cannot be skipped.

### What you'll see

A screen with **6 declaration items** — each must be individually confirmed by tapping the checkbox:

1. ✅ I have had adequate sleep before this shift
2. ✅ I am not impaired by fatigue, illness, or any substance
3. ✅ I am fit to safely drive a heavy vehicle
4. ✅ I understand the fatigue management requirements that apply
5. ✅ I will comply with my work/rest requirements
6. ✅ I understand the penalties for non-compliance

> **⚠️ Important:** You cannot proceed to clock on until **all 6 items** are checked. The screen auto-scrolls to the next unchecked item to help you.

Your declaration is **timestamped and stored** for audit purposes with the app version number.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 7. Clocking On — Starting Your Shift

Once you've confirmed your Fit to Drive declaration, you'll see the **Clock-On screen**. This is where you set up your shift.

### Clock-On fields

| Field | Description | Notes |
|---|---|---|
| **Work/Rest Option** | Your fatigue ruleset for this shift | Dropdown with all 5 NHVR rulesets |
| **Vehicle Registration** | The rego of the vehicle you're driving | May be pre-filled from Walkaround |
| **Odometer** | Current odometer reading (km) | May be pre-filled from Walkaround |
| **Location** | Your current location | Auto-detected via GPS (suburb + postcode) |
| **Start In** | Whether to start in Work or Rest mode | Most drivers start in Work |

### What happens when you clock on

1. **Compliance pre-check** — The app checks your last 28 days of history against the selected ruleset
2. If you have **existing breaches**, a dialog appears asking you to acknowledge and provide a reason
3. If you're **approaching limits** (>80% of work limit used), a warning is shown
4. A **confirmation dialog** appears with your shift details
5. Your shift begins and you're taken to the [On-Shift Dashboard](#9-the-on-shift-dashboard)

### Location details

Your location is automatically captured via GPS (latitude/longitude) and **reverse-geocoded** to show a readable suburb and postcode. You can:
- Edit the location name if GPS is inaccurate
- Add a custom suffix (e.g., "Depot Bay 3")

### Pre-fill from Vehicle Walkaround

If you completed a Vehicle Walkaround checklist before clocking on (see [Section 28](#28-pre-shift-vehicle-walkaround)), the following will be **automatically pre-filled**:
- Vehicle registration (extracted from the walkaround)
- Odometer reading
- Shift start time (backdated to when the walkaround began)

[↑ Back to Table of Contents](#-table-of-contents)

---

## 8. Evaluation Mode (Demo/Training)

**Evaluation Mode** is a special training/demo mode that lets you try the EWD system without creating real records.

### How to enable it

On the Clock-On screen, toggle the **"Evaluation Mode"** switch before starting your shift.

### What makes it different

| Feature | Normal Mode | Evaluation Mode |
|---|---|---|
| Data synced to server | ✅ Yes | ❌ No — local only |
| Compliance snapshots saved | ✅ Yes | ❌ No |
| Background notifications | ✅ Yes | ❌ No |
| Data cleared on logout | ❌ No | ✅ Yes — all evaluation data is wiped |
| Visible to fleet managers | ✅ Yes | ❌ No |
| Counts toward real compliance | ✅ Yes | ❌ No |

### When to use Evaluation Mode

- **Training new drivers** — Let them practise without affecting real records
- **Demonstrating the app** to potential customers
- **Testing** clock-on/off flows during onboarding
- **Familiarising yourself** with the app before your first real shift

> **⚠️ Important:** Evaluation mode shifts are **completely local**. They are never uploaded to the server and are deleted when you log out. They do **not** count as real work diary entries.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 9. The On-Shift Dashboard

This is the screen you'll spend most of your time on while driving. It gives you everything you need at a glance.

### Screen layout

**Top Section — Driver Header**
- Your name and driver ID
- Status badge showing current state (Working / Resting)
- Current vehicle registration

**Centre — Countdown Timer Ring**
- A large animated ring showing **time remaining before your next mandatory rest**
- Colour changes as you approach limits:
  - 🟢 **Green** — Plenty of time remaining
  - 🟡 **Yellow/Orange** — Approaching limit (warning zone)
  - 🔴 **Red** — At or past limit (breach)

**Stats Grid (2×3)**
- **Work Time** — Total work in the current 24-hour rolling window
- **Next Break In** — Time until mandatory rest (shown as an absolute clock time, e.g., "2:45 PM")
- **Rest Remaining** — How much more rest you still need in this window
- **Night Stats** — Night work information (for BFM rulesets)
- **Shift Duration** — How long since you clocked on
- **Breaches** — Count of current breaches (tapping this goes to the Compliance tab)

**Bottom — Work/Rest Toggle**
- A **slide toggle** to switch between Work and Rest
- **End Shift** button to clock off

### Bottom Navigation (3 tabs)

While on shift, you have three tabs:

| Tab | Icon | What it shows |
|---|---|---|
| **Work** | 🛠️ | The On-Shift Dashboard (this screen) |
| **Compliance** | 📊 | Full compliance breakdown by period |
| **Profile** | 👤 | Your driver profile details |

### Timer updates

- The **visual countdown ring** updates every **1 second** for smooth animation
- The **full compliance calculation** runs every **60 seconds** to keep stats accurate
- Stats refresh every **10 seconds** while you're on the home page

[↑ Back to Table of Contents](#-table-of-contents)

---

## 10. Switching Between Work and Rest

The most common action you'll take during a shift is switching between **Work** and **Rest**.

### How to switch

1. On the On-Shift Dashboard, use the **Work/Rest slide toggle** at the bottom
2. Slide from Work → Rest when you're stopping for a break
3. Slide from Rest → Work when you're resuming driving/duties

### What happens when you switch

Each switch automatically records:
- ⏰ **Timestamp** (precise to the minute, per NHVR Section 6.1c)
- 📍 **GPS location** (latitude/longitude, auto-captured per NHVR Section 7.1)
- 📦 **Odometer reading** (prompted when switching to Rest)
- 🚗 **Vehicle registration** (current vehicle)

### Odometer prompt

When switching from **Work to Rest**, you'll be prompted to enter your current **odometer reading**. This records the distance travelled during the work period (per NHVR Section 8.1 — 1km precision).

### Rest time rules

> **💡 Good to know:** Under NHVR rules, only rest periods of **15 minutes or longer** count toward your rest requirements. Short breaks under 15 minutes are recorded but don't count as qualifying rest.

### Rest guidance

While resting, the dashboard shows:
- Whether this rest period is **mandatory** or **voluntary**
- A **countdown** to when you'll have accumulated enough qualifying rest
- Which rest requirement this break is satisfying

[↑ Back to Table of Contents](#-table-of-contents)

---

## 11. Changing Vehicles Mid-Shift

If you need to switch to a different vehicle during your shift (e.g., vehicle swap, breakdown), you can do this without ending your shift.

### How to change vehicles

1. The app will prompt you during certain status changes, or you can trigger it manually
2. Enter the **new vehicle registration**
3. Enter the **new odometer reading**
4. The change is recorded as a new event with the updated vehicle details

> **💡 Note:** All subsequent events will be recorded against the new vehicle registration until you change it again or end your shift.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 12. Understanding the Countdown Timer

The **Countdown Timer Ring** is the most prominent feature on the On-Shift Dashboard. Here's how to read it:

### What it shows

The ring displays the **time remaining before you must take a rest break** to stay compliant with your current fatigue ruleset.

### Colour coding

| Colour | Meaning | Action |
|---|---|---|
| 🟢 Green | Well within limits | Continue working normally |
| 🟡 Yellow | Approaching limit (>80% used) | Plan your next rest break soon |
| 🟠 Orange | Close to limit | Take a break as soon as safely possible |
| 🔴 Red | At or past limit | You are in breach — stop and rest immediately |

### Multiple periods

The timer shows the **most urgent** limit across all rolling windows. For example, under Standard Solo Heavy Vehicle:
- 5h 30min continuous work limit
- 12h work in 24h limit
- 72h work in 7-day limit
- 144h work in 14-day limit

The countdown will show whichever limit you'll hit first.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 13. Breach Warnings & Notifications

ZuTapp actively warns you when you're approaching or have exceeded fatigue limits.

### In-app warnings

- **Breach banner** on the On-Shift Dashboard when any breach is active
- **Compliance tab** badge shows breach count
- **Warning dialog** at clock-on if you have existing breaches from prior shifts

### Background notifications (3-layer system)

Even when the app is in the background or the screen is off, ZuTapp monitors your compliance:

1. **Foreground Service** (Android) — Continuous monitoring while your shift is active
2. **Scheduled Alarms** — Alerts set for specific times when you'll approach breach thresholds
3. **Periodic Background Check** — Fallback check via WorkManager (runs periodically)

### Audio alerts

- **Text-to-Speech (TTS) alerts** are triggered when you're approaching a breach
- TTS alerts are **automatically suppressed** when you're in Rest mode (so they don't wake you)

### Breach acknowledgment

When a breach is detected mid-shift:
1. A dialog appears notifying you of the breach
2. You must **acknowledge** the breach
3. You may be asked to provide a **reason** for the breach
4. The acknowledgment is recorded with a timestamp for audit purposes

[↑ Back to Table of Contents](#-table-of-contents)

---

## 14. Clocking Off — Ending Your Shift

Ending your shift is a **two-step process** to ensure accuracy and legal compliance.

### Step 1: Shift Review

- A **chronological timeline** of all your work/rest events during the shift
- **Summary strip** showing totals: Work Time, Rest Time, Shift Duration
- You can **edit, add, or delete events** if corrections are needed
  - Adding a historic event (e.g., you forgot to switch to Rest)
  - Editing an event's times or location
  - Deleting an incorrect event
- All changes are **audit-logged** — the original data is preserved alongside any edits
- Instructional text explains that all changes are recorded for NHVR compliance

### Step 2: Legal Declaration

After reviewing your events, you must confirm:

> *"I declare that the entries in this work diary are true and correct."*

This screen shows:
- The full NHVR-required declaration text
- Your shift summary details
- Information about your next required rest period

**Authentication is required to submit:**
- 🔐 **Biometric** (fingerprint/face) — preferred method
- 🔑 **Password fallback** — if biometric is unavailable

Once confirmed, your shift is finalised and synced to the server.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 15. Compliance Dashboard

The Compliance Dashboard gives you a **period-by-period breakdown** of your fatigue compliance status.

### How to access it

- While on shift: tap the **Compliance tab** (middle tab in bottom navigation)
- From the EWD Home Page: tap **Compliance View** in the pages list

### What you'll see

**Current / Lapsed Toggle** — Switch between:
- **Current** — Active rolling windows with live data
- **Lapsed** — Historical periods that have already passed

**Per-Period Compliance Cards** showing for each rolling window:
- **Period label** (e.g., "24 Hours", "7 Days", "14 Days")
- **Work time** used vs. maximum allowed (e.g., "8h 30m / 12h 00m")
- **Rest status** — whether rest requirements are met
- **Breach severity** (if any) with colour coding
- **Requirement breakdown** — detailed list of each rest/break requirement and its status

### Auto-refresh

The compliance dashboard **auto-refreshes every 60 seconds** while you're viewing it. It also triggers a sync with the server when you open the page.

### Quick links

From the Compliance Dashboard, you can navigate to:
- **Breach History** — View past breach acknowledgments
- **Recovery Plan** — See what rest you need to clear breaches

[↑ Back to Table of Contents](#-table-of-contents)

---

## 16. Understanding Breach Levels

NHVR fatigue breaches are classified into **four severity levels**, with increasing penalties:

| Level | Severity | Example (Standard Solo HV, 24h period) | Consequence |
|---|---|---|---|
| 🟡 **Minor** | Slightly over limit | >12h work but ≤13h 15m | On-the-spot fine |
| 🟠 **Substantial** | Moderately over limit | >13h 15m work but ≤13h 30m | Higher fine |
| 🔴 **Severe** | Significantly over limit | >13h 30m work but ≤14h | Court prosecution possible |
| ⛔ **Critical** | Dangerously over limit | >14h work | Immediate licence action |

> **💡 Note:** Breach levels apply to **both work limits AND rest requirements**. You can breach by working too much OR by not resting enough.

### The EWD 8-Minute Provision

NHVR rules include an **8-minute grace period** (sometimes called "no-breach threshold"). If you exceed a work limit by 8 minutes or less, it may not be classified as a breach. This accounts for the fact that EWDs count time in 1-minute periods rounded to the last full minute.

### Lapsed Periods

A period is **lapsed** when its rolling window has passed and the compliance result is now historical. Lapsed periods are still visible in the Compliance Dashboard under the "Lapsed" toggle, and they still appear on roadside inspection views.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 17. Recovery Plan — Getting Back to Compliant

If you have active breaches, the **Recovery Plan** tells you exactly what rest you need to clear them.

### How to access it

From the Compliance Dashboard, tap **Recovery Plan**.

### What it shows

For each breached period:
- **Breach severity** and description
- **Required continuous rest** to clear the breach (e.g., "You need 7 hours continuous stationary rest")
- **Live countdown timer** showing time remaining until you've rested enough
- **Plan-specific explanations** of why this rest duration is required

### How the countdown works

- The timer **refreshes every 30 seconds**
- Once you've accumulated enough qualifying rest, the breach clears automatically
- The recovery plan updates in real-time as you rest

[↑ Back to Table of Contents](#-table-of-contents)

---

## 18. Breach History

The Breach History page shows a **read-only log** of all your breach acknowledgments from the past 28 days.

### What each entry shows

- **Timestamp** of when the breach was acknowledged
- **Severity** (Minor / Substantial / Severe / Critical)
- **Type** (Work breach or Rest breach)
- **Affected periods** (which rolling window was breached)
- **Driver's reason** (what you provided when acknowledging)
- **Context** (whether it occurred at clock-on or mid-shift)

> **💡 Note:** This is a read-only log. Breach acknowledgments cannot be edited or deleted.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 19. Compliance Lock Mode — Roadside Inspection

When an **NHVR Authorised Officer** (or Police officer conducting a heavy vehicle inspection) pulls you over, you can put the app into **Compliance Lock Mode**. This is a secure, read-only mode designed specifically for roadside inspections.

### How to enter Compliance Lock Mode

1. From the EWD Home Page, tap **Compliance View**
2. Or navigate to the compliance screen and tap the **Lock Mode** button
3. The app enters a locked, read-only kiosk mode

### What happens when Lock Mode activates

**On Android:**
- The app uses **Screen Pinning** to lock the device to the ZuTapp app
- The home button, app switcher, and notification shade are **disabled**
- The officer can only navigate within the approved EWD compliance screens
- You'll see a one-time OS confirmation prompt the first time

**On iOS:**
- The back gesture is blocked
- Exit requires biometric/password authentication
- The home gesture still works (iOS limitation without MDM), but the lock page persists when you return to the app

### While in Lock Mode

- ✅ Work/rest tracking **continues in the background** — your shift isn't interrupted
- ✅ The officer can browse all compliance views freely
- ❌ No data can be **edited or deleted** (read-only mode, per NHVR Section 26.5)
- ❌ Only the **logged-in driver's** data is shown (per NHVR Section 26.3)

### How to exit Lock Mode

**On Android:**
- Press and hold the Back and Recent buttons together (OS screen unpin gesture)
- The device lock screen appears (PIN/pattern/password) to verify it's the driver

**On iOS:**
- Tap the exit/unlock button on screen
- Authenticate with **biometric (fingerprint/face)** or **password**

### ✨ Step-by-step: What to do when pulled over

1. 🚛 Pull over safely as directed
2. 📱 Open ZuTapp and go to **EWD Home Page**
3. 🔒 Tap **Compliance Lock Mode** to secure the app
4. 🧑‍⚖️ Hand your device to the authorised officer
5. ⏳ The officer reviews your records (your shift continues tracking)
6. 🔓 When returned, exit lock mode with your biometric/password
7. ✅ Continue your shift normally

[↑ Back to Table of Contents](#-table-of-contents)

---

## 20. What an Authorised Officer Can See

In Compliance Lock Mode, the officer has access to **six views**, all read-only:

| View | What it shows | NHVR Section |
|---|---|---|
| **Compliance Dashboard** | Period-by-period compliance status | Section 16.1 |
| **Graphical View** | 24-hour timeline chart (past 28 days) | Section 29.1 |
| **Tabular View** | Event table with all details | Section 30.1 |
| **Annotations** | Officer notes and intercept records | Section 32.1 |
| **Report Transfer** | Generate and email PDF reports | Section 33-35 |
| **Driver Details** | Driver profile and EWD system info | Section 27.1 |

The officer can swipe through the **past 28 days** in both Graphical and Tabular views.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 21. Annotations — Officer Notes

Annotations are notes attached to your work diary by an **authorised officer** during an inspection.

### Creating an annotation

From Compliance Lock Mode or the Annotations page:
1. Tap **Create Annotation**
2. Enter the **flag time** (the time being investigated — can be any time in the past 28 days)
3. Enter the **intercept time** (when the inspection is happening)
4. Enter the **location** of the inspection
5. Enter the **annotation text** (the officer's notes)

### Important rules

- Annotations are **non-editable** once committed (per NHVR Section 32.2)
- They are **synced to the server** for permanent record keeping
- They appear in both the Annotations page and the Graphical View timeline
- Existing annotations are displayed in a **tabular list** format

[↑ Back to Table of Contents](#-table-of-contents)

---

## 22. Graphical View (24-Hour Timeline)

The Graphical View displays your work/rest activity as a **visual 24-hour timeline chart**, following the exact format specified by the NHVR EWD Standards (Section 29.1).

### Layout

The chart shows a grid with hours **0–24** across the top and the following rows:

| Row | What it shows |
|---|---|
| **Annotations** | Officer annotation markers |
| **Comments** | Event comments |
| **Location** | Location names at each work/rest change |
| **Hours** | 0-24 hour labels |
| **2-Up** | 2-Up driver indicator (when applicable) |
| **Work** | Work periods shown as filled blocks |
| **Rest** | Rest periods shown as filled blocks |

### Features

- **Step-line boundaries** clearly show work/rest transitions
- **Total Work / Total Rest** summary displayed at the bottom
- **Swipe left/right** to navigate through the past **28 days**
- **Landscape rotation** supported for a wider timeline view
- **Switch to Tabular View** button for a different perspective

### NHVR-style presentation

The chart uses the official NHVR blue border styling and grid format. This is the same format that authorised officers expect to see during roadside inspections.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 23. Tabular View (Event Table)

The Tabular View shows your work/rest events as a **detailed table** (per NHVR Section 30.1).

### Table columns

| Column | Description |
|---|---|
| **Activity** | Work or Rest |
| **Time** | Start time of the event |
| **Location** | Where the event occurred |
| **Odometer** | Odometer reading at the time |
| **Registration** | Vehicle rego |
| **Work Option** | Fatigue ruleset in use |
| **Comments** | Any comments added by the driver |
| **Origin** | How the event was created (EWD / Historic / External / Review) |
| **Entry Timestamp** | When the entry was recorded in the system |

### Features

- Events displayed in **reverse chronological** order (newest first)
- **Day navigation** — swipe through the past 28 days
- **Landscape rotation** supported for better readability
- **Switch to Graphical View** button

### Event origin types

| Origin | Meaning |
|---|---|
| **EWD** | Recorded in real-time by the app |
| **Historic** | Added retroactively by the driver (e.g., during shift review) |
| **External** | Imported from another source |
| **REVIEW** | Modified during shift review/clock-off |

[↑ Back to Table of Contents](#-table-of-contents)

---

## 24. Work Diary History (28-Day Log)

The Work Diary History shows a **day-by-day summary** of your work and rest activity for the past 28 days.

### What you'll see

For each day:
- **Date** 
- **Total work time** for that day
- **Total rest time** for that day
- **Compliance badge** — colour-coded indicator of compliance status

### Drill-down: Day Detail

Tap any day to open the **Day Detail Page**, which shows:
- **Summary header** with work/rest totals
- **Segmented timeline bar** — a visual strip showing work/rest periods proportionally
- **Chronological event cards** — each event with time, type, location, and details
- Tap any event card to open the **Event Detail Sheet** (bottom sheet) with full event information

[↑ Back to Table of Contents](#-table-of-contents)

---

## 25. Report Transfer — PDF Export & Email

The Report Transfer feature generates **NHVR-compliant PDF reports** of your work diary records (per NHVR Sections 33-35).

### What the report contains

- **Driver details** — name, ID, licence info
- **EWD system details** — app name, version, provider
- **28 graphical day views** — one 24-hour chart per day
- **Tabular data** — full event listing

### Security features

The PDF is packaged in a **ZIP file** with:
- **MD5 checksum** for tamper detection (per NHVR Section 34.1)
- Cryptographic verification that the report hasn't been modified

### How to generate and send

1. From the EWD Home Page, tap **Report Transfer**
2. Choose your **date range** (up to 28 days)
3. Preview the PDF using the built-in viewer
4. Tap **Share** to send via:
   - ✉️ **Email** — directly from the app
   - 📱 **Native share sheet** — use any sharing method on your device (AirDrop, messaging apps, etc.)

### When to use Report Transfer

- **Daily transfer** — NHVR requires records to be transferred daily when possible (Section 19.1)
- **Roadside inspection** — An officer may request a report transfer
- **Fleet management** — Send records to your transport manager
- **Record keeping** — Keep a backup copy of your records

> **💡 Tip:** If connectivity is unavailable, the report is stored locally and can be sent later. The app retries every 15 minutes (per NHVR Section 19.3).

[↑ Back to Table of Contents](#-table-of-contents)

---

## 26. Offline-First — How Your Data Stays Safe

ZuTapp's EWD is built with an **offline-first architecture**. This means your data is always safe, even without an internet connection.

### How it works

1. **Every action is saved locally first** — All work/rest events, shifts, and compliance data are written to an SQLite database on your device immediately
2. **Zero data loss on crash** — Even if the app crashes or your phone dies, your data is already persisted locally
3. **28 days retained locally** — Your device stores a full 28-day rolling window of work diary records
4. **Sync happens in the background** — When connectivity is available, data syncs to the cloud automatically

### What this means for you

- ✅ You can **start, run, and end shifts** with no internet connection
- ✅ **Compliance calculations** work entirely offline
- ✅ **Roadside inspections** work offline — all data is on your device
- ✅ **PDF reports** can be generated offline
- ✅ Your data **syncs automatically** when you're back online

> **💡 Tip:** You don't need to do anything special to use the app offline. It just works. When you get signal again, the app syncs in the background.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 27. Sync & Communications Failure

### How sync works

The app uses **bi-directional sync**:
- **Push** — Your local data is uploaded to the server (shifts, events, annotations, profile)
- **Pull** — Server data is downloaded to your device (driver profile, timezone data, shift history)

### Sync order

Data is synced in this priority order:
1. Start shift
2. End shift
3. Edit event
4. Delete event
5. End event
6. Start event
7. Add event
8. Annotations
9. Driver profile

### Smart retry

If sync fails, the app retries with **increasing intervals**:
- First retry: **1 minute**
- Second retry: **5 minutes**
- Subsequent retries: **15 minutes** (capped)

### Communications failure handling

Per NHVR Section 9.1(c), the app tracks how long communications have been unavailable:
- **Under 24 hours** — Warning indicator shown
- **Over 24 hours** — Critical alert shown

The app continues to function normally during communications failures. All data is stored locally and will sync when connectivity returns.

### What doesn't sync

- **Evaluation mode shifts** — These are local-only and never sync (by design)
- **Synced records** are kept locally (not deleted after sync) for offline access

[↑ Back to Table of Contents](#-table-of-contents)

---

## 28. Pre-Shift Vehicle Walkaround

If your organisation uses ZuTapp's **Vehicle Walkaround** module, it integrates seamlessly with the EWD.

### How the integration works

1. **Start your walkaround** — A background EWD timer starts automatically
2. **Complete your checklist** — The app captures your vehicle rego and odometer during the walkaround
3. **Finish the walkaround** — You're prompted to clock on to EWD
4. **Clock on with pre-filled data** — Vehicle rego, odometer, and start time are automatically filled in

### Key details

- Your **shift start time is backdated** to when the walkaround began (since the walkaround is work activity)
- The vehicle **registration is extracted** from the walkaround tag/checklist name
- The **odometer reading** is captured during walkaround tasks
- The background timer **persists across app crashes** (saved in SharedPreferences)
- Stale timers (>24 hours old) are **automatically discarded**

> **💡 Note:** This integration requires the `walkaroundEwdIntegration` feature flag to be enabled for your organisation.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 29. EWD Admin Tools (Internal)

> **⚠️ Internal use only** — This section is for ZuTapp internal teams and authorised administrators. Admin tools are protected by a **PIN code**.

The EWD Admin page provides four sections for testing, debugging, and data management:

### 1. NHVR Algorithm Tests

- Runs the full **83-scenario NHVR compliance test suite** against all 5 fatigue rulesets
- Displays **pass/fail** per test with expected vs. actual breach levels
- Used to verify that the compliance engine matches NHVR reference data exactly

### 2. Logs Viewer

- Browse timestamped **EWD diagnostic logs**
- Events logged: shift starts/ends, event changes, compliance evaluations, sync operations
- **Clear** all logs or **export** them to a file for support/debugging

### 3. Database Explorer

- Browse all **EWD database tables** directly
- View individual rows and their data
- Execute **raw SQL queries** for advanced debugging
- Tables include: shifts, events, rulesets, annotations, breach acknowledgments, compliance snapshots, diagnostic logs, notification logs, fit-to-drive declarations

### 4. Seed Data Generator

- Generate **realistic test data** with configurable parameters:
  - **Date range** — How many days of history to create
  - **Ruleset** — Which fatigue plan to use
  - **Scenario** — Choose from 7 presets:
    - Clean Run (no breaches)
    - One Minor Breach
    - Multiple Minor Breaches
    - Escalating Breaches
    - Critical Breach
    - Mixed Severity
    - Heavy Work Pattern
  - **Sync options** — Whether to mark data as synced or pending

[↑ Back to Table of Contents](#-table-of-contents)

---

## 30. NHVR Fatigue Rulesets — Full Reference

Below is a summary of the work/rest limits for each of the five supported NHVR fatigue rulesets.

### RSID 1: Standard Hours — Solo Driver, Heavy Vehicle

| Period | Max Work | Min Rest Requirements |
|---|---|---|
| 5h 30m | 5h 15m continuous | 15 min continuous rest |
| 8h 00m | 7h 45m | 2 × 15 min rest blocks |
| 11h 00m | 10h 45m | 3 × 15 min rest blocks |
| 24 hours | 12h 00m | 7h continuous rest |
| 7 days | 72h 00m | 24h continuous rest (in any 7-day window) |
| 14 days | 144h 00m | 2 × night rests + 2 × consecutive night rests |

### RSID 2: Standard Hours — Solo Driver, Bus

| Period | Max Work | Min Rest Requirements |
|---|---|---|
| 5h 30m | 5h 15m continuous | 15 min continuous rest |
| 8h 00m | 7h 45m | 2 × 15 min rest blocks |
| 11h 00m | 10h 45m | 3 × 15 min rest blocks |
| 24 hours | 12h 00m | 7h continuous rest |
| 7 days | 72h 00m | 24h continuous rest |
| 28 days | 288h 00m | 6 × night rests (22:00-08:00, min 7h) |

### RSID 3: Standard Hours — 2-Up Driver, Heavy Vehicle

| Period | Max Work | Min Rest Requirements |
|---|---|---|
| 5h 30m | 5h 15m continuous | 15 min continuous rest |
| 24 hours | 12h 00m | 7h rest (sleeper berth while moving allowed) |
| 7 days | 60h 00m | 24h continuous stationary rest |
| 14 days | 120h 00m | 52h rest window |

### RSID 4: BFM Hours — Solo Driver, Heavy Vehicle

| Period | Max Work | Min Rest Requirements |
|---|---|---|
| 6h 15m | 6h 00m continuous | 15 min continuous rest |
| 9h 00m | 8h 45m | 2 × 15 min rest blocks |
| 12h 00m | 11h 45m | 3 × 15 min rest blocks |
| 24 hours | 14h 00m | 7h continuous rest |
| 7 days (long/night) | 36h 00m | Night rest requirements |
| 14 days | 144h 00m | BFM rest requirements |
| 84h time limit | — | Must have qualifying reset within 84h |

### RSID 5: BFM Hours — 2-Up Driver, Heavy Vehicle

| Period | Max Work | Min Rest Requirements |
|---|---|---|
| 24 hours | 14h 00m | 7h rest (sleeper berth while moving allowed) |
| 7 days | 70h 00m | 24h continuous stationary rest |
| 14 days | 140h 00m | 82h rest window |

> **⚠️ Disclaimer:** These tables are simplified summaries. The full ruleset definitions include detailed breach thresholds (Minor/Substantial/Severe/Critical), night rest definitions, and special provisions. Always refer to the official NHVR documentation for authoritative fatigue rules.

[↑ Back to Table of Contents](#-table-of-contents)

---

## 31. Glossary of Terms

| Term | Definition |
|---|---|
| **EWD** | Electronic Work Diary — a digital replacement for paper work diaries |
| **NHVR** | National Heavy Vehicle Regulator — the body that regulates heavy vehicle operations in Australia |
| **Authorised Officer** | An NHVR-authorised or police officer who can inspect work diaries at roadside |
| **Fatigue Ruleset** | A set of NHVR-defined rules specifying maximum work hours and minimum rest requirements |
| **RSID** | Ruleset ID — the identifier for a specific fatigue ruleset (1-5) |
| **BFM** | Basic Fatigue Management — an accreditation allowing extended driving hours with additional requirements |
| **2-Up** | Two-up driving — when two drivers share driving duties on the same vehicle |
| **Rolling Window** | A moving time period (e.g., "the last 24 hours") used to calculate compliance |
| **Breach** | A violation of fatigue rules — working too much or resting too little |
| **Compliance Lock Mode** | A locked, read-only mode for showing records to authorised officers |
| **Screen Pinning** | An Android feature that locks the device to a single app |
| **Evaluation Mode** | A training/demo mode where shifts are local-only and never synced |
| **Stale Shift** | A shift that has been running for more than 24 hours without being ended |
| **Fit to Drive** | A mandatory pre-shift declaration confirming the driver is fit for duty |
| **Annotation** | A note added by an authorised officer during a roadside inspection |
| **Work Event** | A recorded period where the driver is performing work duties |
| **Rest Event** | A recorded period where the driver is resting |
| **Qualifying Rest** | A rest period of 15 minutes or longer that counts toward rest requirements |
| **Night Rest** | A rest period between 22:00 and 08:00 of at least 7 hours |
| **Continuous Rest** | An uninterrupted rest period (not broken by work periods) |
| **Stationary Rest** | Rest taken while the vehicle is stationary (required for some rules) |
| **Odometer** | The vehicle's distance meter, recorded to 1km precision |
| **GVM** | Gross Vehicle Mass — the maximum loaded weight of a vehicle |
| **Lapsed Period** | A compliance period whose rolling window has already passed |
| **Recovery Plan** | A plan showing what rest is needed to clear active breaches |
| **Report Transfer** | Generating and sending a PDF copy of work diary records |
| **Countdown Ring** | The animated circular timer showing time until mandatory rest |
| **Origin** | How an event was created: EWD (real-time), Historic (added later), External, or Review |
| **Sync** | The process of uploading local data to the cloud server |
| **Walkaround** | A pre-trip vehicle inspection checklist |

[↑ Back to Table of Contents](#-table-of-contents)

---

## 32. Frequently Asked Questions (FAQ)

### Getting Started

<details>
<summary><strong>Q: How do I start using the EWD for the first time?</strong></summary>

1. Open ZuTapp and navigate to the **EWD** module
2. Complete your **Driver Profile** (all fields are mandatory)
3. Set your **default fatigue ruleset** in Fatigue Settings
4. When ready to start a shift, tap **Start Shift**
5. Complete the **Fit to Drive Declaration** (all 6 items)
6. Fill in your **Clock-On details** (vehicle rego, odometer, location)
7. Tap **Clock On** — you're now on shift!
</details>

<details>
<summary><strong>Q: Do I need an internet connection to use the EWD?</strong></summary>

**No.** ZuTapp's EWD works entirely offline. All data is saved to your device immediately. When you have internet, the app syncs in the background automatically. You can start shifts, switch between work and rest, end shifts, view compliance, and even generate PDF reports — all without any internet connection.
</details>

<details>
<summary><strong>Q: Which fatigue ruleset should I choose?</strong></summary>

This depends on your vehicle type, driving arrangement, and accreditation:
- **Solo truck drivers**: RSID 1 (Standard) or RSID 4 (BFM)
- **Solo bus drivers**: RSID 2 (Standard Solo Bus)
- **Two-up drivers**: RSID 3 (Standard 2-Up) or RSID 5 (BFM 2-Up)
- **BFM rulesets** require your company to hold Basic Fatigue Management accreditation

If unsure, ask your fleet manager or transport coordinator.
</details>

### During a Shift

<details>
<summary><strong>Q: I forgot to switch to Rest when I took a break. What do I do?</strong></summary>

You can fix this during the **Shift Review** step when clocking off:
1. Tap **End Shift** on the dashboard
2. In the Shift Review screen, tap **Add Event**
3. Add a historic Rest event with the correct start and end times
4. All corrections are audit-logged for NHVR compliance

You can also add historic events at any time during your shift.
</details>

<details>
<summary><strong>Q: What is a "stale shift"?</strong></summary>

A **stale shift** is one that has been running for more than **24 hours** without being clocked off. If the app detects a stale shift, it will show a dialog with two options:
1. **End the shift and start a new one** — Ends the old shift and lets you start fresh
2. **Continue the current shift** — If the shift is genuinely still active

Stale shifts usually happen when a driver forgets to clock off. The app detects this automatically.
</details>

<details>
<summary><strong>Q: Can I change my vehicle registration mid-shift?</strong></summary>

**Yes.** If you switch vehicles (e.g., breakdown, vehicle swap), the app allows you to enter a new registration and odometer reading without ending your shift. All subsequent events will be recorded against the new vehicle.
</details>

<details>
<summary><strong>Q: What does the countdown timer ring show?</strong></summary>

The ring shows the **time remaining before you must take a rest break**. It considers all rolling windows in your fatigue ruleset and displays the most urgent limit. Colour coding: Green = safe, Yellow = approaching limit, Orange = close, Red = at or past limit (breach).
</details>

<details>
<summary><strong>Q: Will the app alert me if I'm about to breach?</strong></summary>

**Yes.** ZuTapp uses a 3-layer notification system:
1. In-app visual warnings and banners
2. Background push notifications (even when the app is closed)
3. Text-to-Speech audio alerts (suppressed when resting so they don't wake you)

You'll be warned before reaching a breach threshold.
</details>

<details>
<summary><strong>Q: Do short breaks (under 15 minutes) count as rest?</strong></summary>

**No.** Under NHVR rules, only rest periods of **15 minutes or longer** qualify toward your rest requirements. Shorter breaks are still recorded in your work diary but don't count as qualifying rest.
</details>

### Compliance & Breaches

<details>
<summary><strong>Q: What happens if I breach a fatigue rule?</strong></summary>

If a breach is detected:
1. You'll see a **notification** and an in-app alert
2. You must **acknowledge** the breach
3. You may need to provide a **reason** for the breach
4. The breach is **recorded permanently** in your breach history
5. The **Recovery Plan** will show you how much rest you need to become compliant again

Breaches have legal consequences — from on-the-spot fines (Minor) to immediate licence action (Critical).
</details>

<details>
<summary><strong>Q: What is the "8-minute provision"?</strong></summary>

The NHVR EWD standards include an **8-minute grace period** (also called the "no-breach threshold"). Because EWDs count time in 1-minute periods rounded down to the last full minute, exceeding a work limit by up to 8 minutes may not trigger a formal breach. This provision exists to account for the inherent imprecision of minute-level time tracking.
</details>

<details>
<summary><strong>Q: What does "lapsed" mean in the compliance view?</strong></summary>

A **lapsed** period is a rolling window that has already passed. For example, if you're looking at a 24-hour window that ended 6 hours ago, it's lapsed. Lapsed periods still show their compliance results and are visible during roadside inspections, but they can't change (they're historical).
</details>

<details>
<summary><strong>Q: How do I clear a breach?</strong></summary>

Go to the **Recovery Plan** (from Compliance Dashboard u2192 Recovery Plan). It will tell you exactly how much **continuous rest** you need to clear each breach. The countdown timer shows your progress in real-time. Once you've rested enough, the breach clears automatically.
</details>

### Roadside Inspections

<details>
<summary><strong>Q: An officer has pulled me over. How do I show my EWD records?</strong></summary>

1. Open ZuTapp and go to **EWD Home Page**
2. Tap **Compliance Lock Mode** (or look for the lock/shield icon)
3. The app enters a secure, locked mode
4. Hand your device to the officer
5. They can browse your compliance, graphical view, tabular view, annotations, reports, and driver details
6. Your shift continues tracking in the background
7. When returned, exit lock mode with your biometric/password
</details>

<details>
<summary><strong>Q: Can the officer change my records?</strong></summary>

**No.** Compliance Lock Mode is **read-only** (per NHVR Section 26.5). The officer can view all your records but cannot edit or delete anything. The only thing they can do is add **annotations** (officer notes), which become a permanent part of your record.
</details>

<details>
<summary><strong>Q: Can the officer see other drivers' data on my device?</strong></summary>

**No.** Per NHVR Section 26.3, only the **currently logged-in driver's** data is shown in Compliance Lock Mode.
</details>

<details>
<summary><strong>Q: Can the officer leave the EWD app while in Lock Mode?</strong></summary>

**On Android:** No — Screen Pinning disables the home button, app switcher, and notifications. They are locked to the ZuTapp compliance screens.

**On iOS:** The home gesture still works (iOS doesn't support kiosk mode without MDM), but the lock page persists when they return to the app, and exiting requires biometric/password authentication.
</details>

<details>
<summary><strong>Q: What are annotations?</strong></summary>

**Annotations** are notes that an authorised officer adds to your work diary during a roadside inspection. They include:
- The **flag time** — the specific time period being investigated
- The **intercept time** — when the inspection occurred
- The **location** and **text** of the annotation

Once committed, annotations **cannot be edited or deleted** — they become a permanent part of your 28-day record.
</details>

### Reports & Data

<details>
<summary><strong>Q: How do I send my work diary records to my manager?</strong></summary>

1. Go to **Report Transfer** from the EWD Home Page
2. Select your date range
3. The app generates an NHVR-compliant PDF report
4. Tap Share to send via email or any sharing method on your device

The report includes graphical views, tabular data, driver details, and an MD5 checksum for tamper detection.
</details>

<details>
<summary><strong>Q: How far back can I see my records?</strong></summary>

**28 days** — the app maintains a rolling 28-day window of work diary records on your device, as required by NHVR standards.
</details>

<details>
<summary><strong>Q: What happens to my data when I log out?</strong></summary>

- **Normal shifts** — All synced data is preserved on the server. Local data remains on the device.
- **Evaluation mode shifts** — All evaluation data is **permanently deleted** from the device on logout.
</details>

### Evaluation Mode

<details>
<summary><strong>Q: What is Evaluation Mode?</strong></summary>

**Evaluation Mode** is a demo/training mode that lets you use the EWD without creating real records. Toggle it on the Clock-On screen before starting a shift. Evaluation shifts:
- Are **stored locally only** (never sent to the server)
- **Don't count** toward your real compliance
- **Don't trigger** background notifications
- Are **deleted** when you log out
- Are **invisible** to fleet managers

Use it for training, demos, or familiarisation.
</details>

<details>
<summary><strong>Q: Can I use Evaluation Mode during a real shift?</strong></summary>

**No.** Evaluation Mode must be selected before clocking on. You cannot switch a real shift to evaluation mode or vice versa. If you need to practise, end your real shift first, then start a new one in Evaluation Mode.
</details>

### Troubleshooting

<details>
<summary><strong>Q: The app says my shift is "stale" — what should I do?</strong></summary>

A stale shift has been running for more than 24 hours. This usually means you forgot to clock off. Choose **"End shift and start new"** to fix it. The stale shift will be ended at the current time, and you can start a fresh shift.
</details>

<details>
<summary><strong>Q: My location is showing incorrectly. Can I fix it?</strong></summary>

**Yes.** On the Clock-On screen, you can edit the auto-detected location name and add a custom suffix. The GPS coordinates are still recorded accurately — the editable field is just the display name.
</details>

<details>
<summary><strong>Q: The app isn't syncing my data. What should I check?</strong></summary>

1. **Check your internet connection** — WiFi or mobile data
2. **Check if you're in Evaluation Mode** — Evaluation shifts never sync (by design)
3. **Wait for automatic retry** — The app retries every 1-15 minutes
4. **Check the sync indicator** — A warning appears if comms have been down
5. **Try opening the Compliance Dashboard** — This triggers a manual sync

If sync issues persist, contact support.
</details>

<details>
<summary><strong>Q: I'm getting breach notifications while resting. How do I stop them?</strong></summary>

Make sure you've **switched to Rest mode** on the On-Shift Dashboard. TTS (audio) alerts are automatically suppressed while you're in Rest mode. If you're still getting notifications, ensure the Work/Rest toggle shows "Rest".
</details>

[↑ Back to Table of Contents](#-table-of-contents)

---

## 33. Support & Contact

For help with ZuTapp's EWD module:

- **In-app support** — Contact your fleet manager or transport coordinator
- **Technical support** — Reach out to the ZuTapp support team
- **NHVR information** — Visit [nhvr.gov.au](https://www.nhvr.gov.au) for official fatigue management information
- **Admin tools** — Internal teams can access the EWD Admin page for diagnostics and testing

---

<div align="center">

**ZuTapp EWD — Keeping drivers safe and compliant on every shift.**

*This document was generated from the ZuTapp EWD codebase analysis on 2026-04-16.*

*Version 1.0*

</div>

