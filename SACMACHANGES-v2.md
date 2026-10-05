# SAC Math Academy v2: what changed

Starting point: your GitHub repo (SacMathAcademy-main.zip). All 22 code and data files matched my latest package. The only difference was that the repo's `images` folder held just a placeholder, so **all 33 images were missing**, not only the five on S5.

## Course homepage
- Title is now "STAT C1000 · Introduction to Statistics", with "Statistics, one outcome at a time" as the tagline.
- New lead sentence: "Find explanations, practice, and support for the statistics topic you are learning today." Accurate resource counts remain as a smaller line. Search is larger.
- "Question claims. Understand variation. Decide with evidence." appears near the top. The full "Statistical thinking: the big ideas" section is now at the bottom of the page.
- Three opening cards: Learn a topic, Practice and review, Get help.
- Four unit cards still show all 23 outcomes. Each row now shows its Canvas module (for example "Modules 9–10"). The hover instruction is gone. A "Show 'I can' statements" button reveals the full statements and works with keyboard and touch.
- S22 is retitled "Conducting chi-square, ANOVA, and regression tests". For consistency, S21 is now "Choosing chi-square, ANOVA, and regression tests". Official statements are unchanged.
- The full AI guide and the review cards moved off the homepage. A compact AI card and a link remain.

## New course navigation (every course page)
Outcomes · Tools · Practice & Review · Get Help · AI Study Partner. On phones it collapses into a "Course menu" button. It is not sticky, so it never covers a heading or a focused control.

## New pages
- **Practice & Review** (`#/stat-c1000/practice`): midterm review, final skills review, final concept review, inference practice quiz, a guide to the sample problems and self-checks on every outcome page, and the Canvas items. The midterm review itself is unchanged (ratings, saved ratings, study list, 35 practice problems, outcome filters). The old `#/stat-c1000/midterm` address still works.
- **AI Study Partner** (`#/stat-c1000/ai`): the full guide with the steps, four roles, 16 prompts with copy buttons, reflections, and reminders.

## Outcome pages
- Jump links near the top: Notes · Videos · Apps · Practice · Self-check · Help. On wide screens they stay at the top while scrolling. Jumping also moves keyboard focus to the target heading.
- Sample problems now sit inside Step 4 (Practice), before Step 5 (Check yourself). Hints, answer reveals, sources, related-outcome links, and worked-solution links are kept. Pages with more than two problems show two and expand for the rest.
- Items are labeled "On this site: ungraded practice" or "In Canvas". No grading policy was added.
- "Where this fits" is kept.
- General AI instructions are now expandable. "Try the problem first" stays visible, and so do the topic prompts and follow-ups.

## Unfinished items hidden from students
"[App to be built]", the "Planned" retrieval cards and apps section, "[curator email]", "[Add a course]", "coming soon" messages, "Open slot" notes, and "no ... yet" messages. Planned apps can be previewed by setting `SHOW_PLANNED: true` in `config.js`. The S12, S13, and S16 Art of Stat notes were reworded to remove gap language.

## Images
All 33 referenced images are in the `images` folder of this package. Alt text is kept.

## Under the hood
- Version number raised to 2026-10-05.2 in both `app.js` and `course.json`.
- If an older data file is paired with this code, the site uses built-in text and shows a yellow "files are out of date" bar.
- Empty table-header cells now have hidden text for screen readers.
