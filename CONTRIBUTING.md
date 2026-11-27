# Contributing Guide

## Rules
1. Check that the question doesn't already exist (use Ctrl+F / search).
2. Put the question in the right folder (`python/`, `fastapi/`, `ai/`).
3. Name the file after the company or topic: `google.md`, `arrays.md`
4. One PR should cover only one company/topic.
5. Do not add confidential or NDA-protected company information.
6. Spam, irrelevant, or copy-pasted content will be rejected.

## Question format

```md
### Q. Write the question here

- **Company:** Google
- **Role:** SDE-1
- **Round:** Technical Round 1
- **Difficulty:** Medium
- **Year:** 2026

**Answer / Approach:**
Briefly describe the approach or answer.
```

## Workflow

```bash
git clone https://github.com/<your-username>/interview-questions.git
cd interview-questions
git checkout -b add-google-questions
# edit files
git add .
git commit -m "Add Google DSA questions"
git push origin add-google-questions
```

Then click "Compare & pull request" on GitHub.

## Commit messages
Keep them short and clear: `Add <company> <category> questions`