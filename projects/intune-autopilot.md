---
layout: default
title: Intune & Autopilot Migration
---

# Intune & Autopilot Migration (2025)
**Role:** Systems & Cybersecurity Specialist  
**Company Size:** 88 employees  
**Timeframe:** Apr–Aug 2025

## Problem
Aging Windows Server 2012 DC, inconsistent GPOs, no TPM 2.0 on some devices.

## Actions
- Designed AADJ strategy; Autopilot profiles (user-driven), device groups, ESP.
- Security baselines + custom hardening (BitLocker, WDAC, ASR rules).
- MDE onboarding (EDR policy), reporting, and alert tuning.
- Automated drive mapping for AADJ via PowerShell + Intune script.

## Outcome (KPIs)
- 80% reduction in provisioning time (90→18 mins).
- 100% encryption coverage; secure boot verified.
- MDE onboarded devices ↑ to 100%; alert-to-resolution time ↓ by 35%.

## Tech Stack
Windows Autopilot, Intune, Entra ID, MDE P1, BitLocker, PowerShell.

## Artifacts
- Architecture diagram (PNG)
- Intune JSON exports (policy summaries)
- PowerShell snippets (redacted)
