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
  button-share:
    backgroundColor: "{colors.record-paper}"
    textColor: "{colors.navy-print}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 14px"
    height: "40px"
  button-share-hover:
    backgroundColor: "{colors.record-paper-shade}"
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

Scope: this system governs the Red Book world shipped in `v2/index.html` and its Czech twin `v2/cs.html`, which is generated from the same source (a translation table, Czech grammar functions and a Czech d3 locale), so every rule here applies to both languages. The repo root's `index.html` and `cs.html` predate it (cream paper, Fraunces and Nunito, coloured cards) and are not governed by it.

## Overview

**Creative North Star: "The Red Book's Missing Chapter"**

The page is a record the parents keep beside the personal child health record: a red cover band across the top, white record paper beneath, navy print ink, and every chart drawn on the boys' centile-chart blue graph paper the health visitor already reads. It borrows the form of a printed record, not its authority: there is no NHS logo, wordmark, Frutiger or claim of official status.

The record pages are dense like a filled-in form. Each section opens with a red rule, a heading and an answer sentence, then printed record rows (small label above a large tabular value) and chart sheets framed by a hairline. The one exception, added at the parents' request, is a strip of six glance cards tucked half over the bottom of the cover band, like coloured stickers slipped into the book's front: warm field colours, soft corners, big numbers and a Pip on each, and each card opens its section. Below the tabs everything is flat paper and ink again. Outside the glance strip, the world still refuses the baby-tracker default of pastel rounded cards.

