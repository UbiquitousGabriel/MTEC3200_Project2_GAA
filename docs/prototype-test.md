# Prototype Test

**Prototype:** low-fidelity wireframes (`docs/wireframe-slides.html` / `docs/wireframes/`)
**Core flow tested:** a helper finds a nearby request, offers help, and contacts the person who asked
**Date:** YYYY-MM-DD · **Tester:** [code, e.g. T1 — classmate] · **Facilitator:** Gabriel A. Aguilar

---

## Test task (read aloud to the tester)

> You have a free hour this afternoon and want to use it to help someone in your neighborhood. Find a person close by who needs a hand today, and let them know you're on your way.

**Based on:** _[the interview this comes from — e.g. "P3 said they had a free afternoon and wanted to help but didn't know who needed it." Replace with the real situation from your notes.]_

**Done when:** the tester has sent a message to the person they chose to help.

### Task checklist (from Prof. Dora's slide)
- [x] Short scenario that gives the tester a goal
- [ ] Based on a real situation from an interview (fill in the line above)
- [x] Describes what to accomplish, not which buttons to press
- [x] Clear end point
- [x] Doesn't name a button, label, or screen (no "map," "swipe," "I can help," "chat," "send")

---

## Facilitator notes (don't show the tester)

**Expected path:**
1. Landing → Get started → Sign in
2. Map → tap a request circle marked "Today" → I can help
   _or_ Browse (swipe) → swipe right / Help on a request for today
3. Chat → type a message → Send ✅ end

**Before starting, say:**
"This is an early sketch of an app, not a finished product. I'm testing the design, not you. Please think out loud as you go. I won't be able to help, but you can stop at any time."

**During:** stay quiet, don't point, and allow silence. If they're stuck for over 60 seconds, ask: "What are you looking for?"

---

## Notes

### The task I gave
> You have a free hour this afternoon and want to use it to help someone in your neighborhood. Find a person close by who needs a hand today, and let them know you're on your way.

### Where they paused
-

### Where they tapped the wrong thing
-

### What they said out loud
_Paraphrased from the session — replace with their exact words if you wrote them down._
- The choice at the start ("I need help" / "I can help") felt like a **false choice**: both options led to the same place.
- They thought the design was **ugly**.
- They **didn't like the circles** as much as I do.
- They felt it **needs a lot more character**.

### Did they complete the task?
- [ ] Yes, without help
- [ ] Yes, with a hint (what hint: ___ )
- [ ] No (where they stopped: ___ )

**Path they took:**

### Changes I need to make
| What happened | Change to the design | Screen | Status |
|---|---|---|---|
| Tester called the "I need help" / "I can help" choice a false choice: both went to the same sign-up | Removed the two role buttons. Landing now has one action (Get started) and a short, non-clickable "How it works" list (ask, help, meet up safely). Everyone gets the same account and can both ask and help. | 1 · Landing | ✅ Done — `docs/wireframes/01-landing.png` |
| Tester found the look ugly and didn't connect with the circles | Revisit the visual direction before hi-fi: test circles as an accent (map, avatars, action buttons) instead of on every element, and get a second opinion from another tester | Visual design (all screens) | To do |
| Tester said it needs more character | Explore a personality for the brand — e.g. a real app name, an illustration style or mascot, warmer copy, a less generic palette — and compare 2–3 directions with testers | Visual design / brand | To do |
