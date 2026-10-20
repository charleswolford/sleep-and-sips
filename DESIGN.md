---
name: Sleep and Sips
description: The red book's missing chapter, kept by the parents and drawn on centile-chart paper.
colors:
  cover-red: "#b3202a"
  cover-red-deep: "#8e1820"
  cover-ink: "#ffffff"
  cover-blush: "#ffe1de"
  record-paper: "#ffffff"
  record-paper-shade: "#f3f5fa"
  navy-print: "#1b2340"
  navy-print-2: "#4b5474"
  navy-print-3: "#6b7391"
  form-rule: "#d5dcea"
  form-rule-strong: "#aab6cf"
  grid-minor: "#e8eef8"
  grid-major: "#c6d4ec"
  centile-blue: "#4f78bd"
  centile-50: "#2f5aa5"
  series-ink: "#1d2b4f"
  series-blue: "#2f66c9"
  series-gold: "#c27c00"
  series-rose: "#c8467a"
  series-own: "#b3202a"
  series-grey: "#8f99b3"
  card-marigold: "#f6b93f"
  card-marigold-ink: "#2b1d03"
  card-marigold-ink-2: "#553e0c"
  card-sky: "#aecbf4"
  card-sky-ink: "#12203f"
  card-sky-ink-2: "#2f4169"
  card-pink: "#f7c3cd"
  card-pink-ink: "#3b1220"
  card-pink-ink-2: "#66303f"
  card-navy: "#1d2b4f"
  card-navy-ink: "#ffffff"
  card-navy-ink-2: "#c3cde6"
  dark-cover-red: "#a51d27"
  dark-cover-red-deep: "#7a141c"
  dark-cover-blush: "#ffd9d5"
  dark-record-paper: "#160c0f"
  dark-record-paper-shade: "#21141a"
  dark-print: "#f4eeee"
  dark-print-2: "#c6b5b8"
  dark-print-3: "#9d8b8f"
  dark-form-rule: "#3a2930"
  dark-form-rule-strong: "#5a464d"
  dark-grid-minor: "#1d1f2d"
  dark-grid-major: "#2f3a58"
  dark-centile-blue: "#7f9de0"
  dark-centile-50: "#a9c0f2"
  dark-series-ink: "#d6c9c6"
  dark-series-blue: "#6f9bf0"
  dark-series-gold: "#f0b440"
  dark-series-rose: "#f08fb6"
  dark-series-own: "#ff6b6b"
  dark-series-grey: "#8a8090"
  dark-card-white: "#24161c"
  dark-card-white-edge: "#4a3640"
  dark-card-marigold: "#6a4212"
  dark-card-marigold-ink: "#ffe2a8"
  dark-card-marigold-ink-2: "#efc98c"
  dark-card-sky: "#23497f"
  dark-card-sky-ink: "#e3edff"
  dark-card-sky-ink-2: "#b9cdf0"
  dark-card-pink: "#5a2233"
  dark-card-pink-ink: "#ffdbe3"
  dark-card-pink-ink-2: "#efb7c4"
  dark-card-navy: "#1a2240"
  dark-card-navy-edge: "#2f3a60"
  dark-card-navy-ink: "#eef1fb"
  dark-card-navy-ink-2: "#b6c0de"
typography:
  display:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "2.5rem"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  card-value:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "2.75rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.035em"
    fontFeature: "tnum"
  headline:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "1.625rem"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  title:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 700
    lineHeight: 1.3
  card-label:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 700
  record-value:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "1.75rem"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.01em"
    fontFeature: "tnum"
  lede:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 600
    lineHeight: 1.4
  chart-axis:
    fontFamily: "'Public Sans', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "11.5px"
    fontWeight: 400
    fontFeature: "tnum"
rounded:
  swatch: "2px"
  tag: "4px"
  control: "6px"
  card-phone: "14px"
  card: "16px"
  sheet: "0px"
spacing:
  card-gap-phone: "8px"
  card-gap: "14px"
  wrap-mobile: "16px"
  wrap-desktop: "32px"
  sheet-pad: "16px"
  pair-gap: "20px"
  sheet-gap: "24px"
  group-gap: "28px"
  page-gap: "44px"
