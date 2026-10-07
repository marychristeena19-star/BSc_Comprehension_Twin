# Science Reading Twin (BSc)

An adaptive English language twin for first-year BSc students in Kerala. Students read **popular-science
articles from every branch of science** and answer **higher-order-thinking questions**, building English
language skills and critical thinking (not syllabus science).

## For students
1. **Reading check:** 2 diagnostic passages (about 100 and 200 words) place each student on a 6-level ladder
   (80 → 100 → 130 → 160 → 200 → 250 words).
2. **Unlimited practice:** passages rotate through 16 branches of science (physics, chemistry, biology, botany,
   zoology, space, earth science, climate, health, genetics, AI, mathematics, energy, oceans, brain, history of
   science). 80%+ moves up a level, below 50% moves down one. Each passage targets the weakest skill.
3. **Three HOTS questions per passage:** analysis/inference (MCQ), vocabulary in context (MCQ), and a written
   evaluate/create question. Hints, instant feedback, grammar and vocabulary scaffolds.
4. **Twin 🦉** welcomes, motivates and gives a full review with smileys after every passage.
5. **Save & quit** any time; resume later. **Try again** to redo a passage.

## Accuracy safeguards
- Strict rules: only well-established facts; no invented studies, experts, quotes, dates or statistics.
- Passages that mention studies, "Dr.", "researchers at", recent dates, etc. are rejected automatically.
- Every new passage is **fact-checked by a second, stronger model**; failing passages are rewritten.
- Only fact-checked passages are reused from the bank.
- Students can **🚩 report** a passage; it is never reused and appears on the teacher dashboard.
No AI system can guarantee zero errors — glance at the Bank and Flags tabs now and then.

## Google Sheet tabs (created automatically)
Summary · Roster · Logins · Passages · Attempts · Drafts · Bank · Flags

## Setup
See **BSc_Twin_Setup_Guide.docx** for the full step-by-step guide.
Secrets needed: `GEMINI_API_KEY`, `TEACHER_PASSWORD`, `SHEET_ID`, `gcp_service_account` (whole JSON key).
Students go in the Sheet's **Roster** tab (column A roll number, column B full name).
