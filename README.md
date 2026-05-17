# Fulcrum Health – PressW UX Assessment
**Submitted by:** Xio Santaella, Sr. UX Designer, PressW  
**Date:** 05/16/26

---

## Overview

This repository contains my submission for the PressW UX engagement assessment for Fulcrum Health. The brief provided eight days worth of real engagement artifacts: stakeholder emails, scheduler interviews, clinician field notes, an engineering memo, and a platform data dump. The task was to read them carefully, identify where the leverage is, and come back with a point of view.

---

## File

| File | Description |
|------|-------------|
| `pressw_submission.pdf` | Full submission: strategy memo and user stories |

---

## Part 1: Strategy Memo

A memo to Lena Whitford, CPO of Fulcrum Health. The position: fix the clinician mobile experience first, without touching the scheduler workflows currently protecting renewals.

Covers four areas:

**Discovery: First 30 Days**  
Three parallel workstreams with no dedicated researcher. Inside PressW, inside Fulcrum, and customer-side research through Aisha's team. Deliverables by day 30: a clinician friction map, a technical constraints brief, an account-risk assessment, and a prioritized Phase 1 recommendation.

**Where the Leverage Is**  
Mobile WAU is 38% against a 70% benchmark. NPS dropped from 42 in 2022 to 19 today. 64% of clinicians abandon the in-app swap and text the scheduler instead. The app fails on every action flow. The mobile app also runs on a separate API layer, meaning it can be redesigned without touching the rules engine.

**What to Redesign, Keep, and Cut**  
Redesign clinician mobile navigation, information hierarchy, and action flows. Keep the scheduler console untouched. Cut broad platform work and net-new features. 80 hospital systems with individual configurations is not a place to move fast.

**Risks and Unknowns**  
The problem may not be visual. The swap workflow has five config-dependent paths with invisible workarounds. Hard constraints include the login rebuild already in progress, the schedule grid being off limits, and ACGME rules at teaching hospital accounts. Clinician research access takes 2 to 3 weeks and requires account coordination.

---

## Part 2: User Stories

Five job stories for the clinician mobile workflow. Format: When / I want to / So I can.

| Story | User | Type |
|-------|------|------|
| 1. Checking schedule between patients | Clinician / Mobile | Core use case |
| 2. Requesting time off on mobile | Clinician / Mobile | Core use case |
| 3. Handling a same-day cancellation | Scheduler / Desktop | Retention workflow |
| 4. Swap approved but schedule unchanged | Clinician / Mobile | Unhappy path |
| 5. New clinician opening the app for the first time | Clinician / Mobile | Unhappy path |

Stories 4 and 5 are drawn directly from the interview transcripts. Story 4 is based on Maya's experience of showing up to a shift she thought she had swapped off. Story 5 is based on Marcus's observation that every new resident orientation requires a 20-minute app tutorial just to get started.

---

## Source Material Reviewed

- CPO intro email (Lena Whitford)
- CS Slack DM (Sam Ortega)
- Scheduler interview transcript (Renee Halloran, Mercy Regional)
- Scheduler interview transcript (Marcus, St. Bridget's)
- Clinician field notes (ED break room, Mercy Regional)
- Engineering memo (Tomas Reyes, VP Engineering)
- Platform data dump (compiled by Jules Park, PM)
