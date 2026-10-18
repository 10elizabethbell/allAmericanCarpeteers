---
name: All American Carpeteers LLC
description: A one-room pitch site where the hero is a carpet you clean yourself.
colors:
  flag-navy: "#14346b"
  navy-deep: "#0e2752"
  flag-red: "#c8102e"
  red-deep: "#a50d26"
  wall-cream: "#f6f1e7"
  paper: "#fffdf8"
  ink: "#1c2433"
  ink-soft: "#4a5468"
  pile-oatmeal: "#d3c7b1"
  rule-cream: "#e6dfd1"
  arrow-well: "#ece6da"
  on-navy: "#e9eef8"
  white: "#ffffff"
typography:
  display:
    fontFamily: "\"Avenir Next Condensed\", \"Arial Narrow\", \"sans-serif-condensed\", system-ui, sans-serif"
    fontSize: "clamp(64px, 20.5vw, 148px)"
    fontWeight: 800
    lineHeight: 0.88
    letterSpacing: "0.005em"
  slogan-lead:
    fontFamily: "\"Avenir Next Condensed\", \"Arial Narrow\", \"sans-serif-condensed\", system-ui, sans-serif"
    fontSize: "clamp(25px, 7.4vw, 40px)"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "0"
  headline:
    fontFamily: "\"Avenir Next Condensed\", \"Arial Narrow\", \"sans-serif-condensed\", system-ui, sans-serif"
    fontSize: "clamp(36px, 10vw, 64px)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "0.005em"
  title:
    fontFamily: "\"Avenir Next Condensed\", \"Arial Narrow\", \"sans-serif-condensed\", system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "0.005em"
  numeral:
    fontFamily: "\"Avenir Next Condensed\", \"Arial Narrow\", \"sans-serif-condensed\", system-ui, sans-serif"
    fontSize: "58px"
    fontWeight: 800
    lineHeight: 0.8
  lede:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(18px, 4.8vw, 21px)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  row:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 600
  label:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    letterSpacing: "0.08em"
rounded:
  focus: "6px"
  button: "12px"
  round: "50%"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  section: "64px"
  section-wide: "96px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.flag-red}"
    textColor: "{colors.white}"
    rounded: "{rounded.button}"
    padding: "0 26px"
    height: "58px"
  button-primary-hover:
    backgroundColor: "{colors.red-deep}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.flag-navy}"
    rounded: "{rounded.button}"
    padding: "0 26px"
    height: "58px"
  button-ghost-hover:
    backgroundColor: "{colors.flag-navy}"
    textColor: "{colors.white}"
  phone-link:
    textColor: "{colors.flag-navy}"
    typography: "{typography.title}"
    height: "44px"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.row}"
    padding: "8px 0"
    height: "60px"
  service-arrow:
    backgroundColor: "{colors.arrow-well}"
    textColor: "{colors.flag-navy}"
    rounded: "{rounded.round}"
    size: "38px"
  service-arrow-hover:
    backgroundColor: "{colors.flag-red}"
    textColor: "{colors.white}"
---

# Design System: All American Carpeteers LLC

## Overview

**Creative North Star: "The Freshly Cleaned Room"**

The page is one room seen from the doorway: a warm cream wall at the top, a white baseboard, and wall-to-wall carpet below it. Everything above the baseboard is the business talking (who, the slogan, how to reach Vincent). Everything below is the trade itself, simulated: soiled pile that a steel cleaning wand works in pull strokes, each stripe laid down wet and drying bright, with the soil slowly creeping back so there is always more to clean. A finger or mouse can take the wand. Bound carpet runners recur between sections as the carried motion, so the room keeps going as you scroll.

The voice is a straightforward trades pitch with a patriotic sign-off. Flag navy and flag red come straight from the client's flyer and star mark; they sit on cream and paper, never on black. Type is heavy, condensed and uppercase for headings (the flyer's lettering, on a system font stack by house rule), with plain sentence-case body underneath. Density is phone-first: single column, large tap targets, every action a text message or call.

Depth is physical rather than decorative: the baseboard and runners cast short warm shadows onto the floor, and the primary button carries a soft red glow. Nothing else floats.

**Key Characteristics:**
- Room composition at every width: wall above, baseboard, carpet floor below.
- Flag navy + flag red on cream and paper; navy fields for the "our voice" section and footer.
- Heavy condensed uppercase display, plain sentence-case body, system fonts only.
- A live canvas carpet is the signature; runners repeat it as section dividers.
- Texting is the main door: one filled red "Text for a quote" button, everything else outlined or text.

## Colors

A two-flag palette (navy carries structure, red carries action) set on a warm cream room.

