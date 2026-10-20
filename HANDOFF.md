# All American Carpeteers LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/allAmericanCarpeteers/ · **Repo:** https://github.com/10elizabethbell/allAmericanCarpeteers · **Built:** 2026-10-18 from Muse brief (run 2026-10-18) · **Revamped:** 2026-10-19 to the calm band style

## What changed in the revamp (2026-10-19)
The business hasn't been contacted yet, so the whole site was rebuilt to the new house default (`calm-photo-style.md`, learned from lpmr.co.uk), copying DPG Home Improvement's `index.html`.
- **Gone:** the cream-wall room, the self-cleaning carpet canvas hero with the wand, the carpet runners between sections, and the condensed system display font. That build is in git history at `0054f3f` if you want it back as an opt-in signature.
- **Look:** paper `#f4f6fb` and flag-navy bands (`#14346b`, deep `#0e2752` with the faint diagonal texture), with flag red `#c8102e` from the flyer as the one accent. Cal Sans headings, system body at 16/1.7, pill buttons and 24px cards.
- **Hero:** plain textured navy band. Eyebrow "Eco-friendly cleaning". H1 "Cleaner, fresher homes *in Randolph.*", which bounces in letter by letter. The flyer slogan "If you walk or sit on it, we clean it." is the promise line. Two buttons: **Get a quote** (filled, goes to the form) and **Text Vincent** (outlined, `sms:`). The number is only in the header's top-right corner.
- **Structure:** hero → "We clean your home like it's our own" (three flyer claims, Vincent Morea Owner / Operator, Facebook row) → "What we clean" arrow rows on navy (Carpet & fabric, Floors, Businesses) → How it works (3 steps) → quote form on deep navy → closing band (name, area, big tap-to-call number) → footer.
- **New: quote form.** Chips for the job (multi-select), name, town (optional) and notes (optional). It composes a text to 973-978-9516. Tapping a service row ticks its chip. Screen & recoat, refinishing and basement/garage also write their own note, so Vincent knows which job it is.
- **New: floating text circle** (red, bottom right). It shows after the hero and hides over the form and the closing band. Turn it off with `CONFIG.FLOAT`.
- **Motion:** the H1 bounce-in plus one 12px fade-up for things below the first screen. Under reduced motion or without JS, everything shows at once (checked).
- **New og image** (`og.jpg`, 1200×630) in the same navy/red look.

## What's built
- One single-file page, phone first. It was checked at 360, 390, 430 and 1440 in Chrome and WebKit: no sideways scroll, tap targets 44px+, and both quote buttons on the first phone screen.
- **Contact:**
  - `tel:+19739789516` ×3: header, closing band, and the form's fallback line.
  - `sms:` ×3: hero button, floating circle, and "Text and ask." in the closing band.
  - The form composes its own text (decoded and checked).
- **Facebook:** a row in the care section, plus the footer. There's no work-photo section to put it under.
- Favicon and home-screen icon: the flyer's star mark, rebuilt as vector.

## Assumptions I made
- **No photo hero and no work photos.** The flyer's before/after crops are about 210px wide, so they'd be blurry when blown up to a hero or a 4:5 card. Each pair also shows a different subject before and after, and they and the owner portrait look AI-generated (the shirt logo text is garbled). Using them would be soft and possibly untrue.
- **Red is the accent, not gold.** The flyer has no gold. Red is a fill with **white** text on it (5.9:1); the house rule's navy-on-accent would fail (about 2.5:1). On navy, red text is a lighter `#ff6670`, used only for large display text (4.3:1).
- **H1 is my wording.** "Cleaner, fresher homes" comes from their caption ("cleaner, fresher, and healthier"). The flyer slogan sits under it.
- **Voice is "we".** Their caption says "we", but the flyer says Owner/Operator. Switch to "I" if Vincent works alone.
- **How it works is inferred** (text or call → get your quote → we clean it). Nothing in the brief describes their process.
- **Claims are from the flyer's carpet panel** (deep low-moisture cleaning, deodorizing, organic solutions) and the caption (eco-friendly). The finish reviewer read "low-moisture" as hardwood-only from the brief's text, but on the flyer image it sits under CARPET CLEANING, so I kept it.

## Placeholders and gaps
- **Facebook:** no business page. Both links go to the owner's personal profile (`profile.php?id=100004055979808`, shown as "Dottore Morea", 403 for Muse), so visitors may hit a login wall.
- **No email anywhere:** none exists. Add it to the footer only.
- No hours, prices, reviews, years in business, insurance, or town list.
- **No real job photos.** This is the biggest gap. A work-photo section (4:5 cards, then "Click to see more of my work." to Facebook) would slot in after "What we clean".

## Questions for the owner
1. Can you send real before/after photos from your phone (same spot, before and after)? One could also become the hero background.
2. Do you have (or want) a Facebook business page we can link instead of your personal profile?
3. Which towns do you cover besides Randolph?
4. Is it just you, or a crew? (Decides "I" vs "we".)
5. Hours? Free estimates? Insured? Years in business? Any customer reviews we can quote?
6. Which services matter most? (Row order could lead with them.)
7. An email for the footer?

## Ideas not built (yours to pick)
- **Impeccable findings I kept against its advice** (your calm-style choices):
  - The eyebrow pills, which the craft floor bans: hero, services and form.
  - The H1 letter bounce-in.
  - The floating text circle.
  - Cal Sans.
  - The faint diagonal band texture. The detector flags it as `repeating-stripes-gradient`; this is suppressed for `index.html` in `.impeccable/config.json`.
- **Runner-up signature (opt-in):** the old self-cleaning carpet hero (a wand pulls nap stripes, and a finger takes over) at `0054f3f`. A second option: hardwood planks you buff to a shine.
- From the finish reviewer:
  - Use the star-and-stripes mark as a quiet motif (eyebrow dots, step numbers).
  - Fill the empty right half of the plain navy hero on desktop.
  - I left both alone, since the house rule says nothing extra in the hero.
- Before/after sliders under "What we clean" once real photos arrive (plain red divider).
- Atkinson Hyperlegible body text, if Vincent's customers turn out to skew 40+. Then also apply `older-audience.md`: no bounce-in and no fade-up.

## Not verified
- Real-device touch and the `sms:` handoff with the pre-filled body on iOS and Android, including inside Facebook's in-app browser.
- Field fills (`#e6ecf5` on white) are about 1.2:1 against the card. That's the house fix from DPG; each field has a visible label above it, but it isn't a WCAG 1.4.11 3:1 boundary.
