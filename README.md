# Big Panda Maths

The Key Stage 2 sister of [Little Panda Maths](https://github.com/pjanak/little-panda-maths): a colourful, mobile-first maths site for 7–11 year olds (Years 3–6), using the "maths mastery" methods that UK schools adopted from Shanghai. Bao the panda is back, now with reading glasses.

Compared with Little Panda Maths, older children type answers on a number pad instead of picking from three, and read-aloud is off by default (the speaker button still reads any question).

## Games

**Number and calculating**

- **Times Tables (乘法口诀)**: up to 12 × 12. Year 6 mode copies the Year 4 Multiplication Tables Check, with 6 seconds per question, missing numbers and division. Answers show the matching line of the Chinese times-table rhyme.
- **Column Methods (竖式)**: formal written addition and subtraction, typed one digit at a time from the ones, with carries and exchanges shown as they happen.
- **Clever Calculating (巧算)**: mental shortcuts such as + 99 as + 100 − 1, and 25 × 4 = 100.
- **Place Value (数位)**: digit values and rounding on a number line, up to 10 million and three decimal places.

**Fractions, problems and measures**

- **Fractions (分数)**: naming, shading equivalent fractions, comparing, fractions of amounts, adding and subtracting.
- **Bar Models (线段图)**: word problems drawn as bars, from part-whole to the "units" method for times-as-many and ratio.
- **Decimals and Percentages (百分数)**: hundred squares, then percentages of amounts.
- **Area and Perimeter (面积)**: rectangles on a grid, then from side lengths, then L-shapes.

## Year groups

| Game | Years 3–4 | Year 5 | Year 6 |
|---|---|---|---|
| Times Tables | 2, 3, 4, 5, 8, 10 tables | All tables to 12 × 12 | 6-second check mode, missing numbers, division |
| Column Methods | 3-digit addition | 4-digit addition and subtraction | 5-digit subtraction across zeros |
| Clever Calculating | Bonds to 100, ± 9 and 19 | ± near-hundreds, × 5 | 25 × 4, 125 × 8, × 99, grouping |
| Place Value | To 9,999, rounding to 10 or 100 | To 999,999, rounding to 1,000 or 10,000 | To 10 million, plus decimals |
| Fractions | Naming fractions, unit fractions of amounts | Shading equivalents, comparing | Fractions of amounts, adding and subtracting |
| Bar Models | Part-whole | Comparison | Units: times as many, ratio |
| Decimals and Percentages | Tenths and hundredths | Percentages on a hundred square | Percentages of amounts, comparing |
| Area and Perimeter | Perimeter on a grid | Area and perimeter from side lengths | L-shapes |

A wrong answer has no penalty: the game gives a hint (often the first step of the method) and lets the child try again. Every 10 stars brings up a celebration.

## Grown-up settings

Open **Grown-up settings** at the bottom of the home screen:

- **Play timer**: 10, 15, 20 or 30 minutes, with a countdown and a "Time's up!" screen. Holding the button for 2 seconds adds 5 more minutes.
- **Read questions aloud**: off by default for KS2.
- **Reset stars**: sets the star count back to 0, after a confirmation step.

## Running it

Live at **https://big-panda-maths.pages.dev** (Cloudflare Pages, redeploys on every push to `main`).

It's a single static file with no build step. Open `index.html` in a browser, or host the folder on any static host (GitHub Pages, Cloudflare Pages, Netlify). A physical keyboard works too: type digits, Backspace and Enter.