components:
  button-cover:
    backgroundColor: "{colors.cover-ink}"
    textColor: "{colors.cover-red-deep}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 16px"
    height: "44px"
  button-cover-hover:
    backgroundColor: "#ffeceb"
  link-forget:
    textColor: "{colors.navy-print-2}"
    typography: "{typography.label}"
  glance-card-white:
    backgroundColor: "{colors.record-paper}"
    textColor: "{colors.navy-print}"
    typography: "{typography.card-value}"
    rounded: "{rounded.card}"
    padding: "16px 18px 18px"
    height: "158px"
  glance-card-marigold:
    backgroundColor: "{colors.card-marigold}"
    textColor: "{colors.card-marigold-ink}"
    rounded: "{rounded.card}"
  glance-card-sky:
    backgroundColor: "{colors.card-sky}"
    textColor: "{colors.card-sky-ink}"
    rounded: "{rounded.card}"
  glance-card-pink:
    backgroundColor: "{colors.card-pink}"
    textColor: "{colors.card-pink-ink}"
    rounded: "{rounded.card}"
  glance-card-navy:
    backgroundColor: "{colors.card-navy}"
    textColor: "{colors.card-navy-ink}"
    rounded: "{rounded.card}"
  tab:
    backgroundColor: "{colors.record-paper}"
    textColor: "{colors.navy-print-2}"
    padding: "14px 12px 11px"
  tab-active:
    textColor: "{colors.navy-print}"
  segment:
    textColor: "{colors.navy-print-2}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 12px"
    height: "38px"
  segment-pressed:
    backgroundColor: "{colors.cover-red}"
    textColor: "{colors.cover-ink}"
  record-field:
    textColor: "{colors.navy-print}"
    rounded: "{rounded.sheet}"
    padding: "9px 14px 14px"
  chart-sheet:
    backgroundColor: "{colors.record-paper}"
    rounded: "{rounded.sheet}"
    padding: "16px 16px 12px"
  tooltip:
    backgroundColor: "{colors.record-paper}"
    textColor: "{colors.navy-print}"
    rounded: "{rounded.tag}"
    padding: "8px 10px"
---

# Design System: Sleep and Sips

Scope: this system governs the Red Book world shipped in `v2/index.html`. The repo root's `index.html` and `cs.html` predate it (cream paper, Fraunces and Nunito, coloured cards) and are not governed by it. A Czech page in this world, when it comes, follows this file.

## Overview

**Creative North Star: "The Red Book's Missing Chapter"**

The page is a record the parents keep beside the personal child health record: a red cover band across the top, white record paper beneath, navy print ink, and every chart drawn on the boys' centile-chart blue graph paper the health visitor already reads. It borrows the form of a printed record, not its authority: there is no NHS logo, wordmark, Frutiger or claim of official status.

The record pages are dense like a filled-in form. Each section opens with a red rule, a heading and an answer sentence, then printed record rows (small label above a large tabular value) and chart sheets framed by a hairline. The one exception, added at the parents' request, is a strip of six glance cards tucked half over the bottom of the cover band, like coloured stickers slipped into the book's front: warm field colours, soft corners, big numbers and a Pip on each, and each card opens its section. Below the tabs everything is flat paper and ink again. Outside the glance strip, the world still refuses the baby-tracker default of pastel rounded cards.

