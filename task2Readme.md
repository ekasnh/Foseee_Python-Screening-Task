
## 9) README.md (for GitHub repository)

Below is a ready-to-drop `README.md` you can include in your submission repository. It explains how to run and test the prompt locally and what to include when submitting the repo link.

```
# AI Tutor Prompt — Buggy Python Code (Submission)

This repository contains a ready-to-use AI prompt and supporting materials for grading and demonstration. The goal: provide an AI prompt that helps a student debug Python code by diagnosing issues and giving stepwise hints **without** giving the final solution unless explicitly requested.

## Contents
- `PROMPT.md` — the primary assistant prompt (same text as in this repo) ready to copy-paste into an AI system.
- `README.md` — this file with setup and submission instructions.
- `examples/` — sample buggy Python files and sample assistant replies (non-spoiler hints) — *optional but recommended*.
- `rubric.md` — checklist showing how to grade assistant replies for compliance with the "no-solution unless requested" rule.

## How to use
1. Copy `PROMPT.md` into the system or assistant prompt field of your AI interface.
2. Use the assistant by pasting a student's code and a short description of the observed problem.
3. Evaluate the assistant's response using `rubric.md`.

## Example workflow
1. Student posts code snippet + one-line description of expected behavior.
2. Assistant replies with the structured sections: `Restatement`, `Quick Scan`, `Possible Causes`, `Hint — Level 1`, `Hint — Level 2`, `Hint — Level 3`, `Suggested Tests and Invariants`, `Next Steps`.
3. Student tries tests; if needed, they reply `WALKTHROUGH` or `SHOW` (explicit consent required to receive full code).
