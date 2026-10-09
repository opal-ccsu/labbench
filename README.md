# Lab Bench

Interactive course tools for the CCSU statistics sequence, from OPAL, the Organizational
Psychology Answers Lab (Dr. Caleb Bragg). Every tool is one self-contained HTML file: no
build step, no framework, no server, no analytics, nothing uploaded. Open it from a folder
or serve it with GitHub Pages.

Licensed under CC BY-NC 4.0; see LICENSE.

## Tools

- **index.html** — the landing page. Routes a student from what they need today (a lab is
  due, which test is this, exam this week, numbers and no sentence, ordering data from an
  AI, just need the word) to the right bench and the right place in it, then describes the
  four benches, the house rules, and the license. The lab logo goes at `brand/opal-logo.png`;
  until that file exists the masthead shows a wordmark.

- **psy210/** — Psy 210 Lab Bench, the SPSS statistics laboratory. All thirteen labs
  run live in the browser on the handouts' sample scenarios: order a dataset with the
  truth built in, verify it, read SPSS-style output and syntax, write the APA sentence,
  then draw again to watch sampling error. Includes a practice loop for the AI Data
  Protocol and a which-test chooser. Labs 11 and 13 use teaching replicas built to the
  codebooks of the real files handed out in lab.

- **psy215/** — Psy 215 Lab Bench, Psychological Statistics in Excel. The same engine with an
  Excel identity: sheet grids, formula cards, a variable table with scale of measurement, and
  all ten Excel data activities, plus the sample prompts for the three Team Mastery
  assignments that need data.

- **glossary/** — Psy 215 and Psy 210 concepts and terms: 222 entries with a definition,
  an example and a watch-for, tagged by course, by the week or lab where each first appears,
  and by Reid chapter. Searchable, filterable, with a quiz mode. The data live in
  `glossary/terms.json`, which is the single source of truth for the Concept Bench.

- **wall/** — the comics pinned beside the benches, in course order, with the line each is
  pinned up for and its credit. Allison Horst's statistics illustrations (CC BY 4.0, web-sized
  copies in `comics/horst/`) and xkcd strips (CC BY-NC 2.5, loaded from xkcd.com with a link
  fallback). The registry `build`-side is one file shared by every page; each lab and activity
  shows its pins under the mistake panel, and the Concept Bench shows a tagged comic under the
  model answer.

- **concepts/** — Concept Bench, the glossary as typed practice for both courses. Seven
  modes: define a term in your own words, name the term from its idea, fill the blank, work
  the number with fresh values each time, name the test for a scenario and say why, find the
  error in a report, and fill the decision map from memory. Terms and numbers are checked
  exactly; explanations are checked for key ideas and then self-marked against the glossary
  entry. Filter by course and by movement; mastery is tracked only in the student's browser.
  `concepts/content.md` lists everything the bench adds on top of the glossary, for review.

## Adding a tool

1. Put the single HTML file at `<course>/index.html`.
2. Keep CSS and JavaScript inline and every link relative, so the tool works both
   opened from disk and served under any base URL.
3. Add a line under **Tools** above.

Textbook for Psy 210: Reid, H. M. (2021). *Indispensable statistics for the behavioral
sciences, with SPSS 26.* Open access: https://digitalcommons.buffalostate.edu/oer/1