### Primary
- **Flag Navy** (`flag-navy`): Headings, wordmark, header phone number, ghost-button border and text, the group rule under each service group, runner bindings, the full-bleed "how we treat your home" field, and the blue band on the wand head. The structural color of the site.
- **Deep Navy** (`navy-deep`): Footer field and the stripe inside the reversed footer star. Only ever a darker floor under navy-adjacent content.

### Secondary
- **Flag Red** (`flag-red`): Action and emphasis. The primary button fill, the slogan lead-in, step numerals, the star bullets, the phone icon, the hover state of service-row arrows and text links, and the focus ring.
- **Deep Red** (`red-deep`): Primary-button hover only.

### Neutral
- **Wall Cream** (`wall-cream`): The room's wall. Page background, header, hero copy, the "How it works" and close sections. Also the browser `theme-color`.
- **Paper** (`paper`): Lifted reading surfaces: the services list, the runner bay beneath it, and the service-area section. Alternates with wall cream to pace the scroll.
- **Ink** (`ink`): Body text and service-row labels.
- **Soft Ink** (`ink-soft`): Supporting copy: the promise, row sub-lines, step details, the close paragraph, the drag hint.
- **Pile Oatmeal** (`pile-oatmeal`): Base color of every carpet (hero floor and runners) and the canvas fallback background. The carpet's own tuft shades (`#bfb299` to `#f1eadc`) live inside the simulation and are not page colors.
- **Rule Cream** (`rule-cream`): 1px dividers between service rows.
- **Arrow Well** (`arrow-well`): Resting fill of the round arrow in each service row.
- **On-Navy** (`on-navy`): Body and lede text on the navy field. Headings and list items on navy are pure white.

### Named Rules
**The Cream Wall Rule.** Light surfaces are wall cream or paper; there is no dark mode and no black field. The darkest surface is deep navy, and only in the footer.

**The One Red Door Rule.** Exactly one filled red button per view: "Text for a quote". Every other button is a navy ghost. Red elsewhere is small: numerals, star bullets, icons, hover and focus.

## Typography

**Display Font:** Avenir Next Condensed (with Arial Narrow, `sans-serif-condensed`, system-ui fallback), always `font-stretch: condensed`
**Body Font:** system-ui (with -apple-system, Segoe UI, Helvetica Neue, Arial)

**Character:** The display is the flyer's lettering: heavy, condensed, uppercase, tightly leaded, set in navy like a truck door. The body is the phone's own font, plain and sentence case, so it reads like a text from Vincent.

### Hierarchy
- **Display** (800, clamp(64px, 20.5vw, 148px) on phones, clamp(84px, 9.2vw, 140px) at 900px+, 0.88): "We clean it." Only the hero slogan.
- **Slogan Lead** (700 italic, clamp(25px, 7.4vw, 40px), 1.05, sentence case, red): "If you walk or sit on it," set directly above the display as the first half of the same sentence. The italic condensed voice also signs Vincent's name (34px, white) on the navy field.
- **Headline** (800, clamp(36px, 10vw, 64px), 0.95, uppercase, navy): Section headings. The service-area place name (clamp(46px, 14vw, 104px)) and the closing line (clamp(44px, 13vw, 96px)) are the two sanctioned oversize headlines.
- **Title** (800, 22px, uppercase, navy): Service group names, each underlined by a 2px navy rule. The header phone number uses the same condensed 800 at 19px (24px at 900px+).
- **Numeral** (800, 58px, 0.8, red): Step counters in "How it works".
- **Lede** (400, clamp(18px, 4.8vw, 21px), 1.5, max 30-34em): Opening paragraph of a section. The hero promise runs a step smaller (clamp(17px, 4.6vw, 20px), 1.45).
- **Body** (400, 17px, 1.55): Everything else. `text-wrap: pretty` on paragraphs, `balance` on headings.
- **Row** (600, 18px): Service row labels; optional 15px/400 soft-ink sub-line.
- **Label** (400, 14-15px, 0.08em, uppercase): Only for the owner's role under his signature and the flyer's tagline in the footer. Never above a heading.

### Named Rules
**The Shout and Say Rule.** Headings shout (condensed, 800, uppercase); everything else says (system body, sentence case). Nothing in between: no light display weights, no uppercase body paragraphs.

**The House Fonts Rule.** No webfonts. Display and body are system stacks by Ellie's pitch-site rules; the condensed character comes from `font-stretch` and the stack order, not a download.

## Layout

Phone-first single column inside a 1180px container with a 20px gutter (40px at 900px+). Sections pad 64px top and bottom (96px at 900px+). Section backgrounds alternate wall cream, paper and navy to pace the scroll; runner strips sit at two of the seams.

