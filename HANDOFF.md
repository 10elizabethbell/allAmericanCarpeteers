# All American Carpeteers LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/allAmericanCarpeteers/ · **Repo:** https://github.com/10elizabethbell/allAmericanCarpeteers · **Built:** 2026-10-18 from Muse brief (run 2026-10-18)

## What's built
- One page, phone first: header (star + "All American Carpeteers LLC" wordmark, 973-978-9516 top-right as `tel:`), hero, What we clean, care/owner band, How it works, service area, close, footer.
- **World:** a room. Cream wall with the text, a white baseboard, and the carpet below it. Navy `#14346b` and red `#c8102e` are sampled from their flyer.
- **Signature:** the hero floor is a soiled carpet that a cleaning wand works on its own. It pulls straight passes up and down, lifting between them, and leaves classic light/dark nap stripes that go on wet and dry bright. A finger (any direction) or the mouse takes over the wand. Soil creeps back slowly once a stripe is dry.
- **Carried motion:** bound carpet runners between sections. An unseen hand brushes the nap, and the visitor can brush it too (mouse or touch, with page scroll still working).
- **Contact:** "Text for a quote" opens a pre-written text to 973-978-9516. Every service row opens a text naming that service. "Text us and ask" covers the service area. Call is the header number and the close.
- All tunables are in `CFG` at the top of the carpet script: `WAND_W`, `AUTO_SPEED`, `IDLE_MS`, `REGROW`, `DRY_S`, `NAP_RELAX`, `RUNNER_RELAX`, `BRUSH_R`.
- Impeccable: detector run plus every mode except live and onboard, and the finish reviewer. Fixes applied (soil retune, straight passes, wider desktop wand, copy trims, runner bindings, 320px header, a11y). Two detector findings were suppressed in `.impeccable/config.json`: the cream wall color, and the flyer tagline set in caps.

## Assumptions I made
- **Voice is "we".** Their caption says "we", but the flyer says Owner/Operator. Switch to "I" if Vincent works alone.
- **No work photos on the site.** The flyer's four before/after pairs are about 210px wide each and show a different subject before vs after (different sofa, different floor). They and the owner portrait look AI-generated: the shirt logo text is garbled. Posting them as "our work" would be untrue, and they'd be blurry on a phone.
- **How it works is inferred:** "Call or text → Get your quote → We come to you." Nothing on the flyer describes their process.
- **Care points use flyer and caption wording:** eco-friendly/organic solutions, deep low-moisture cleaning, removes dirt, stains and odors.
- **The logo is rebuilt as vector from the flyer:** a navy star with white/red stripes. The favicon and home-screen icon use the star.
- **Customers weren't specified as 40+,** so the page keeps the motion. If Vincent's customers skew older, apply `older-audience.md`: a still carpet and a shorter page.
- **Font:** system stack with Avenir Next Condensed for display, which is close to the flyer's condensed lettering on Apple devices. Android falls back to its condensed sans.

## Placeholders and gaps
- **Facebook:** there's no business page. Both links go to the owner's personal profile (`profile.php?id=100004055979808`). It's shown under the name "Dottore Morea" and was 403-restricted to Muse, so visitors may hit a login wall. The label says "See us on Facebook" rather than naming Vincent for that reason.
- **No email anywhere:** none exists. Add it to the footer only if he has one.
- No hours, prices, reviews, years in business, insurance, or town list. Nothing is shown for any of them.
- No real job photos. This is the biggest gap: real before/afters would go right above the Facebook button.

## Questions for the owner
1. Can you send real before/after photos from your phone (same spot, before and after)?
2. Do you have (or want) a Facebook business page we can link instead of your personal profile?
3. Which towns do you cover besides Randolph (Denville, Mendham, Chester, Rockaway, Morristown…)?
4. Is it just you, or a crew? (Decides "I" vs "we".)
5. Hours? Free estimates? Insured? Years in business? Any customer reviews we can quote?
6. Which services matter most? (Row order could lead with them.)
7. An email for the footer?

## Ideas not built (yours to pick)
- **Runner-up world:** hardwood planks you buff to a shine. A screen-and-recoat sheen follows the finger and the grain shows through. Better if hardwood refinishing turns out to be his money-maker.
- Before/after sliders under "What we clean" once real photos arrive (plain red divider).
- A `book.html` quote form (service, town, photo reminder, day) composed into the same text.
- A little steam puff behind the wand, and a satisfying "fully clean" moment when the visitor clears the whole floor (confetti in flag colors?).
- Tap-to-tick services that build one text listing everything (like Sunny Side).
- Copy alt for the hero promise: "We clean your home the way we'd want ours cleaned."

## Not verified
- Real-device touch on iPhone/Android, and inside Facebook's in-app browser (headless sweeps passed for touch and mouse, including vertical drags).
- The SMS handoff with the pre-filled body on real iOS and Android.
- Frame rate on older phones. The hero runs about 9k cells per frame on a phone and about 47k on a 1440 desktop.
- WebKit/Safari rendering of `roundRect` (there's a fallback) and the condensed font fallback on Android.
