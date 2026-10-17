---
name: write-ux-invoice-line
description: Write a timesheet description line for the UX work done in this session. Use when the user needs an invoice or time-entry line for design, prototyping, or UX research work.
disable-model-invocation: true
---

# Write UX Invoice Line

Turn the current working context into one timesheet description line, ready to paste into a time-tracking tool.

One line covers **one working context** — this session's work on this project. Several lines a day for the same project is normal. Meetings are billed elsewhere; this skill is for design and build work.

## Steps

1. **Gather the evidence.**
   - The conversation context — what was designed, prototyped, researched, synthesized, iterated on, evaluated, rejected. Exploration and discarded directions count: choosing between three approaches is the work.
   - `git log` and `git status` for this session's commits, to catch work done outside the narrative.
   - Anything the user typed after the command — design-tool work the session can't see.
   - Completed tasks in the user's task manager, when one is connected. Pull tasks the user completed in the window being billed, in the project being billed; ask which project or window if it isn't clear. When the session was opened only to write the line, these may be the main evidence.

   Task titles are evidence, not copy: roll them up into the work they add up to, don't list them.

   Done when you can name the **work that landed**, at the grain it landed: not the files touched, and not a product decision buried inside research docs.

2. **Name the work.** The line's first clause states the activity that landed. Match grain to deliverable:

   - **Designed or prototyped a product change:** name the UX decision and, where there was one, what it replaced.
   - **Assembled research, synthesis, or planning docs:** name that pack (audit, conceptual model, job stories, breadboards, open questions). Do not promote a decision *inside* the docs as if a product UI shipped.

   Quality bar:

   - Weak: `Updated table component` — names a component.
   - Strong (product change): `Prototype apply modes in settings drawer for users to intentionally choose local vs. matching vs. global updates; remove silent live inheritance and the late confirm` — names the decision and what it displaced.
   - Weak (research session billed as a product ship): `Lock the object model: primary record as workspace, queue as completion, line item as evidence` — names a decision from inside the docs as if it shipped.
   - Strong (same session, correct grain): `Assemble the UX research pack from the PRD and researcher notes: layer audit, conceptual model, job stories, interaction breadboards, and open questions`

3. **Write the line.** Primary clause first; secondary work follows after a semicolon.

   Length matches the session's substance — roughly 70–170 characters, and never padded. A narrow session gets a shorter line.

   Capitalize the first word. Sentence fragment, no filler, no citations, no attendee names.

4. **Check it.** Every activity in the line is supported by the evidence. Nothing is described as delivered that did not land. Then output the line and nothing else.

## Voice

Say what was designed and why it changed. For research sessions, say what was assembled:

- `Designed the bulk upload history UX; replaced the slide-out error list with a master-detail layout showing rejected rows in the client's own file columns and flagged cells`
- `Build framework-free HTML/CSS foundation and component library for modernizing legacy pages; dashboard, design system tokens, components and patterns`
- `Prototype and iterate on the search and results list pages; add more design system components`
- `UX polish pass to clarify hierarchy, labels, grouping, and user intent`
- `Iterating and designing the search checkout flow`
- `Assemble the UX research pack from the PRD and researcher notes: layer audit, conceptual model, job stories, interaction breadboards, and open questions`

The time entry's project code already names the project, so spend characters on the work, not the app name.

Reach for the terms that make the activity legible: prototype, iterate, design system, component, interaction, flow, states, edge cases, master-detail, hierarchy, UX polish pass, wireframe, audit, accessibility, handoff, demo, research pack, synthesis, job stories, breadboard, conceptual model.
