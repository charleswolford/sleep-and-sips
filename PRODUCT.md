# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users
Two parents looking after their baby son. They use the page in four situations, all confirmed:
- a quick check on a phone, often tired or at night, to see how he is doing right now;
- a weekly look-back, sitting down to see how sleep, feeds and pumping have trended;
- health visitor appointments, showing growth and feeding to a professional;
- splitting the load, working out who covers which hours and nights.

## Product Purpose
Sleep and Sips turns a Nara Baby CSV export into charts of a baby's sleep, feeds, pumping, nappies and growth. Success is that either parent can answer "how is he doing, and is anything changing?" in seconds, and can go deeper when they want to.

## Positioning
Nara Baby logs events; it does not answer the questions these parents actually ask: is enough breast milk being pumped to cover what he drinks, is the night getting longer, which hours need an extra pair of hands, and is he tracking his WHO centile. The page reads the export entirely on the device: nothing is uploaded.

## Operating Context
- Data arrives as a fresh CSV export from the Nara Baby app every few days (columns such as Type, Start Date/time, Created By Caregiver, [Pump] Total Volume, [Sleep] Duration (Seconds), [Bottle Feed] Breast Milk Volume, [Growth] Weight).
- On a phone the parent taps a button and picks the file from Files; on a computer they can drag it onto the page. The data can be remembered on the device and cleared with "Forget data on this device".
- Hosted on GitHub Pages at charleswolford.github.io/sleep-and-sips (noindex). The new version lives as a separate page in the same repo; the current index.html and cs.html stay as they are.

## Capabilities and Constraints
- Static HTML, CSS and JavaScript in a single file, d3 v7 inlined, WHO weight-for-age table for boys (0 to 730 days) inlined. No server, no network calls for data.
- Data logic already proven in the current page: split bottles within 20 minutes joined as one feed; partial days (birth day, export day) left out; days with a daytime gap over 6 hours with no sleep logged left out of sleep charts; wake gaps over 5 hours treated as missed logs; weeks start on Monday; times are UK local.
- Charts in the current page: milk pumped vs drunk (7-day rolling), pumping and breastfeeding time per day, daily rhythm (noon-to-noon or midnight-to-midnight, all days / week / day), longest and total sleep, wake windows by part of day, ml per kg per day, feed mix by week, weight vs WHO centile bands, busiest hours, night feeds by caregiver, data-quality list.
- Caregiver attribution is by who logged the entry, which is not always who did the care.
- English first for the new version. The current page also ships Czech (cs.html, with a language switch); Czech for the new version comes later.

## Brand Commitments
- Name: Sleep and Sips.
- Pip, a caterpillar mascot, appears in the current page. Whether Pip stays in the new version is left to the design round.
- Copy is warm, direct and explanatory, written for tired parents, and it defers to the health visitor on interpreting growth.

## Evidence on Hand
- Real exports from Nara Baby, kept on the parents' own devices. This is personal data and must never be committed or published.
- WHO Child Growth Standards weight-for-age, boys, expanded daily table (inlined in the current page).
- No testimonials or claims exist and none should be invented.

## Product Principles
- Answer the question first, then show the chart that proves it.
- Honest about the data: say what is estimated, left out or attributed by logger.
- Private by construction: the file never leaves the device.
- Works one-handed on a phone at 3am as well as on a laptop at the weekend.

## Accessibility & Inclusion
Used by tired people in low light on phones: legible sizes, strong contrast, large tap targets, and both light and dark modes.
