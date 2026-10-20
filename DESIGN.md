---
name: All American Carpeteers LLC
description: A calm band pitch site in the flyer's flag navy and red, built to get a text to Vincent.
colors:
  paper: "#f4f6fb"
  card-white: "#ffffff"
  field-mist: "#e6ecf5"
  deep-navy: "#0e2752"
  flag-navy: "#14346b"
  body-slate: "#26364c"
  soft-slate: "#4a5868"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c9d7ea"
  flag-red: "#c8102e"
  flag-red-deep: "#a80d27"
  red-lite: "#ff6670"
  error-red: "#b3261e"
  hairline: "rgba(14,39,82,.12)"
typography:
  display:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  phone-display:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
  title:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  row-title:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(18px, 4.9vw, 20px)"
    fontWeight: 400
    lineHeight: 1.2
  label:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  button:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  field: "10px"
  row-card: "20px"
  card: "24px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  section: "64px"
  section-wide: "96px"
  stack-sm: "16px"
  stack-md: "28px"
  stack-lg: "36px"
  column-gap: "64px"
components:
  button-primary:
    backgroundColor: "{colors.flag-red}"
    textColor: "{colors.card-white}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.flag-red-deep}"
    textColor: "{colors.card-white}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  input-field:
    backgroundColor: "{colors.field-mist}"
    textColor: "{colors.deep-navy}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field-mist}"
    textColor: "{colors.deep-navy}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.deep-navy}"
    textColor: "{colors.card-white}"
  form-card:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.body-slate}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  link-row-card:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.deep-navy}"
    typography: "{typography.row-title}"
    rounded: "{rounded.row-card}"
    padding: "14px 16px 14px 22px"
    height: "72px"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.row-title}"
    padding: "10px 0"
    height: "64px"
  arrow-disc-active:
    backgroundColor: "{colors.flag-red}"
    textColor: "{colors.card-white}"
    rounded: "{rounded.circle}"
    size: "44px"
  step-number:
    backgroundColor: "{colors.flag-red}"
    textColor: "{colors.card-white}"
    rounded: "{rounded.circle}"
    size: "48px"
  float-circle:
    backgroundColor: "{colors.flag-red}"
    textColor: "{colors.card-white}"
    rounded: "{rounded.circle}"
    size: "60px"
---

# Design System: All American Carpeteers LLC

## Overview

**Creative North Star: "The Flag-Folded Flyer"**

The page is the owner's flyer put in calm order: off-white paper bands alternate with the flyer's flag navy, and flag red is the one warm voice. Each band does one job (who and where, how we treat your home, what we clean, how it works, ask for a quote, call), stacked in a single phone-width column that opens into two columns on desktop. Nothing is there to decode; a homeowner scrolling inside Facebook's in-app browser should find their job and text Vincent without a second look.

The house calm band style sets the grammar: full pill buttons, rounded white cards only where something is filled in, hairline-divided rows instead of boxed cards, a rounded display face (Cal Sans at weight 400) over a system body. Depth comes from band colour and a faint diagonal line texture on the navy bands, not from shadows. The only motion is the hero H1 bouncing in letter by letter and a 12px fade-up for content below the first screen.

There are no photos. The flyer's before/after pairs are about 210px wide, show different subjects before and after, and are not real work, so the build uses band colour, the rebuilt star mark and line icons instead.

**Key Characteristics:**
- Paper and navy bands, flag red as the single accent
- Cal Sans 400 display, system sans body at 16/1.7
- Pills for actions, 24px cards for the form, hairline rows for lists
- Faint 135-degree line texture on navy bands as the only surface detail
- Flat: one shadow in the system, on the floating text circle
- Motion limited to the hero H1 bounce-in and a 12px fade-up, both off for reduced motion and no JS

## Colors

Flag navy and flag red from the flyer on cool off-white paper; red is rationed so it always means "act here".

### Primary
- **Flag Navy** (`flag-navy`): the flyer's navy. Hero band (with line texture) and the services band. Also the focus and hover outline colour on light surfaces, chosen so focus never reads as the red fill. Fills the star in the wordmark.
- **Deep Navy** (`deep-navy`): two jobs at one value. As a surface it is the quote and footer band, always with the line texture. As ink it is every heading, label and selected chip on light surfaces.