Light mode is white paper; dark mode is deep oxblood-black paper (the cover goes slightly deeper, the grid turns ink-blue on near-black, the navy chart ink becomes a warm pale stone so it differs in hue from the dark chart blue, the baby's own red brightens to stay legible, the card fields darken to deep marigold, sky, plum and navy). The direction contract named #170d0f for dark paper; the build ships #160c0f and that is the recorded value.

**Key Characteristics:**
- Red cover band at the top: the name and the load button on one row, the export time and a line saying weekly figures are 7-day averages against the 7 days before.
- Six glance cards tucked over the cover's bottom edge: the one playful, rounded, coloured place in the system.
- Blue graph paper with minor and major lines under every chart.
- Printed form-field rows: hairline cells, small label above value, square corners.
- One typeface (Public Sans, embedded) at every size, with tabular numerals on every number.
- Flat record paper: only the glance cards and the chart tooltip lift off the page.
- One authored motion moment: once per loaded export, the glance-card numbers count up from the week before. Charts never animate.
- Milestone flags in muted print ink mark the firsts on the charts.

## Colors

A record-book palette: one cover red, navy print on white paper and a family of chart blues, plus a small set of sticker colours used only on the glance cards. Dark mode keeps the same roles on oxblood-black paper.

### Primary
- **Record Cover Red** (cover-red): the cover band, the landing screen, the 2px rule above each section heading, the active tab underline, a pressed segment, text selection and the caret. Its deep shade (cover-red-deep) is the text colour on white elements on the cover and landing (the load button, the error note); cover-blush is secondary text on the cover.

### Secondary
- **Centile Blue** (centile-blue, centile-50): the nine printed centile lines and their right-edge labels; the 50th is darker and heavier. It also draws the ticks of the centile scale on the Weight card and the focus ring on paper.
- **Chart Inks** (series-ink, series-blue, series-gold, series-rose, series-grey): every data series that is not his own measure or an alert. Each ink holds at least 3:1 against its ground in both modes, and each has a fixed meaning that carries across charts:
  - **Navy ink** (series-ink; a warm pale stone in dark mode, distinct in hue from the dark blue): breast milk he drank, the 7-day average lines, feeds in busiest hours, and the first person in night feeds.
  - **Chart blue** (series-blue): milk pumped, sleep (including the sleep bands in the row-per-day rhythm chart), pumps in busiest hours, and the second person.
  - **Marigold** (series-gold): formula, drawn as a solid line, never dashed; bottles in the rhythm chart, nappies in busiest hours, and the third person.
  - **Rose** (series-rose): direct breastfeeds, in the rhythm chart too, and the fourth person.
  - **Grey** (series-grey): an "other" or remainder bucket.
  - Daily dots behind a 7-day average render at 0.75 opacity. Faded bars (weeks also breastfed, partial night weeks) fade only the fill (fill-opacity), never the outline or the ink itself. The old blue tint (--s-tint) is still defined in the stylesheet but no chart uses it, so it is not a system token.

### Tertiary
- **His Own Red** (series-own): the one series per chart that is the baby's own headline measure (weigh-ins on the centile chart, total he drank, ml per kg), the weight figure on the Weight card and the dot on its centile scale. In dark mode it lifts to a coral red (dark-series-own).
- **Sticker Fields** (card-marigold, card-sky, card-pink, card-navy, each with an ink and a secondary ink; white cards use record paper and navy print): the five glance-card fields. Marigold carries Age, sky carries Milk a day (with a faint 14px graph-paper grid), pink carries Breast milk share, navy carries Longest sleep, and white carries Weight and Pumped a day. Dark mode uses the dark-card set, with a 1px inset edge (dark-card-white-edge, dark-card-navy-edge) on the white and navy cards so they separate from the paper.

### Neutral
- **Record Paper** (record-paper) and **Paper Shade** (record-paper-shade): the page and sheet ground; the shade fills table headers, hovered controls and loading skeletons.
- **Navy Print** (navy-print, navy-print-2, navy-print-3): body text, secondary labels and notes, and muted chart text and shading. Muted print ink (navy-print-2) is also the chart annotation ink: milestone-flag rules and dots, and dotted reference rules.
- **Form Rules** (form-rule, form-rule-strong): hairline sheet borders and dividers; the strong rule draws record-row cells, controls, table frames and axes.
- **Graph Paper** (grid-minor, grid-major): the chart grid; major lines also frame the plot area.

### Named Rules
**The Cover Red Rule.** Red belongs to the cover. On paper it appears only as the section rule, the active tab or segment, an alert, and his own measure; never as a fill for a sheet, card or ordinary series.

**The One Red Series Rule.** Red in a chart means only his own measure or an alert: at most one red series per chart (his weigh-ins, total he drank, ml per kg; a caveat version of the same series is allowed, as in the ml-per-kg "also breastfed" bars: a faded fill with a full-strength 1.5px red outline, keyed by an outlined tint swatch), plus alert marks such as a long daytime gap with no sleep logged. Every other series uses the chart inks with their fixed meanings. The glance cards are the one place the palette widens further: their sticker fields are backgrounds, never series, and never enter a chart.

## Typography

**Display Font:** Public Sans (with system-ui, -apple-system, Segoe UI, sans-serif)
**Body Font:** Public Sans
**Label/Mono Font:** Public Sans, with tabular numerals

**Character:** One sturdy public-sector sans used like the type on a printed form: heavy for the name on the cover and the glance numbers, bold for headings and values, semibold for small printed labels, regular for the answer sentences.

Public Sans is embedded in the page as base64 woff2 (variable weight 400 to 800, latin and latin-ext subsets, SIL Open Font License 1.1), so the page makes no font requests.

### Hierarchy
- **Display** (800, 2.5rem, 1.05; 2.125rem under 600px): the baby's name on the cover band. The landing title uses the same voice at 2.75rem.
- **Card value** (800, 2.75rem, 1, -0.035em, tabular; 1.875rem on phones): the glance-card numbers, with the unit at 1.0625rem, weight 600, in the card's secondary ink.
- **Headline** (700, 1.625rem, 1.2): each section heading, always under the red section rule.
- **Title** (700, 1.0625rem, 1.3): group and chart-sheet titles; an inline small note at the label size may follow on the same baseline.
- **Card label** (700, 0.9375rem; 0.8125rem on phones): the glance-card name, in sentence case.
- **Record value** (700, 1.75rem, 1.15, tabular; 1.5rem in dense rows and on mobile): the numbers in record rows, with the unit at 0.9375rem, weight 500, in secondary ink.
- **Lede** (400, 1.0625rem, 1.55, max 64ch): the answer sentence that opens each section; key figures in bold.
- **Body** (400, 1rem, 1.5): running text.
- **Label** (600, 0.8125rem): printed field labels, control text, legends, notes, card sub-lines and table headers. Sentence case; never uppercase, never letter-spaced.
- **Chart axis** (400, 11.5px, tabular): axis ticks and shade labels; centile labels are 600 at 11px.

### Named Rules
**The One Family Rule.** Public Sans sets everything, including chart axes and tooltips; no second face, no monospace.

**The Tabular Numbers Rule.** Every value, card number, table cell, axis label and tooltip uses tabular numerals so figures line up the way they do on a form.

## Layout

A single centred column (max 72rem) with 16px side padding, 32px from 768px up. The cover band is a small grid with no wordmark: the name and the Load newer export button share the first row (20px column gap, 12px on phones), and the export time and the 7-day averages line run full width below. The glance strip pulls up 68px into the band (the band keeps 92px of bottom padding for it; 48px and 64px on phones), three cards across, two across under 900px, with a 14px gap (8px on phones). Then a sticky tab bar on paper with a hairline bottom rule holds the six sections (Since birth, Milk, Sleep, Growth, Shifts, Notes), with Since birth first, directly under the glance cards; on narrow screens it scrolls horizontally with a fade at the right edge. Each section is a record page: 44px above, a 2px red rule, the headline, the lede, then groups 28px apart.

Record rows are an auto-fit grid of cells at least 13rem wide; dense rows are three across. Under 600px they become two across, and an odd last cell spans both columns. Chart sheets stack 24px apart; pairs sit side by side when each can have 27rem, with a 20px gap, otherwise they stack. Small-multiple charts use an auto-fit grid of 15rem minimum. The footer, behind a hairline, holds the privacy line, the link to the previous version and "Forget data on this device". Interactive targets are at least 44px on the cover and 38px for chart controls.

## Elevation & Depth

Flat paper with two exceptions. Depth on the record pages is drawn with lines and tints: hairline sheet borders, strong rules on record cells, the paper shade on table headers and hovers. The glance cards sit on a soft oxblood-tinted shadow, as if laid on top of the cover, and the chart tooltip floats over the plot.

### Shadow Vocabulary
- **Card rest** (`box-shadow: 0 12px 26px -12px rgba(70, 8, 16, .45), 0 2px 5px rgba(70, 8, 16, .12)`; dark `0 12px 26px -12px rgba(0, 0, 0, .7), 0 2px 5px rgba(0, 0, 0, .3)`): glance cards at rest.
- **Card lift** (`box-shadow: 0 18px 30px -12px rgba(70, 8, 16, .5), 0 3px 6px rgba(70, 8, 16, .14)`): glance cards on hover and focus, with a 3px rise.
- **Tooltip lift** (`box-shadow: 0 6px 18px rgba(20, 28, 60, .16)`; dark `0 6px 18px rgba(0, 0, 0, .5)`): chart tooltips only.

### Named Rules
**The Flat Paper Rule.** Sheets, record rows, tabs and buttons carry no shadow. Only the glance cards and the tooltip are allowed off the page.

## Shapes

Square paper, softened controls, round stickers. Sheets, record cells, tables and the chart frame have square corners; buttons, segmented controls, date inputs and nav buttons are gently rounded (6px); the error note, tooltip and the breast-milk split bar are 4px; legend swatches 2px, line swatches square. The glance cards are the one generously rounded form (16px, 14px on phones). Pip is the one rotated shape: each card's Pip has its own tilt (between -9deg and 7deg), and the landing Pip is tilted -7deg with a 1.6px white die-cut outline.

## Components

### Buttons
Few and firm.
- **Shape:** gently rounded (6px), 44px tall.
- **Cover button:** white on the cover band with deep-red text and a stroked upload icon, 0.9375rem bold; the file input fills it invisibly. It is the page's one primary action ("Load newer export"; "Load Nara export" on the landing).
- **Hover / Focus:** hover tints to a pale blush (#ffeceb); press drops 1px; focus on the cover is a 2px white outline offset 2px.
- **Forget link:** an underlined text button in the footer, in secondary ink, navy on hover.

### Glance cards (signature)
Six link cards, playful but organised, that answer "how is he doing" before the tabs: Age, Weight, Milk a day, Breast milk share, Pumped a day and Longest sleep, each opening its section.
- **Shape:** 16px corners (14px on phones), at least 158px tall on desktop, padding 16px 18px 18px (10px 12px 12px on phones).
- **Fields:** marigold, white, sky with a faint 14px graph-paper grid, pink and navy, each with its own ink and secondary ink in light and dark.
- **Content:** card label, an 800-weight number with its unit, and a sub-line at the bottom with the change in bold. Weight sets its number in his own red and adds a nine-tick centile scale (ticks in centile blue, the 50th heavier, a red dot ringed in the card colour where he sits). Breast milk share adds an 8px split bar: the filled share in the card ink over a 22% tint of it.
- **Pip:** one Pip variant per card (bib, tape, bottle, magnify, clock, sleep), 128px at the bottom right (72px on phones), each at its own rotation; sub-lines and bars stop short of it.
- **States:** hover, focus and active lift the card 3px onto the card-lift shadow and wiggle the Pip; active settles back with a slight press. Focus-visible is a 3px ink outline, offset 3px, over a 3px white inner ring. Under reduced motion the wiggle and transitions are off.
- **Count-up (the page's one authored motion moment):** once per loaded export, each card number counts up from the week before (Weight from the previous weigh-in) to the current value over 1.1s with an exponential ease-out (1 - 2^(-10t)), and the breast-milk split bar grows from the prior share over the same 1.1s (cubic-bezier(.16, 1, .3, 1)). It never repeats on resize or redraw and is skipped entirely under prefers-reduced-motion.

### Segmented controls and date navigation
- **Style:** a 1px strong-rule frame with 6px corners, 38px tall, label-size semibold text in secondary ink, internal dividers in the strong rule.
- **State:** hover fills with paper shade; the pressed segment fills with cover red and white text. Arrow buttons and the date field share the frame and height.

### Navigation (section tabs)
- **Style:** sticky, paper background, hairline bottom rule; 0.9375rem semibold in secondary ink.
- **States:** hover darkens the text and shows a strong-rule underline; the current section shows navy text over a 3px cover-red underline.
- **Mobile:** horizontal scroll with no scrollbar and a right-edge fade.

### Record rows
Printed form fields. A grid of cells drawn with a shared 1px strong rule (top and left on the row, right and bottom on each cell), square corners, padding 9px 14px 14px. Inside: a small semibold label, the large tabular value with its unit, and a short sub-line in secondary ink with its key change in bold.

### Chart sheets
- **Corner Style:** square.
- **Background:** record paper.
- **Border:** 1px hairline (form-rule).
- **Internal Padding:** 16px 16px 12px (12px 12px 10px on mobile), 10px between title, legend, chart and the "How to read this chart" disclosure, whose chevron turns 90deg when open. The disclosure text refers to the key by name, never to colour names.

### Graph paper and the centile chart (signature)
Every chart is drawn on centile-chart paper: major lines on the y-axis ticks, minor lines dividing each major square into five (or two, when squares get small), the same pitch across, and a major-colour frame around the plot. The growth chart reproduces the boys' chart page in chart units (0.1 kg and one-week squares, heavier every kilo and every four weeks), with the nine centile lines 0.4th to 99.6th labelled at the right edge, the 50th heavier, and the baby's weigh-ins as a red line with paper-ringed dots on top.

### Milestone flags
Small flags for the baby's firsts, drawn over the graph paper in neutral annotation ink, so a flag never reads as a data series. Each is a dotted 1.2px rule in muted print ink (navy-print-2; dash 1 3, round caps) the full plot height, a 3.5px dot in the same ink on the plot's top edge with a 1.5px paper ring, and an 11px weight-600 label in print ink with a 3px paper halo. Labels sit beside the rule (to the right, or to the left near the right edge) in up to three stacked rows 15px apart, starting below any shaded band's label; a label that cannot fit without overlapping is dropped, and its rule and dot stay. In use: First N h and the longest so far on the longest-sleep chart, First pump and First formula on the milk chart, and Back to birth weight on the centile chart.

### Tooltip
Paper background, 1px strong rule, 4px corners, tooltip lift, label-size text with a bold title row and tabular values right-aligned against colour swatches. On touch it sits clear of the finger.

### Pip
On the dashboard, Pip appears only on the glance cards, one variant per card. On the landing, the hero Pip is a die-cut sticker (11rem) above the title. Pip never sits on record paper or in a chart.

## Do's and Don'ts

### Do:
- **Do** open every section with the 2px cover-red rule, the headline and an answer sentence before any chart.
- **Do** draw every new chart on the graph paper (minor and major lines, framed plot) with Public Sans axes at 11.5px, using only the chart inks with their fixed meanings (breast milk navy, pumped and sleep blue, formula and bottles marigold, breastfeeds rose) plus his own red, each at least 3:1 against its ground.
- **Do** present headline numbers on the record pages as record rows: small label above a large tabular value, hairline cells, square corners.
- **Do** keep a new glance card to the existing pattern: one of the five sticker fields, label, 800-weight number, bottom sub-line, its own Pip and rotation, and a link to its section.
- **Do** keep red for the cover, section rules, the active state, alerts and the one series or figure that is his own measure.
- **Do** keep dark mode on the oxblood-black paper (dark-record-paper) with the dark token set, never an inverted light theme.
- **Do** mark a new first or record on a chart with a milestone flag (dotted muted-ink rule, ringed top dot, haloed 11px label) rather than a callout box or icon; never draw a flag in a series ink.
- **Do** describe direct breastfeeding as history once the last logged breastfeed is more than 14 days before the export: its key and totals carry the end date ("Minutes breastfeeding a day, until <date>"; "The last one was on <date>").
- **Do** keep tap targets at 44px on the cover and at least 38px for chart controls, and keep every motion off under reduced motion.

### Don't:
- **Don't** use an NHS logo, wordmark, Frutiger or any claim of official status.
- **Don't** use rounded colour cards outside the glance strip; sheets and record rows stay square hairline paper.
- **Don't** put Pip on record paper or in charts, or let Pip lead a record page.
- **Don't** add shadows to sheets, rows, tabs or buttons; only the glance cards and the tooltip lift.
- **Don't** animate charts, record rows or tabs, or replay the count-up; it runs once per loaded export.
- **Don't** introduce a second typeface or set labels in uppercase or wide letter-spacing.
- **Don't** use the sticker field colours as chart series, add series colours outside the chart inks and his own red, or reassign an ink's meaning from one chart to the next.
