# 848 Interview Preparation Tool

## Overview

A gamified, interactive learning webapp built to prepare for a technical interview under time constraints. Inspired by the effectiveness of spaced repetition and game mechanics (Duolingo-style learning), this tool transforms interview notes into an engaging study experience.

## The Problem

**Time constraint + information overload = poor retention.**

Preparing for a Service Desk interview with:
- 3 evenings available
- Extensive notes covering 8 key anchors + broader frameworks
- Need for reliable recall under pressure
- No existing tool designed for this specific workflow

Traditional cramming (reading notes repeatedly) is ineffective. Interview preparation needed a different approach.

## The Solution

An interactive, self-contained HTML webapp featuring:

- **9 interactive lessons** covering the 8 ITIL anchors + Golden Chain framework
- **Multiple question types**: multiple choice, scenario-based, personal rehearsal, and interactive sequence-building
- **Gamification mechanics**: XP rewards, streak tracking, progress visualization
- **Persistent local storage**: progress syncs to browser (no server needed)
- **Performance dashboard**: final review screen showing accuracy per lesson and overall mastery
- **Zero dependencies**: single HTML file, works offline, portable across devices

### Key Features

| Feature | Purpose |
|---------|---------|
| **XP + Streak System** | Psychological hooks to maintain engagement and consistency |
| **Progress Tracking** | Visual feedback on which anchors need more work (traffic-light review) |
| **Interactive Chain Builder** | Undo/clear buttons allow correction before submitting (better UX) |
| **Responsive Design** | Works on phone during commute, laptop at desk |
| **Persistent State** | Resume mid-lesson without losing progress |
| **Final Review Screen** | Comprehensive performance summary for post-interview reflection |

## The Outcome

- ✅ Improved retention through active recall + gamification
- ✅ Didn't need the crib sheet during interview
- ✅ Confident, thorough interview performance
- ✅ Technical demonstration embedded in preparation strategy

## Usage

1. Download `848-interview-prep.html`
2. Open in any modern browser
3. Work through lessons at your own pace
4. Progress is saved automatically (browser local storage)
5. Review final performance dashboard upon completion

## Technical Notes

- **Single HTML file**: All CSS and JavaScript embedded for portability
- **No external dependencies**: Runs completely offline
- **Browser storage**: Uses `localStorage` API for persistent state
- **Responsive**: Designed for mobile-first, works on any screen size
- **Clean commits**: See GitHub history for iteration and refinement

## Why This Approach?

**Time to value matters.** Building this took ~2 hours with Claude (focusing on the problem, not reinventing infrastructure). That time investment paid for itself within the first study session through improved retention.

**Constraints breed creativity.** Limited time to prepare led to a more efficient preparation method than traditional cramming.

**Tool fit matters.** Existing tools (flashcard apps, note-taking) weren't designed for this specific interview structure. Building a custom tool meant perfect alignment with actual needs.

## Lessons Learned

1. **Gamification works** – XP and streaks are psychological, but they're *effective* at maintaining consistency
2. **Flow matters** – removing friction (undo/clear buttons, responsive design) improved usability significantly
3. **Persistent progress** – knowing where you left off reduces friction to re-engagement
4. **Active recall > passive review** – multiple choice questions force thinking, not just reading

## Files

- `848-interview-prep.html` – Complete webapp (ready to use)
- `README.md` – This file

## License

Personal project. Feel free to fork/adapt for your own interview prep.

---

**Built by:** Sami  
**Purpose:** 848 Group Tier 1 Service Desk Interview Preparation  
**Status:** ✅ Complete and tested
