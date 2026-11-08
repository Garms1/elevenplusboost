# ElevenPlusBoost

Free 11+ practice for families in Surrey, Croydon and Sutton, live at **[elevenplusboost.com](https://elevenplusboost.com)**.

ElevenPlusBoost helps children prepare for the entrance tests at Caterham, Trinity, Whitgift and the five Sutton grammar schools. Children practise in each school's real format, and parents see exactly which topics need more work.

## What it does

- **Mock tests in each school's format**: timings, sections and question styles based on what each school publishes.
- **Over 130 question types** across English, Maths, verbal reasoning and non verbal reasoning. Each type is a small program that creates fresh questions every time, so practice never runs out.
- **A Parent area** to see readiness by school, spot weak topics, turn wrong answers into new practice and set work with a deadline.
- **Bitesize lessons, flashcards, writing and interview practice** for the parts of the 11+ a multiple choice test cannot cover.
- **Free school guides** with key dates, what is tested and a simple plan for each school.
- **Settings for families**: light and dark mode, bigger text, an easy read font, read aloud, and a choice of the schools they are interested in.

## How it is built

- Plain HTML, CSS and JavaScript, with no frameworks and no tracking.
- The source is split into small parts (styles, question banks, question generators, screens and events) and joined into one fast loading page by a short build script.
- The non verbal reasoning diagrams (shapes, nets, folds and codes) are drawn in code as SVG, so they stay sharp on any screen.
- Progress is saved only in the visitor's own browser. There are no accounts and nothing is sent to a server.
- Each school guide is a plain HTML page that search engines and AI tools can read.

## Quality checks

Every change is checked automatically before it goes live:

- every button on phone and laptop is pressed to confirm it does something;
- accessibility is tested with axe-core on every screen, in light and dark mode;
- the HTML is validated, and typed text is tested to make sure it is always handled safely;
- every link on the home page and school guides is followed;
- about 8,000 generated questions are checked to confirm each one is complete, with distinct options and a valid answer.

## About

Designed and built in 2026 as a family project, to make good 11+ preparation free and easy for local families.
