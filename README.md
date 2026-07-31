# CTF Student Learning Features

Collection of practical features to make Capture-The-Flag challenges more effective for students who are still learning.

## Core Features

### 1. Activity Log / Request History
Students can view a private chronological log of their own requests and actions (timestamp, method, status, short summary). Helps them understand what actually happened instead of guessing blindly.

### 2. Guided Mode vs Free Mode
- **Guided Mode**: Extra scaffolding, progressive hints, tooltips, and explanations.
- **Free Mode**: All guidance hidden for advanced students.
- Using Guided Mode or any hint automatically reduces the points awarded on solve.

### 3. Immediate Educational Feedback
Incorrect submissions return short, non-spoiling feedback (e.g. "Flag format correct but value wrong", "Endpoint requires authentication") instead of a generic error.

### 4. Partial Credit / Intermediate Flags
Award reduced points for reaching clear milestones before the final flag. Progress indicators show students they are advancing.

### 5. Post-Solve Write-up
After a correct flag is submitted, unlock a short official explanation of the intended path and key learning points.

### 6. Quality-of-Life
- Clean, high-contrast, mobile-friendly UI
- Persistent, always-visible flag submission box
- Optional informational timer (non-punitive)
- "Report issue" button for quick feedback on broken challenges

## Design Principles
- Keep feedback educational, not punitive
- Prefer progressive disclosure over information dump
- Point penalties for assistance should be transparent
- Everything must work well on mobile
- Server-side validation for all scoring and state

## Implementation Notes
These features are intentionally described at the specification level so they can be implemented in any CTF platform (CTFd, custom Flask/Django, etc.).

---
Generated from iterative design sessions focused on student learning outcomes.
