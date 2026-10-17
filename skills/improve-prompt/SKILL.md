---
name: improve-prompt
description: Write a deeper prompt for a task, framed the way a top professional in the field would approach it, before starting. Use when starting a substantial task, or when asked to go deeper or be more ambitious.
---

# Write Deep Prompt

Inspired by Felix Rieseberg's essay [How to be more ambitious: A tutorial for humans with models](https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/).

The goal is a deeper version of the task, not a bigger one.

## Steps

1. **Answer four questions** before doing the task:
   1. What would a top professional in this field do here that wasn't asked for?
   2. What is the rawest material they would start from, instead of an already digested summary?
   3. Which specific methods and tools would they use? Use real instruments like databases, statistical models, or test suites, not just expert vocabulary.
   4. What outside check, other than the model or the user, would show the result is right? Prefer a tool or test that gives feedback right away.
2. **Rewrite the prompt** so it asks for exactly that.
3. **Optional moves:**
   - **Altitude:** ask what should happen next, find the goal behind the goal, and aim at that outcome.
   - **Unreasonable goal:** set a target far beyond the ask, like 200ms instead of 5s, and keep going.
   - **Challenge assumptions:** try to reproduce a believed cause from the raw data.
   - **Range:** describe the work with verbs instead of nouns, list the fields that would bring something useful, and borrow their methods. Don't role-play them.
4. **Confirm, then do it.** Show the user the rewritten prompt and get a go-ahead before starting a large or costly run. Then do the work and validate it with the outside check from step 1.
