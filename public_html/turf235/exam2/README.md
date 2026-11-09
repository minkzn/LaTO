# TURF 235 Exam 2 Study Site

## Contents
- `study-guide.html` — searchable/printable study guide
- `quiz.html` — 1201-question quiz, 10 at a time
- `questions.json` — the question bank; currently the union of M10-M20, will grow as later modules are added
- `styles.css`

## Question distribution
Each module's questions carry over 1:1 from its own module bank (`../M#/questions.json`), so the distribution naturally reflects how much well-formed material each module supports — nothing here is padded to a fixed count.

- M10: 61
- M11: 119
- M12: 50
- M13: 107
- M14: 149
- M15: 171
- M16: 104
- M17: 122
- M18: 59
- M19: 161
- M20: 98

## Accuracy / source rules
- Each question is modeled on the real Canvas quiz style for its module and sourced from that module's own course PDFs, with a curated slice of textbook enrichment on the same topics where it adds real depth.
- Every question reveals its source after submission.

## Quiz behavior
- 10 questions per batch
- correct answers retire
- missed answers cycle to the back
- progress saved per module filter in localStorage