The hero is a fixed room stack at every width: header (68px, 84px at 900px+), hero copy, an 18px baseboard, then the floor at clamp(270px, 46svh, 470px) (clamp(320px, 44svh, 520px) at 900px+). At 900px+ the hero copy splits 1.15fr / 1fr with the slogan left and the promise and actions bottom-aligned right; the floor stays full-bleed.

Breakpoints: 600px (action buttons go side by side, min-width 230px), 900px (two-column sections, services flow into two CSS columns with 56px gap, footer becomes 1.4fr / 1fr / 1fr), and a sub-360px tightening that drops the phone icon and shrinks the mark.

Tap targets are at least 44px everywhere (header links, footer links, inline text links get 11px vertical padding); buttons are 58px and rows 60px.

### Named Rules
**The Room Order Rule.** Wall above, baseboard, carpet below, at every width. The floor is never moved beside the copy or cropped into a card.

**The Static Header Rule.** The header scrolls away with the page. No sticky bar, no floating call button; the reach-out moments are the hero, the service rows and the close.

## Elevation & Depth

Flat by default. Depth exists only where the room is physical: the baseboard and runners throw short, warm-brown shadows onto what is below them, and the wand casts its own shadow on the pile inside the canvas. The primary button carries a soft red under-glow so the one red door reads as pressable. No cards, no hover lifts.

