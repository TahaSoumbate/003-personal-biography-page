# Personal Biography Page

A long-form "about me" page built as part of a front-end learning path.
Focus: semantic HTML, heading hierarchy, and readable long-form typography.

**[→ Live demo](https://TahaSoumbate.github.io/personal-biography-page/)**


## What's in it

- Semantic heading outline: one `<h1>`, three `<h2>` sections, one `<h3>` subsection
- A pull quote using `<blockquote>` with an attributed `<cite>`
- A dated timeline as an `<ol>` with `<time datetime="">` for each event
- A text column capped at `65ch` for comfortable reading

## What I learned

- Why heading *level* is structural and heading *size* is CSS — choosing levels for meaning, not appearance
- Why `max-width: 65ch` beats `width: 30%` for limiting line length
- Separating heading line-height (~1.1) from body line-height (~1.6)
- Using `<time datetime="2015">` so dates are machine-readable while staying human-friendly
- Why a universal `* { margin: 0 }` reset is wrong on prose pages — and how to rebuild vertical rhythm

## Tech

Plain HTML and CSS. No frameworks, no build step.

## Run locally

```bash
git clone https://github.com/TahaSoumbate/personal-biography-page.git
cd personal-biography-page
# open index.html in your browser