# TURF 235 Exam 1 Study Site

## Contents
- `study-guide.html` — searchable/printable study guide
- `quiz.html` — 100-question exams drawn from the 350-question pool, 10 at a time
- `questions.json` — the 350-question pool (full per-module banks live in `../M#/questions.json`)
- `styles.css`

## What's in the pool
Same format as Exam 2. Built from how the real exams pull from the quizzes:
- Every actual Exam 1 question with its correct answer (Q13 left out; its key is uncertain)
- The M1-M9 module quiz questions, near-verbatim, with keys
- The M8-M9 grass ID and subfamily questions that reappeared on Exam 2, plus "Who am I?" riddles
- 68 module-page details from the per-module banks, added to the thinner modules (M1, M5-M9)

Each exam draws 100 questions, weighted by module share of the pool. The "Skip grass ID questions" toggle hides the 105 tagged grass identification questions.

## Pool by module
- M1: 39
- M2: 44
- M3: 50
- M4: 47
- M5: 39
- M6: 39
- M7: 39
- M8: 28
- M9: 25

## Quiz behavior
- 10 questions per batch
- correct answers retire
- missed answers cycle to the back
- progress saved in localStorage (separately with grass ID skipped)
