---
name: add-todoist-task
description: Create, find, or update a Todoist task and always return its link. Use when you create, look up, or mention a Todoist task.
---

# Manage Todoist Task

Handle one Todoist task through whatever Todoist tools are available, and hand it back with its link every time.

## Steps

1. **Pick the project.** Find the project the task belongs to. If it's unclear, ask instead of guessing. With no project given and none that fits, use Inbox.
2. **Look before you create.** Search for an existing task that matches. Reuse it if it does.
3. **Create it.** Otherwise add the task to that project. Set a due date, time, or duration only if the user gave one.
4. **Never reschedule without asking.** Don't change an existing task's due date or time unless the user says to.
5. **Always return the link:** `https://app.todoist.com/app/task/<task id>`. Every mention of the task carries that link.
