---
name: write-ux-invoice-line
description: Write a timesheet description line for the UX work done in this session.
disable-model-invocation: true
---

# Write UX Invoice Line

Turn the current working context into one timesheet description line, ready to paste into a time-tracking tool.

One line covers **one working context** — this session's work on this project. Several lines a day for the same project is normal. Meetings are billed elsewhere; this skill is for design and build work.

## Steps

1. **Gather the evidence.**
   - The conversation context — what was designed, prototyped, iterated on, evaluated, rejected. Exploration and discarded directions count: choosing between three approaches is the work.
   - `git log` and `git status` for this session's commits, to catch work done outside the narrative.
   - Anything the user typed after the command — design-tool work the session can't see.

   Done when you can name the primary UX decision made, not just the files touched.

2. **Name the decision.** The line's first clause states the UX decision or the thing designed — and, where there was one, what it replaced. This is the quality bar:

   - Weak: `Updated table component` — names a component.
   - Strong: `Prototype apply modes in settings drawer for users to intentionally choose local vs. matching vs. global updates; remove silent live inheritance and the late confirm` — names the decision and what it displaced.

3. **Write the line.** Primary clause first; secondary work follows after a semicolon.

   Length matches the session's substance — roughly 70–170 characters, and never padded. A narrow session gets a shorter line.

   Capitalize the first word. Sentence fragment, no filler, no citations, no attendee names.

4. **Check it.** Every activity in the line is supported by the evidence. Nothing is described as delivered that did not land. Then output the line and nothing else.

## Voice

Say what was designed and why it changed:

- `Designed the bulk upload history UX; replaced the slide-out error list with a master-detail layout showing rejected rows in the client's own file columns and flagged cells`
- `Build framework-free HTML/CSS foundation and component library for modernizing legacy pages; dashboard, design system tokens, components and patterns`
- `Prototype and iterate on the search and results list pages; add more design system components`
- `UX polish pass to clarify hierarchy, labels, grouping, and user intent`
- `Iterating and designing the search checkout flow`

The time entry's project code already names the project, so spend characters on the work, not the app name.

Reach for the terms that make the activity legible: prototype, iterate, design system, component, interaction, flow, states, edge cases, master-detail, hierarchy, UX polish pass, wireframe, audit, accessibility, handoff, demo.
