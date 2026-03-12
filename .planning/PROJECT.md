# KSFreePlayConferenceGuest

## What This Is

A participant-facing GitHub Pages site for the KeySteps@JC Free Play Case Conference (January 4, 2025). It is a simplified, read-only companion to the organizer site (KSFreePlayConference), tailored for conference attendees who have already arrived and need quick access to the programme, activity details, downloadable resources, and survey links.

## Core Value

Participants can quickly find what they need during the conference — the schedule, activity instructions, and survey links — without wading through organizer-only content.

## Requirements

### Validated

(None yet — ship to validate)

### Active

- [ ] Participant can view programme rundown / schedule
- [ ] Participant can view activity details (Activity 1 & 2)
- [ ] Participant can access downloadable resources (PowerPoint, guidelines)
- [ ] Participant can fill in pre-test survey
- [ ] Participant can fill in post-test survey
- [ ] Participant can join Google Classroom
- [ ] Navigation is simple and clear for non-technical conference attendees

### Out of Scope

- Transport/logistics info — participants have already arrived by the time this is shown
- Budget, reporting, tasks pages — organizer-only content
- Participants list — privacy concern, not needed by attendees
- Role selector — not relevant for a homogeneous participant audience

## Context

- Source site: `C:/Users/hkkchan/Downloads/KSFreePlayConference` (organizer planning platform)
- Target site: `C:/Users/hkkchan/Downloads/KSFreePlayConferenceGuest` (this project)
- Conference: KeySteps@JC Phase Two — Free Play Case Conference, January 4, 2025
- The source uses static HTML/CSS/JS with Inter font, Font Awesome icons, and vanilla JS
- Specific links to embed:
  - Google Classroom: https://qr.codes/KcWzCB
  - Pre-test: https://eduhk.au1.qualtrics.com/jfe/form/SV_1UgFScb9EjCdZPw
  - Programme PowerPoint: https://qr.link/2lBfdx
  - Guideline: https://qr.link/inG2Km
  - Post-test: https://eduhk.au1.qualtrics.com/jfe/form/SV_6sNQjkbijFtMiX4

## Constraints

- **Tech Stack**: Plain HTML/CSS/JS — must match the source site's stack (no build tools, no frameworks)
- **Hosting**: GitHub Pages — all paths must be relative, no server-side logic
- **Audience**: Conference participants, likely on mobile during the event

## Key Decisions

| Decision | Rationale | Outcome |
|----------|-----------|---------|
| Port from source rather than rebuild | Preserves styling consistency and reuses tested components | — Pending |
| Dedicated survey section on homepage | Surveys are a primary action; should be prominent, not buried | — Pending |
| Remove role selector | All users are participants; selector adds friction with no benefit | — Pending |

---
*Last updated: 2026-03-12 after initialization*