### Secondary
- **Flag Red** (`flag-red`): primary button fill, step numbers, the floating text circle, the arrow disc on hover/focus, icon strokes on light (claims, phone glyphs), the inline "Text and ask." link, and text selection. Always paired with white text when it is a fill (5.9:1). Red text sits on light surfaces only (5.4:1).
- **Flag Red Deep** (`flag-red-deep`): primary button hover fill. Nowhere else.
- **Red Lite** (`red-lite`): red as display text on navy only: the accent last phrase of a dark-band heading (4.3:1, large text only), the eyebrow dot on dark bands, and footer link hover (5.2:1).

### Neutral
- **Paper** (`paper`): page ground, header, and the light bands. Also the `theme-color`.
- **Card White** (`card-white`): the quote form card and the Facebook link row; text on every red fill.
- **Field Mist** (`field-mist`): text inputs, textarea and unselected chips inside the white form card.
- **Body Slate** (`body-slate`): running text on light.
- **Soft Slate** (`soft-slate`): ledes, secondary lines, placeholders, step descriptions, optional markers.
- **On Dark** (`on-dark`): headings, row titles and ghost button text on navy.
- **On Dark Soft** (`on-dark-soft`): running text and row sub-lines on navy.
- **Hairline** (`hairline`): dividers between rows on light. On navy the divider is `rgba(255,255,255,.12)`.
- **Error Red** (`error-red`): field error text and invalid-field borders. Distinct from the brand red so an error never looks like a button.

### Named Rules
**The White-on-Red Rule.** Flag red as a fill always carries white text. Navy on red fails contrast and is never used.

**The Lite-Red-Is-Large Rule.** Red Lite appears on navy only, and only as display-size text (the heading accent phrase), a dot, or a footer hover. Never body text, never on paper.

