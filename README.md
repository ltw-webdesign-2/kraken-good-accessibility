---
summary: 'Fix some accessibility problems for VoiceOver & make sure the document prints properly.'
time: '1 hour'
deliverables: '1 HTML file, 3 CSS files, images'
---

# Kraken good accessibility

## Overview

- *Fork this repository.*
- Fix a few accessibility problems:
  1. Add the appropriate ARIA landmark roles to tags in the HTML.
  2. Add proper `aria-label` attributes to the navigation items to make them sound better in VoiceOver; also consider `role="presentation"` to hide unnecessary items from VoiceOver.
  3. Make a few small tweaks to the print styles for better paper accessibility; both in the CSS & HTML with [Modulifier’s print classes](https://learn-the-web.algonquindesign.ca/topics/modulifier-cheat-sheet/#print-styles).
- *Run it through Markbot and make sure it passes all the checks.*

---

## Details

- *Colours:* `#000` (for print)

---

## Goal

Visually match the images in the “screenshots” folder.

- Final screenshots in the “screenshots” folder.

---

## Hand in

Drop this folder into your Markbot application. Make sure to fix all the errors. And submit for grades using Markbot.