### Shadow Vocabulary
- **Baseboard cast** (`box-shadow: 0 5px 7px -2px rgba(60,45,25,.28)`): Under the baseboard, onto the floor. Paired with a vertical gradient (#fff to #fbf8f2 to #e9e2d4) that gives the board its rounded top.
- **Runner cast** (`box-shadow: 0 3px 5px -1px rgba(60,45,25,.3)`): Under each runner strip.
- **Red glow** (`box-shadow: 0 6px 16px -6px rgba(200,16,46,.55)`): Primary button only.

### Named Rules
**The Warm Shadow Rule.** Shadows are warm brown (rgb 60,45,25), short and soft, and only fall from room objects. Never grey, never hard-offset, never on content boxes.

## Shapes

Gently rounded action shapes (12px buttons), perfect circles for row arrows (38px), and square edges for everything architectural: baseboard, runners, section fields and rules are all straight-edged and full-bleed. Rules are navy 2px under group titles, rule-cream 1px between rows, and 7px navy bindings top and bottom on runners. The star mark (navy star clipped with a white and a red stripe) is the only emblem; on navy it inverts to a white star with a deep-navy stripe, and plain red stars serve as list bullets. Icons are 22px stroke SVGs (2px, round caps and joins) in `currentColor`; brand icons are filled.

## Components

### Buttons
Big, plain and thumb-sized.
- **Shape:** gently rounded (12px), 2px border, 58px tall, 26px side padding, 800 18px system font (not the display face), optional 22px leading icon.
- **Primary:** flag red fill and border, white text, red glow. Used only for "Text for a quote".
- **Hover / Focus:** primary deepens to red-deep; ghost fills navy with white text. Colors ease over .18s; press nudges down 1px and scales to .99 with `cubic-bezier(.2,.8,.2,1)`. Focus is the global 3px red outline at 3px offset with 6px radius.
- **Ghost:** transparent with navy border and text. On the navy field it becomes white-bordered and fills white with navy text on hover (the Facebook button).

### Navigation
- **Header:** wordmark (star mark plus two stacked condensed uppercase lines, small "LLC") top-left; the phone number with a red phone icon top-right, condensed 800 navy, red on hover. No menu, no other header links.
- **Footer:** deep navy field, reversed wordmark, the flyer tagline as a label, phone and Facebook as 44px white links (hover to a pale pink tint), and a fine-print line.

### Service Rows
A list of text links, each one opening a pre-filled text message for that service.
- **Rest:** full-width row, 60px min height, 18px 600 ink label, optional 15px soft-ink sub-line, 1px rule-cream divider, and a 38px arrow-well circle holding a navy arrow on the right.
- **Hover / Focus:** only the arrow changes: it fills red, the arrow turns white, and it slides 3px right (.25s `cubic-bezier(.2,.8,.2,1)`). The row's own background, outline and shadow stay untouched; keyboard focus draws the red ring around the arrow, not the row.
- **Groups:** a 22px navy title with a 2px navy rule beneath, rows below; two CSS columns at 900px+, groups never split.

### Steps
Numbered list with a 58px red condensed numeral spanning two lines on the left, a 19px bold navy step line and a soft-ink detail on the right.

### Carpet Floor (signature)
A canvas simulation that fills the hero floor below the baseboard.
- **Pile:** a texture drawn once per size: oatmeal base, soft mottling, and thousands of small tufts in seven warm shades. Soil is a multiply layer (traffic lane through the lower middle, noise mottling, a few stains, speckle) tinted warm brown; wet is a cool multiply tint; nap laid away from you darkens, nap laid toward you brightens through a screen layer.
- **Wand:** drawn from above: a steel-gradient head (16px deep, 6px corners) square to a steel shaft that runs off the bottom edge to an unseen operator, a navy band in the middle of the head, a dark vacuum slot on the leading edge, a dark hose curving away, and a soft warm shadow on the pile. The head is about a fifth of the floor wide, never under 64px.
- **Self-running:** the wand pulls stripes up and down the floor, lifts at each end, side-steps by 0.86 of a head width, and turns back at the edges, with a slight hand wobble. Pulling up lays the pile light; pushing down lays it dark, which produces the alternating nap stripes. About 40% of the floor is already cleaned before the first paint.
- **Life cycle:** each pass halves the soil under the head and wets it; the stripe dries over a few seconds; once dry, soil slowly creeps back toward its original pattern and stripes fade very slowly, so the floor never finishes.
- **Hand control:** a finger drag (any direction) or a hovering mouse takes the wand; the native cursor is hidden over the floor. After the pointer leaves, the wand resumes on its own after a short idle. The first touch fades the "Drag across the carpet to clean it" hint.
- **Reduced motion:** a still, pre-cleaned frame; the visitor can still clean by hand, and the frame updates only while they do.
- **Performance:** one shared animation loop for every carpet; off-screen carpets sleep via IntersectionObserver; pixel ratio is capped; mobile address-bar resizes keep the scene.

**Tunable constants** (`CFG` in the page script):

| Constant | Value | Effect |
|---|---|---|
| `CELL` | 4 | CSS px per simulation cell (soil/wet/nap resolution) |
| `DPR_MAX` | 1.5 | Pixel-ratio cap for the canvases |
| `WAND_W` | 124 | Widest wand head in CSS px; actual is min(124, floor width / 5.2), floor 64 |
| `AUTO_SPEED` | 280 | Self-running wand speed in px/s (x1.4 on floors wider than 900px) |
| `IDLE_MS` | 2200 | Delay before the wand runs itself again after the pointer leaves |
| `REGROW` | 0.006 | Per-second rate soil creeps back once a stripe is dry |
| `DRY_S` | 2.6 | Seconds for a wet stripe to dry |
| `NAP_RELAX` | 0.012 | Per-second fade of hero nap stripes |
| `RUNNER_RELAX` | 0.07 | Per-second fade of brushed nap on runners back to their stripes |
| `BRUSH_R` | 26 | Runner brush radius in px |

### Carpet Runner
A bound runner strip used as a section divider: 58px of the same pile, bound by 7px navy edges top and bottom, with a short warm cast shadow. It is clean (no soil) and pre-striped with soft, slightly wavering alternating bands. An unseen hand brushes along it in a swaying path; a hovering mouse or a touch also brushes, and brushing right lays the pile light. Brushed nap relaxes back to the stripes. Touch still scrolls the page vertically through it. Runners load after the hero, when the browser is idle.

## Do's and Don'ts

### Do:
- **Do** keep the room order (wall, 18px baseboard, carpet floor) at every width, with the wand already working on first paint.
- **Do** put the phone number top-right in the header once; repeat it lower only as a plain text link (close line, footer).
- **Do** make every quote action a pre-filled `sms:` link to Vincent; reserve the filled red button for "Text for a quote".
- **Do** set headings in the condensed display stack at 800, uppercase, navy (white on navy), and everything else in the system body stack in sentence case.
- **Do** alternate wall cream, paper and navy section fields, and use bound runners as the dividers between them.
- **Do** keep every tap target at least 44px tall; buttons 58px, rows 60px.
- **Do** honor reduced motion with a still frame that still responds to the visitor's hand.
- **Do** tune the carpet through `CFG`, not by editing the simulation math.

### Don't:
- **Don't** add a sticky header, sticky call bar or floating action button.
- **Don't** change a service row's background, border, outline or shadow on hover or focus; only the arrow changes.
- **Don't** put black or dark-grey fields on the page; the darkest surface is deep navy in the footer.
- **Don't** load webfonts; the system stacks are the house choice.
- **Don't** use grey or hard-offset shadows, or shadows on content boxes; shadows fall only from the baseboard, runners, the wand and the one red button.
- **Don't** put uppercase tracked labels above headings; the label style belongs only to the owner's role line and the flyer tagline.
- **Don't** show before/after photos, reviews, prices or credentials that the business has not supplied.