**The Accent-Means-Act Rule.** Red marks actions and the path to them: the quote button, the text circle, step numbers, the active arrow, phone glyphs. Decoration does not get red.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** system sans (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** Cal Sans is round, friendly and confident at a single weight; it carries every heading, label, button, row and phone number so the page reads as one voice. The system body keeps paragraphs fast and familiar.

### Hierarchy
- **Display** (400, clamp 42-80px, line-height 1.02, max 12ch): the hero H1 only, in white, with its last phrase in Red Lite.
- **Headline** (400, clamp 30-48px, 1.08): section H2s. On dark bands the last phrase may be in Red Lite.
- **Phone Display** (400, clamp 30-52px, 1): the closing tap-to-call number, with a red phone glyph at 0.8em.
- **Title** (400, clamp 20-24px, 1.15): claims list items and service group H3s (24px).
- **Row Title** (400, clamp 18-20px, 1.2): service rows and the Facebook row. Step titles run 21px (22px desktop) in the same face.
- **Label** (400, 17px, 1.2): form labels and legends, header wordmark (17/19/22px by width) and header phone (17px, 20px desktop).
- **Button** (400, 18px, 1): all pill buttons.
- **Lede** (400, clamp 17-19px, 1.7, max 38ch): the paragraph under a section heading. The hero promise is the same family at clamp 17-20px, line-height 1.5, max 30ch.
- **Body** (400, 16px, 1.7): running text and every input (16px so iOS does not zoom).
- **Small** (400, 15px, 1.4): row sub-lines, owner role, error text, form footnote.

### Named Rules
**The One-Weight Display Rule.** Cal Sans is used at 400 only; hierarchy comes from size, never from faux bold.

**The Balanced Heading Rule.** Headings use `text-wrap: balance` and tight line-height (1.02-1.08) with -0.005em tracking.

## Layout

Single column at phone width inside a 1160px max container with a 20px gutter (40px from 760px). Sections pad 64px top and bottom, 96px from 760px; the hero pads 56/68px, 96/112px on desktop. Section heads stack on a 16px gap with a 640px measure.

Breakpoints: 359px and below hides the star and phone glyph in the header; 400px enlarges the wordmark; 760px widens gutter and section padding, puts hero buttons side by side (240px min) and service groups in two columns (64px gap); 1024px splits the care band (copy left, claims right), puts the quote heading in a sticky left column beside the form (1fr / 1.2fr), aligns the closing band as name left and big phone right, and lays the three steps in a row.

Rhythm: 16px inside stacks, 28px before lists and cards, 36px before groups and steps, 64px between desktop columns. Tap targets are at least 44px everywhere; the header respects safe-area insets and the footer reserves 96px at the bottom so the text circle never covers content.

## Elevation & Depth

Flat. Depth is band colour (paper, flag navy, deep navy) plus the line texture on navy surfaces. Cards are white on deep navy or paper with no shadow; the Facebook row and service rows explicitly suppress shadows on hover and focus.

### Shadow Vocabulary
- **Float lift** (`box-shadow: 0 10px 28px rgba(8,24,46,.3)`): the floating text circle only, because it sits over moving content.

### Named Rules
**The Line-Texture Rule.** Navy bands that frame the page (hero, quote, footer) carry `repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`. The services band stays plain flag navy so its rows read cleanly. Paper bands are never textured.

**The One-Shadow Rule.** The text circle is the only element with a shadow.

## Shapes

Soft and round throughout. Actions are full pills (999px): buttons, chips. Fill-in surfaces are rounded rectangles: the form card at 24px, the Facebook row at 20px, inputs at 10px. Indicators are circles: the 44px arrow disc, 48px step numbers, the 60px text circle. Lists use 1px hairline dividers rather than boxes. Line icons are 2.2-2.6px rounded strokes. The brand mark is the flyer's five-point star with a white and a red diagonal stripe clipped inside it.

## Components

### Buttons
Round, plain, and big enough to hit with a thumb.
- **Shape:** full pill, 56px tall, 26px side padding, 2px border, Cal Sans 18px; optional 20px leading icon.
- **Primary:** flag red fill, white text. Hover (pointer devices only): flag red deep. In the form it is full width and gains a 3px flag navy outline at 3px offset on hover and focus.
- **Ghost (dark bands only):** transparent with a 70% on-dark border and on-dark text; hover goes to a white border and 10% white fill.
- **Press:** scales to 0.98 over 120ms. Colour changes take 200ms.

### Chips
- **Style:** checkbox chips in the quote form. Field mist pill, 46px tall, 16px padding (13px at 380px and below), system 16px deep navy text, 2px transparent border.
- **State:** hover and keyboard focus draw a flag navy border; selected is deep navy fill with white text; selected plus focus adds a 3px outline. The real checkbox is visually hidden, not removed.

### Cards / Containers
- **Quote form card:** white, 24px radius, clamp 20-32px padding, 20px internal gap, max 600px, no border, no shadow. Sits on the deep navy band.
- **Link row card (Facebook):** white, 20px radius, 72px tall, max 440px, label with a 28px navy icon on the left, arrow disc on the right.

### Inputs / Fields
- **Style:** field mist fill, 10px radius, 2px transparent border, 52px min height (textarea 110px, vertical resize), 16px system text in deep navy, navy caret, soft slate placeholder.
- **Focus / hover:** border turns flag navy (150ms); no glow.
- **Error:** border and a 15px message in error red, shown only after submit. Messages use `role="alert"`; the first failing field takes focus.

### Navigation
- **Header:** paper bar, 64px (76px desktop). Star wordmark left (two stacked Cal Sans lines, small spaced "LLC"), tap-to-call number right with a red phone glyph; number turns red on hover. No menu.
- **Footer:** deep navy with line texture, on-dark-soft 16px text, on-dark links at 44px height, Red Lite on hover.

### Claims List
Three Cal Sans lines on paper, each led by a 40px red line icon, separated by hairlines. Points, not cards.

### Service Arrow Rows (signature)
Lists of jobs on flag navy grouped under 24px H3s. Each row is a 64px link: row title on the left (optional 15px on-dark-soft sub-line), a 44px arrow disc on the right at 10% white. On hover or focus only the disc changes, to flag red with white arrow (focus adds a 3px white outline); the row itself never gets a background or shadow. Tapping a row ticks the matching chip in the quote form and, where rows share a chip, appends a note naming the job to the textarea.

### Numbered Steps
Three steps, each a 48px flag red circle holding a Cal Sans counter, beside a 21px title and a soft slate line. Stacked on phones, three across at 1024px.

### Quote Form (signature)
Chips, name, optional town, optional note, then "Text this to Vincent". Submitting validates (something picked or written, and a name), then composes the message and opens `sms:` with it as the body. After 900ms a status line appears with the phone number in case no messages app opened. A footnote says the button opens your messages.

### Closing Band
Paper band: business name as an H2, the "Cleaning · Restoration · Floor care" line, the service area with an inline red "Text and ask." link, and the Phone Display number with a red glyph.

### Floating Text Circle
One 60px flag red circle, bottom right inside safe-area insets, white chat icon, Float lift shadow. It slides up from 120px off-screen (350ms, `cubic-bezier(.2,.8,.2,1)`) once the hero is out of view and hides while the quote form or closing band is on screen; when hidden it leaves the tab order and is `aria-hidden`. Removed if IntersectionObserver is missing or the config turns it off. Never a bottom bar.

### Eyebrow Pills (owner exception)
Three uses, kept because the owner chose LPMR-style eyebrows for the house style on 2026-10-19, against Impeccable's ban on eyebrows. A 14px weight-500 system label in a faint pill (6% navy on paper, 12% white on navy) with a 7px dot (flag red on light, Red Lite on dark). Marked up as `<p>`, never a heading; no arrow, hover or shadow, so it can't read as a button. This records the existing exception; it is not a pattern to add to new surfaces without the owner asking.

### Motion
- **H1 bounce-in:** JS splits the hero H1 into letters (words kept unbreakable). Each letter slides in from 50px right and fades in over 1s on `cubic-bezier(.34,1.56,.64,1)` (the overshoot is the bounce), staggered 20ms. When the last letter lands the plain heading is restored so kerning and selection return; an `aria-label` carries the text while it is split.
- **Fade-up:** elements marked to rise are visible at rest. Only those starting below the first screen are set 12px down at opacity 0, then rise over 400ms ease-out as they enter view (8% bottom inset), once.
- **Reduced motion:** no letter split, no fade-up, no transitions on buttons or the text circle, no smooth scroll.
- **No JS:** the H1 stays plain and nothing starts hidden, because both the letter split and the below-the-fold hidden state are applied by script; the text circle never appears.

## Do's and Don'ts

### Do:
- **Do** put white text on every flag red fill, and keep red text on light surfaces only.
- **Do** keep Red Lite for display-size accent phrases and dots on navy, and footer link hover.
- **Do** use flag navy for focus and hover outlines on light surfaces and white outlines on dark ones (3px, 3px offset).
- **Do** alternate paper and navy bands, with the 135-degree line texture on the hero, quote and footer bands.
- **Do** use Cal Sans 400 for headings, labels, buttons, rows and phone numbers, and the system stack at 16/1.7 for running text.
- **Do** list jobs as hairline-divided rows where only the arrow disc changes on hover and focus.
- **Do** keep hover styles inside `@media (hover:hover)` so taps don't leave them stuck.
- **Do** keep every tap target at least 44px and every input at 16px or larger.
- **Do** keep motion to the H1 bounce-in and the 12px fade-up, both off under reduced motion and without JS.

### Don't:
- **Don't** put navy text on a red fill; it fails contrast.
- **Don't** use Red Lite as body text or on paper.
- **Don't** use the flyer's before/after images or owner portrait, or stand-in photos; there are no real work photos.
- **Don't** add shadows beyond the floating text circle.
- **Don't** give service rows or the Facebook row a hover background or shadow; only the arrow disc changes.
- **Don't** turn the text circle into a bottom bar or show it over the form or closing band.
- **Don't** add new eyebrow pills beyond the owner's existing exception.
