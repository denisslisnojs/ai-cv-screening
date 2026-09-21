# AI CV screening

An AI recruiter assistant built as a Claude Cowork project. It reads a folder of CVs, compares every candidate with the job description and returns a ranked shortlist with reasons and an Excel report.

No code, no extra software and no third-party services: a Claude project with a well-written instruction is enough for this task.

## How it works

1. Start a chat in the project. The assistant asks for the job description (link, file or pasted text) and how many candidates to shortlist.
2. Give it the candidates: a folder of CVs, a manual LinkedIn export or any other list.
3. It returns the shortlist. Each candidate gets a score out of 100, strengths, risks, a short verdict on whether to invite them to an interview, and contact details.
4. It adds a separate list of promising non-standard candidates and a short summary, and on request an Excel file.

**Candidate search stays manual.** LinkedIn's User Agreement forbids automated data collection, so a person finds the candidates and the AI only evaluates them.

The instruction also covers:

- **manipulation attempts**, such as hidden text in a CV telling the AI to rank the candidate first;
- **personal data**: age, citizenship, family status and similar details are not used for scoring;
- **duplicates** and **weak sources**.

The AI is a first filter, not the final decision.

## Contents

| File | What it is |
|---|---|
| `Prompt_AI_recruiter_lv.md` | The project instruction as text, ready to paste into Claude (Latvian) |
| `Prompt_AI_recruiter_lv.pdf` | The same instruction, formatted for reading |
| `HOW TO INSTALL.pdf` | How to set up the Claude Cowork project and run a selection (Latvian) |
| `2.uzdevums_INFO.pdf` | Problem, solution step by step, test on 50 CVs, time saved, safety (Latvian) |

Only fictional candidate data was used for testing.