Light mode is white paper; dark mode is deep oxblood-black paper (the cover goes slightly deeper, the grid turns ink-blue on near-black, the navy chart ink becomes a warm pale stone so it differs in hue from the dark chart blue, the baby's own red brightens to stay legible, the card fields darken to deep marigold, sky, plum and navy). The colours switch on the band chooses follow device, always dark or always light (stored as 'sas-theme'): the dark set applies under prefers-color-scheme: dark unless the page is forced light (data-theme="light"), and always when forced dark (data-theme="dark"). Print is always the light palette. The direction contract named #170d0f for dark paper; the build ships #160c0f and that is the recorded value.

**Key Characteristics:**
- Red cover band at the top: the name and the band actions (language link, colours switch, Load newer export) on one row, then the export time, a this-week sentence in white, and a small line saying weekly figures are 7-day averages against the 7 days before.
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
  - **Navy ink** (series-ink; a warm pale stone in dark mode, distinct in hue from the dark blue): breast milk he drank, the 7-day average lines, the 2px outline on each night's longest stretch, feeds in busiest hours, and the first person in night feeds.
  - **Chart blue** (series-blue): milk pumped, sleep (including the sleep bands in the row-per-day rhythm chart and the last seven nights chart), pumps in busiest hours, and the second person.
  - **Marigold** (series-gold): formula, drawn as a solid line, never dashed; bottles in the rhythm and last-seven-nights charts, nappies in busiest hours, and the third person.
  - **Rose** (series-rose): direct breastfeeds, in the rhythm chart too, and the fourth person.
  - **Grey** (series-grey): an "other" or remainder bucket.
  - A dashed line at 0.65 opacity means only "4 weeks earlier": the comparison copy of a series, moved 28 days forward, in that series' ink and keyed with the dashed swatch. No other series is dashed.
  - Daily dots behind a 7-day average render at 0.75 opacity. Faded bars (weeks also breastfed, partial night weeks) fade only the fill (fill-opacity), never the outline or the ink itself. The old blue tint (--s-tint) is still defined in the stylesheet but no chart uses it, so it is not a system token.

### Tertiary
- **His Own Red** (series-own): the one series per chart that is the baby's own headline measure (weigh-ins on the centile chart, total he drank, ml per kg), the weight figure on the Weight card and the dot on its centile scale. In dark mode it lifts to a coral red (dark-series-own).
- **Sticker Fields** (card-marigold, card-sky, card-pink, card-navy, each with an ink and a secondary ink; white cards use record paper and navy print): the five glance-card fields. Marigold carries Age, sky carries Average milk a day (with a faint 14px graph-paper grid), pink carries Breast milk share, navy carries Average longest sleep, and white carries Weight and Average pumped a day. Dark mode uses the dark-card set, with a 1px inset edge (dark-card-white-edge, dark-card-navy-edge) on the white and navy cards so they separate from the paper.

### Neutral
- **Record Paper** (record-paper) and **Paper Shade** (record-paper-shade): the page and sheet ground; the shade fills table headers, hovered controls and loading skeletons.
- **Navy Print** (navy-print, navy-print-2, navy-print-3): body text, secondary labels and notes, and muted chart text and shading. Muted print ink (navy-print-2) is also the chart annotation ink: milestone-flag rules and dots, and dotted reference rules.
- **Form Rules** (form-rule, form-rule-strong): hairline sheet borders and dividers; the strong rule draws record-row cells, controls, table frames and axes.
- **Graph Paper** (grid-minor, grid-major): the chart grid; major lines also frame the plot area.

### Named Rules
**The Cover Red Rule.** Red belongs to the cover. On paper it appears only as the section rule, the active tab or segment, an alert, and his own measure; never as a fill for a sheet, card or ordinary series.

**The One Red Series Rule.** Red in a chart means only his own measure or an alert: at most one red series per chart (his weigh-ins, total he drank, ml per kg; a caveat version of the same series is allowed, as in the ml-per-kg "also breastfed" bars: a faded fill with a full-strength 1.5px red outline, keyed by an outlined tint swatch), plus alert marks such as a long daytime gap with no sleep logged. The dashed 0.65-opacity "4 weeks earlier" copy of his own measure counts as the same series, not a second red one. Every other series uses the chart inks with their fixed meanings. The glance cards are the one place the palette widens further: their sticker fields are backgrounds, never series, and never enter a chart.

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
- **Card label** (700, 0.9375rem; 0.8125rem on phones): the glance-card name, in sentence case. On phones Czech labels may wrap to two lines (line height 1.3); every label then reserves two lines (2.6em) so the numbers stay aligned across cards, and Pip drops to 52px from the top.
- **Record value** (700, 1.75rem, 1.15, tabular; 1.5rem in dense rows and on mobile): the numbers in record rows, with the unit at 0.9375rem, weight 500, in secondary ink.
- **Week sentence** (600, 1.0625rem, 1.45, white, max 62ch): the this-week sentence on the cover band, above a 0.8125rem explainer line in blush.
- **Lede** (400, 1.0625rem, 1.55, max 64ch): the answer sentence that opens each section; key figures in bold.
- **Body** (400, 1rem, 1.5): running text.
- **Label** (600, 0.8125rem): printed field labels, control text, legends, notes, card sub-lines and table headers. Sentence case; never uppercase, never letter-spaced.
- **Chart axis** (400, 11.5px, tabular): axis ticks and shade labels; centile labels are 600 at 11px. Row labels in the last seven nights chart are 700 at 12.5px, with a 500 11.5px sub-line.

### Named Rules
**The One Family Rule.** Public Sans sets everything, including chart axes and tooltips; no second face, no monospace.

**The Tabular Numbers Rule.** Every value, card number, table cell, axis label and tooltip uses tabular numerals so figures line up the way they do on a form.

## Layout

A single centred column (max 72rem) with 16px side padding, 32px from 768px up. The cover band is a small grid with no wordmark. On desktop the name and the actions row (language link, colours switch, Load newer export; 8px apart) share the first row, 20px apart, and the export time, the week sentence and the small 7-day explainer line run full width below. On phones the band text comes first and the actions sit in one row under it, 12px down, with the load button stretching to fill. When the export is more than 8 days old a white reminder tag appears under the band text. The glance strip pulls up 68px into the band (the band keeps 92px of bottom padding for it; 48px and 64px on phones), three cards across, two across under 900px, with a 14px gap (8px on phones). The Share this week as an image button and its status note sit under the cards. Then a sticky tab bar on paper with a hairline bottom rule holds the six sections (Since birth, Milk, Sleep, Growth, Shifts, Notes), with Since birth first, directly under the glance cards; on narrow screens it scrolls horizontally with a fade at the right edge. Each section is a record page: 44px above, a 2px red rule, the headline, the lede, then groups 28px apart.

Record rows are an auto-fit grid of cells at least 13rem wide; dense rows are three across. Under 600px they become two across, and an odd last cell spans both columns. Chart sheets stack 24px apart; pairs sit side by side when each can have 27rem, with a 20px gap, aligned to the top rather than stretched to equal height; otherwise they stack. Small-multiple charts use an auto-fit grid of 15rem minimum. The footer, behind a hairline, holds the privacy line, the link to the previous version and "Forget data on this device". Interactive targets are at least 44px on the cover and 38px for chart controls.

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
- **Secondary (Share this week as an image):** paper fill, 1px strong rule, 6px corners, 40px tall, 0.8125rem semibold print ink with a 16px stroked icon; hover fills with paper shade; disabled at 0.6 opacity while the image is made. A small status note in secondary ink sits beside it.
- **Print:** the same secondary style, on the growth sheet header and in the footer; it opens the health visitor printout.
- **Language link:** "Česky" / "English", an underlined 0.8125rem semibold text link in blush in the band actions (white on hover) and on the landing, 44px tall; the choice is remembered as 'sas-lang'.
- **Colours switch:** a 44px-tall outlined button in the band with a 1px translucent white outline (55%) and 6px corners, transparent fill (12% white on hover), showing its state in words (Auto, Dark, Light) beside a 20px icon; on phones only the word shows. It cycles follow device, always dark and always light.
- **Stale-export reminder:** a white tag with 4px corners and deep-red 0.8125rem semibold text ("This export is N days old…"), shown only when the export is more than 8 days old; hidden in print.
- **Forget link:** an underlined text button in the footer, in secondary ink, navy on hover.

### Glance cards (signature)
Six link cards, playful but organised, that answer "how is he doing" before the tabs: Age, Weight, Average milk a day, Breast milk share, Average pumped a day and Average longest sleep, each opening its section. Any card showing a 7-day average says "Average" in its label, on the page and in the share image.
- **Shape:** 16px corners (14px on phones), at least 158px tall on desktop, padding 16px 18px 18px (10px 12px 12px on phones).
- **Fields:** marigold, white, sky with a faint 14px graph-paper grid, pink and navy, each with its own ink and secondary ink in light and dark.
- **Content:** card label, an 800-weight number with its unit, and a sub-line at the bottom with the change in bold. Weight sets its number in his own red and adds a nine-tick centile scale (ticks in centile blue, the 50th heavier, a red dot ringed in the card colour where he sits). Breast milk share adds an 8px split bar: the filled share in the card ink over a 22% tint of it.
- **Pip:** one Pip variant per card (bib, tape, bottle, magnify, clock, sleep), 128px at the bottom right, each at its own rotation; sub-lines and bars stop short of it. On phones Pip moves up beside the number (64px wide, 36px from the top, 4px from the right) so it clears the longer labels.
- **States:** hover, focus and active lift the card 3px onto the card-lift shadow and wiggle the Pip; active settles back with a slight press. Focus-visible is a 3px ink outline, offset 3px, over a 3px white inner ring. Under reduced motion the wiggle and transitions are off.
- **Count-up (the page's one authored motion moment):** once per loaded export, each card number counts up from the week before (Weight from the previous weigh-in) to the current value over 1.1s with an exponential ease-out (1 - 2^(-10t)), and the breast-milk split bar grows from the prior share over the same 1.1s (cubic-bezier(.16, 1, .3, 1)). It never repeats on resize or redraw and is skipped entirely under prefers-reduced-motion.

### Segmented controls and date navigation
- **Style:** a 1px strong-rule frame with 6px corners, 38px tall, label-size semibold text in secondary ink, internal dividers in the strong rule.
- **State:** hover fills with paper shade; the pressed segment fills with cover red and white text. Arrow buttons and the date field share the frame and height.

### Compare checkbox
A native checkbox under the sheet title ("Compare with 4 weeks earlier"): 16px box with accent-color cover red, 0.8125rem semibold label in secondary ink, 32px tall. Ticking it adds the dashed 0.65-opacity copy of the main series moved 28 days forward.

### Navigation (section tabs)
- **Style:** sticky, paper background, hairline bottom rule; 0.9375rem semibold in secondary ink.
- **States:** hover darkens the text and shows a strong-rule underline; the current section shows navy text over a 3px cover-red underline.
- **Mobile:** horizontal scroll with no scrollbar and a right-edge fade.

### Record rows
Printed form fields, used for the Since birth totals (three dense rows under small headings: Milk, Pumping, Nappies and feeds) and for "Pumping, last 7 full days" in Milk (Sessions a day, Typical session, Time pumping a day, Milk per session), which sits above the pumping chart, carries a worded change against the 7 days before in each sub-line ("10 ml less than the week before", "Same as the week before"), and hides itself when the export has no pump entries. A grid of cells drawn with a shared 1px strong rule (top and left on the row, right and bottom on each cell), square corners, padding 9px 14px 14px. Inside: a small semibold label, the large tabular value with its unit, and a short sub-line in secondary ink with its key change in bold.

### Chart sheets
- **Corner Style:** square.
- **Background:** record paper.
- **Border:** 1px hairline (form-rule).
- **Internal Padding:** 16px 16px 12px (12px 12px 10px on mobile), 10px between title, legend, chart and the "How to read this chart" disclosure, whose chevron turns 90deg when open. The disclosure text refers to the key by name, never to colour names.

### Graph paper and the centile chart (signature)
Every chart is drawn on centile-chart paper: major lines on the y-axis ticks, minor lines dividing each major square into five (or two, when squares get small), the same pitch across, and a major-colour frame around the plot. The growth chart reproduces the boys' chart page in chart units (0.1 kg and one-week squares, heavier every kilo and every four weeks), with the nine centile lines 0.4th to 99.6th labelled at the right edge, the 50th heavier, and the baby's weigh-ins as a red line with paper-ringed dots on top.

### Row-per-day chart and the one-day timeline
The daily rhythm chart opens on One week on phones and on All days on larger screens. Its One day view lists the entries as a timeline: the time in bold, then an 8px dot per entry type before the entry (sleep blue, bottle marigold, breastfeed rose, pump navy ink, anything else grey).

### Tables
Hairline tables on paper with sticky paper-shade headers. The weigh-in table shows every row with no height cap. Any table that still scrolls has a small secondary-ink note under it giving the row count. On phones the weigh-in table and the days-left-out table in Notes stack: each row becomes a two-column record, with a small 11px semibold label from its heading above each value, and long text cells span both columns.

### Last seven nights chart
One 44px row per night from 19:00 to 07:00 on hourly graph paper (major line every 2 hours). Sleep is a chart-blue band; the night's longest stretch is outlined 2px in navy ink; bottles are 4px marigold marks with a paper edge. Each row has a bold 12.5px label and an 11.5px sub-line at the left, and the row fills with paper shade on hover.

### Milestone flags
Small flags for the baby's firsts, drawn over the graph paper in neutral annotation ink, so a flag never reads as a data series. Each is a dotted 1.2px rule in muted print ink (navy-print-2; dash 1 3, round caps) the full plot height, a 3.5px dot in the same ink on the plot's top edge with a 1.5px paper ring, and an 11px weight-600 label in print ink with a 3px paper halo. Labels sit beside the rule (to the right, or to the left near the right edge) in up to three stacked rows 15px apart, starting below any shaded band's label; a label that cannot fit without overlapping is dropped, and its rule and dot stay. In use: First N h and the longest so far on the longest-sleep chart, First pump and First formula on the milk chart, and Back to birth weight on the centile chart.

### Tooltip
Paper background, 1px strong rule, 4px corners, tooltip lift, label-size text with a bold title row and tabular values right-aligned against colour swatches. On touch it sits clear of the finger.

### Share image
A 1080px-wide PNG drawn in the light palette whatever the mode, 1314px tall for a sentence of up to three lines and growing with it: the cards start at max(404, 272 + (lines - 1) x 44 + 72)px and the cover-red band runs 116px past that start (520px at the base size). The band holds the name (800, 92px), "Week to <date>" in blush, labelled by the week's last full day, and the week sentence in white (600, 32px, 44px lines), then the six glance cards in a 2 x 3 grid with 30px corners, a soft oxblood shadow, the white cards edged in the hairline rule, and each Pip at the top right. It carries no footer text. It is shared through the native share sheet or downloaded.

### Health visitor printout
Two A4 pages with 12mm margins, always in the light palette, with the band colour forced to print.
- **Page 1:** a compact red band with the name, the export time, a print-only line saying it is a summary printed for the health visitor, and a print-only record row of six facts from the last 7 full days (Born, Age today, Feeds a day, Milk a day, Wet nappies a day, Dirty nappies a day). The row has white-ruled cells on the red, 8pt blush labels and 12pt white tabular values. The week sentence follows, then Growth: the centile chart at 260px tall and the full weigh-in table.
- **Page 2:** starts at Milk with feed mix and ml per kg (190px) side by side, then the pumping record row and the last seven nights at 30px rows.
- **Hidden on paper:** the cards, tabs, actions, footer, section summary sentences, the longest-sleep chart, the ml-per-kg footnote, every other chart, the how-to text and all controls.
- Charts are redrawn at the A4 width (186mm) before printing. Sheets, rows and the pumping table never break across pages (the weigh-in table may), and sheet borders print in the strong rule.

### Icon
Pip's head on cover red: a teal face (#2bb3a9), an orange hat (#f2711c) with a yellow band and pom-pom (#ffd84a), dark eyes with white highlights and pink cheeks. The SVG favicon has 112/512 rounded corners; the PNGs (512, 180 for the touch icon, 32) are full-bleed so the platform applies its own mask.

### Pip
On the dashboard, Pip appears only on the glance cards, one variant per card. On the landing, the hero Pip is a die-cut sticker (11rem) above the title. Pip never sits on record paper or in a chart.

## Do's and Don'ts

### Do:
- **Do** open every section with the 2px cover-red rule, the headline and an answer sentence before any chart.
- **Do** draw every new chart on the graph paper (minor and major lines, framed plot) with Public Sans axes at 11.5px, using only the chart inks with their fixed meanings (breast milk navy, pumped and sleep blue, formula and bottles marigold, breastfeeds rose) plus his own red, each at least 3:1 against its ground.
- **Do** present headline numbers on the record pages as record rows: small label above a large tabular value, hairline cells, square corners.
- **Do** label every weekly figure as an average ("Average milk a day"), on cards, rows and the share image alike.
- **Do** keep a new glance card to the existing pattern: one of the five sticker fields, label, 800-weight number, bottom sub-line, its own Pip and rotation, and a link to its section.
- **Do** keep red for the cover, section rules, the active state, alerts and the one series or figure that is his own measure.
- **Do** keep dark mode on the oxblood-black paper (dark-record-paper) with the dark token set, never an inverted light theme, and respect the stored colours choice over the device setting.
- **Do** write every new string for both languages; Czech copy is generated from the same source, so layouts must allow for longer Czech words (two-line card labels on phones).
- **Do** follow the Czech copy rules: decimal days take "dne"; decimal centiles have no ordinal dot ("0,4", "99,6"); centile positions read "na čáře 25. percentilu" or "mezi čarami 9. a 25. percentilu"; average cards name the average ("Vypité mléko denně (průměr)", "Odsáté mléko denně (průměr)").
- **Do** keep the printout to two light A4 pages limited to what a health visitor reads: the facts row and growth on page 1; feed mix, milk for size, pumping and the last seven nights on page 2.
- **Do** mark a new first or record on a chart with a milestone flag (dotted muted-ink rule, ringed top dot, haloed 11px label) rather than a callout box or icon; never draw a flag in a series ink.
- **Do** write every change against the week before out in full: "<amount> <unit> more/less/higher/lower/longer/shorter than the week before", and for weight "up/down <kg> since the weigh-in before"; never "on last week" or a bare signed number; no change reads "Same as the week before". In the week sentence, a change under 5% (0.25 h for sleep) reads "about the same", never "steady".
- **Do** describe direct breastfeeding as history once the last logged breastfeed is more than 14 days before the export: its key and totals carry the end date ("Minutes breastfeeding a day, until <date>"; "The last one was on <date>").
- **Do** keep tap targets at 44px on the cover and at least 38px for chart controls, and keep every motion off under reduced motion.

### Don't:
- **Don't** use an NHS logo, wordmark, Frutiger or any claim of official status.
- **Don't** use rounded colour cards outside the glance strip; sheets and record rows stay square hairline paper.
- **Don't** put Pip on record paper or in charts, or let Pip lead a record page.
- **Don't** add shadows to sheets, rows, tabs or buttons; only the glance cards and the tooltip lift.
- **Don't** dash any series other than the "4 weeks earlier" comparison.
- **Don't** animate charts, record rows or tabs, or replay the count-up; it runs once per loaded export.
- **Don't** introduce a second typeface or set labels in uppercase or wide letter-spacing.
- **Don't** use the sticker field colours as chart series, add series colours outside the chart inks and his own red, or reassign an ink's meaning from one chart to the next.
