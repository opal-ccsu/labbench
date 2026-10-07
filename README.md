# Lab Bench

Interactive course tools for the CCSU statistics sequence, built by Dr. Caleb Bragg.
Every tool is one self-contained HTML file: no build step, no framework, no server,
no analytics, nothing uploaded. Open it from a folder or serve it with GitHub Pages.

## Tools

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

## Adding a tool

1. Put the single HTML file at `<course>/index.html`.
2. Keep CSS and JavaScript inline and every link relative, so the tool works both
   opened from disk and served under any base URL.
3. Add a line under **Tools** above.

Textbook for Psy 210: Reid, H. M. (2021). *Indispensable statistics for the behavioral
sciences, with SPSS 26.* Open access: https://digitalcommons.buffalostate.edu/oer/1
