---
format: 1080x1080
message: "ProFeeder turns everyday chore time into show-ring wins — the whole barn in one app."
arc: PAS with feature-benefit progression (hook → pain → product intro → feature run → price relief → CTA)
audience: 4-H/FFA show-pig families and exhibitors scrolling Facebook
mode: autonomous
music: confident, warm, country-tinged acoustic with a driving beat — builds to the CTA
---

## Video direction

- **Palette system** (from frame.md): `ink` #0d1b2e (navy) is the dark ground and dark-frame canvas; `canvas` #faf6ec (cream) is the light ground; the gold accent (#e8b64c, ember #d9a441) is the ONLY voltage — deployed as italic serif emphasis words, underlines, badges, and glows. Dark frames (1, 3, 8) use cream/white type on navy; light frames (2, 4, 5, 6, 7) use navy ink on cream. Never invent hues; UI mockups use the same system plus restrained functional chips (per frame.md components).
- **Type**: display = Instrument Serif 400 (headlines, the gold italic emphasis words); body/labels = Inter; data = JetBrains Mono. Reference roles, not families.
- **Motion grammar**: smooth long-tail settles (`power3` default) — no bounce, no overshoot except where a blueprint's signature explicitly calls a spring pop on a small accent. Every frame reveals sequentially ON its VO cue — at t=0 only what is being spoken is on screen; remaining pieces arrive across the back ~50%. During holds: stillness, at most subtle jitter (`sine-wave-loop`, low amplitude). Internal seams are velocity-matched cuts.
- **Rhythm / held frames**: Frame 7 (Start free) is the deliberate breather — one restrained move, then dead-still. Frame 1's final swap and Frame 8's resolved lockup also hold still. Frames 3–6 carry the kinetic energy.
- **Caption band**: all content composed into the top ~83%; bottom band stays clear.
- **Negative list**: no bouncy eases as default; no lazy breathing; no back-half pans/pushes; no slideshow front-loading; no screensaver float; no browser chrome/nav/scrollbars outside the deliberate phone-UI reconstructions; no purple-blue "AI" gradients; no stock-photo pigs (typography + recreated UI only).

## Frame 1 — Won at chore time

- scene: Bold serif type on dark navy — "Banners aren't won on show day." with "show day" swapping to "at chore time." in gold
- voiceover: "Banners aren't won on show day. They're won at chore time."
- duration: 3.669s
- transition_in: cut
- status: outline
- src: compositions/frames/01-hook.html
- type: hook
- persuasion: Pattern interrupt — reframes where winning actually happens
- beat: curiosity + conviction
- blueprint: kinetic-type-beats
- asset_candidates:

narrativeRole: Stops the scroll with an insider truth every show family already feels — the daily grind decides the banner. Sets up chore time as the battleground ProFeeder owns.
keyMessage: The daily work decides the win.

- blueprint: kinetic-type-beats (Reproduce — sub-shape A, fixed-line token swap)
- sfx: impact-soft

Scene 1 (0.0–1.4s): solid navy ink field. As the VO opens, "Banners aren't won" arrives dead-center via per-word staggered reveal (`dynamic-content-sequencing`) in cream display serif, smooth long-tail settle — Centered, headline ~55% of frame width, upper-two-thirds. Nothing else on canvas.
Scene 2 (1.4–2.2s): on "on show day," the phrase completes — "on show day." lands as the line's variable slot, a drawn gold underline sweeps left→right beneath it (`css-marker-patterns`). Camera locked.
Scene 3 (2.2–3.5s): on "chore time," the signature move — the slot hard-cuts in place (`discrete-text-sequence`): "on show day." swaps to "at chore time." set in gold italic display serif, slightly larger; the underline snaps to the new width. Line holds dead still to the end.


## Frame 2 — The guesswork

- scene: Three short pain lines land solo on cream canvas — "Scribbled feed notes." / "Guessed weights." / "A wormer date you missed."
- voiceover: "Scribbled feed notes. Guessed weights. A wormer date that slipped."
- duration: 4.032s
- transition_in: crossfade
- status: outline
- src: compositions/frames/02-pain.html
- type: pain_point
- persuasion: Pain validation — names the exact daily failures
- beat: frustration + recognition
- blueprint: kinetic-type-beats
- asset_candidates:

narrativeRole: Agitates the specific, recognizable failure modes of running a show barn on paper and memory. Each line is a real thing that costs placings.
keyMessage: Guesswork is quietly costing you.

- blueprint: kinetic-type-beats (Reproduce — Problem variant, pain lines land alone)
- sfx: whoosh-soft

Scene 1 (0.0–1.3s): cream canvas, bare. "Scribbled feed notes." reveals centered in navy ink display serif via chunk reveal (`dynamic-content-sequencing`) — Centered, ~50% width, upper-two-thirds; a rough gold scribble strikes through "Scribbled" (`css-marker-patterns`).
Scene 2 (1.3–2.6s): on "Guessed weights," the prior line blurs off as the next flies in with a light motion-blur entrance (`motion-blur-streak` + `discrete-text-sequence`), landing solo center; a gold hand-drawn circle rings "Guessed" (`css-marker-patterns`). Velocity-matched seam.
Scene 3 (2.6–4.0s): on "a wormer date that slipped," the final pain line replaces it the same way and HOLDS — the last two words "that slipped." tinted ember and dropping a few pixels on a long-tail settle, like the date itself slipping. Still to the end.


## Frame 3 — Meet ProFeeder

- scene: Phone mockup rises center on dark navy; "Feeding Time" checklist UI on screen; wordmark "ProFeeder" locks in above with gold italic accent
- voiceover: "Meet ProFeeder — the whole barn, in your pocket."
- duration: 2.987s
- transition_in: zoom-through
- status: outline
- src: compositions/frames/03-intro.html
- type: product_intro
- persuasion: Friction reduction — one app replaces the mess
- beat: relief + intrigue
- blueprint: device-surface-showcase
- asset_candidates:

narrativeRole: The turn. Product named by frame 3, promise landed: everything the barn needs, one app. Phone UI recreated as styled HTML (feeding checklist per site hero).
keyMessage: One app runs the whole barn.

- blueprint: device-surface-showcase (Adapt — static-tour variant)
- sfx: riser, pop-soft

Adapt: keep the surface-as-hero + accent-shape-behind signature; single screen (Feeding Time checklist) instead of a multi-screen cycle — the intro only introduces; rows tick live instead of screens advancing.
Scene 1 (0.0–1.5s): navy ink field. As the VO says "Meet ProFeeder," a phone mockup slides up from the lower edge and settles (`spring-pop-entrance`, smooth settle, no overshoot) center-right at ~55% canvas height; a large gold-tinted disc scales up behind it (`scale-swap-transition` restrained form) — asymmetric 60/40, 3 depth layers (disc / phone / type), phone face showing the "Feeding Time" checklist UI (recreated HTML: header, pen rows, ration chips).
Scene 2 (1.5–2.8s): on "the whole barn," the wordmark "ProFeeder" reveals per-word (`dynamic-content-sequencing`) in cream display serif upper-left, with ".ag" in gold; two checklist rows on the phone tick complete with drawn gold checks (`svg-path-draw`).
Scene 3 (2.8–4.0s): on "in your pocket," a small gold italic tagline "the whole barn, in your pocket." fades up under the wordmark; everything settles and HOLDS — at most subtle jitter on the phone (`sine-wave-loop`, low amplitude).


## Frame 4 — Know every pig

- scene: Pig detail card UI — weight 262 lbs, rate-of-gain +1.52/day counts up, "on target for show weight" badge pops; days-to-show chip
- voiceover: "Track every pound of gain — and see exactly where every pig stands, days out from the show."
- duration: 5.931s
- transition_in: push-slide LEFT
- status: outline
- src: compositions/frames/04-weights.html
- type: feature_showcase
- persuasion: Show-don't-tell proof — live numbers doing the math for you
- beat: control + confidence
- blueprint: dataviz-countup
- asset_candidates:

narrativeRole: The hero feature — rate-of-gain math toward target show weight is the core magic. The count-up dramatizes certainty replacing guesswork.
keyMessage: You always know where every pig stands.

- blueprint: dataviz-countup (Adapt — hero-instrument count-up, no push-through)
- sfx: tick-count, chime-soft

Adapt: keep the count-up + ring-fill signature landing as one beat; single hero pig-card instrument instead of a 2–3 instrument traversal (5s frame, one idea); camera limited to one gentle push-in that peaks and settles.
Scene 1 (0.0–1.6s): cream canvas. On "track every pound of gain," a pig detail card (recreated HTML: "Bessie" header, weight readout) rises centered (`spring-pop-entrance`, smooth) — Centered, card ~60% of frame, upper-two-thirds; the weight counts up to 262 lbs in mono digits with font-size growing on the value (`counting-dynamic-scale`) while a gold progress ring sweeps toward target weight on the same ease (`stat-bars-and-fills`).
Scene 2 (1.6–3.4s): on "exactly where every pig stands," a rate-of-gain stat chip "+1.52 /day" slides into the card and its mini bar fills (`stat-bars-and-fills`); a gold "on target" badge spring-pops beside the ring (`spring-pop-entrance` — the sanctioned accent pop); a gentle camera push-in runs (`multi-phase-camera`) and peaks.
Scene 3 (3.4–5.0s): on "days out from the show," a navy chip "SHOW IN 21 DAYS" reveals under the card (`discrete-text-sequence`); glow blooms softly behind the card (`ambient-glow-bloom`); camera eases to a stop and the card HOLDS still.


## Frame 5 — Rations & health

- scene: Two-up feature cards assemble — "Custom rations, blended on the fly" with feed-mix UI chips; "Vaccines & wormers that never slip" with reminder rows checking off
- voiceover: "Blend custom rations on the fly. And health schedules? Never slip again."
- duration: 4.971s
- transition_in: push-slide LEFT
- status: outline
- src: compositions/frames/05-rations-health.html
- type: feature_showcase
- persuasion: Feature-to-benefit translation — capability stated as a promise kept
- beat: ease + peace of mind
- blueprint: grid-card-assemble
- asset_candidates:

narrativeRole: Widens the value: feeding precision plus health protocols — the two chores with the highest stakes — handled in the same app.
keyMessage: Rations and health protocols, handled.

- blueprint: grid-card-assemble (Adapt — Key_Feature grid, two cards)
- sfx: pop-soft, check-tick

Adapt: keep the staggered assemble-into-slot signature; two large feature cards instead of a 6–9 tile grid — each card reveals ON its spoken cue rather than one opening cascade.
Scene 1 (0.0–2.0s): cream canvas. On "blend custom rations on the fly," the RATIONS card fades + slides into the left slot (`center-outward-expansion`, direct-into-slot form) — split-screen two-up developing left→right, cards ~44% width each, upper-two-thirds; inside it, three feed-mix chips (corn / supplement / show feed) stagger in (`gsap-effects` stagger) and a gold blend bar fills (`stat-bars-and-fills`).
Scene 2 (2.0–3.6s): on "health schedules," the HEALTH card assembles into the right slot the same way; two reminder rows ("Ivomec — due Sat", "Vaccine — done") appear, and on "never slip again" their checkmarks draw on in gold (`svg-path-draw`) with the done-row dimming by position.
Scene 3 (3.6–4.5s): both cards settle level and HOLD; a single traveling gold glow sweeps once across the pair (`ambient-glow-bloom` traveling form) and dies out. Still to the end.


## Frame 6 — Show day, dialed in

- scene: Show countdown UI — "Indiana State Fair — 21 days" counts down; checklist rows (entries, target weight, buyer) tick complete
- voiceover: "Every show — counted down, dialed in."
- duration: 2.475s
- transition_in: push-slide LEFT
- status: outline
- src: compositions/frames/06-showday.html
- type: benefit_highlight
- persuasion: Future pacing — the viewer sees their show season under control
- beat: anticipation + control
- blueprint: grid-card-assemble
- asset_candidates:

narrativeRole: Pays off the hook — chore-time discipline arriving at show day fully prepared. Echoes the site's own line verbatim.
keyMessage: Nothing sneaks up on you.

- blueprint: grid-card-assemble (Adapt — Benefits vertical-list, BUILD mode)
- sfx: tick-count

Adapt: keep the ~1 item/sec accumulating-list signature with marker-pop + check-draw entries; the list is a show-countdown card (header + 3 checklist lines) instead of abstract benefit lines.
Scene 1 (0.0–1.2s): cream canvas. On "every show," a show card header assembles centered — "INDIANA STATE FAIR" in Inter caps with a mono countdown "21 DAYS" beside it counting down from 24 (`counting-dynamic-scale`, shrinking beat) — Centered, card ~58% width, upper-two-thirds.
Scene 2 (1.2–2.4s): on "counted down," checklist line 1 "Entries submitted" enters: gold marker spring-pops, check draws on (`spring-pop-entrance` + `svg-path-draw`), text mask-wipes in; line 2 "Target weight — on track" follows the same way (~1/sec cadence).
Scene 3 (2.4–3.5s): on "dialed in," line 3 "Buyer confirmed" lands and ALL three checks flash gold once together (`asr-keyword-glow` envelope); card HOLDS dead still.


## Frame 7 — Start free

- scene: Calm title card on cream — "Start free." large serif; "$0 to start · Pro from $9/mo" small beneath
- voiceover: "Start free."
- duration: 1.109s
- transition_in: crossfade
- status: outline
- src: compositions/frames/07-price.html
- type: benefit_highlight
- persuasion: Risk reversal — zero cost to try
- beat: ease
- blueprint: titlecard-reveal
- asset_candidates:

narrativeRole: The breather beat. Removes the last objection (price) in two words before the ask.
keyMessage: Trying it costs nothing.

- blueprint: titlecard-reveal (Reproduce — Benefits variant)
- sfx:

Scene 1 (0.0–0.4s): static camera, bare cream canvas. The allocated breather begins.
Scene 2 (0.4–1.4s): on "start free," the ONE move — "Start free." fades in centered in navy display serif while scaling ~95%→100% on a smooth ease-out (`scale-swap-transition`, restrained) — Centered, ~50% width, exact optical center of the safe area.
Scene 3 (1.4–2.5s): a small qualifier line "$0 to start · Pro from $9/mo" translates up from below center and fades in beneath (`discrete-text-sequence` slide-up crossfade), "$0" in gold. Everything HOLDS dead still — no second phase, no drift.


## Frame 8 — Win more banners

- scene: Dark navy close — "Get ProFeeder." locks up, gold italic "Win more banners." lands beneath; App Store / Google Play badges + profeeder.ag
- voiceover: "Get ProFeeder — and win more banners."
- duration: 2.411s
- transition_in: zoom-through
- status: outline
- src: compositions/frames/08-cta.html
- type: cta
- persuasion: Status seeking — the banner is the identity payoff
- beat: motivation + triumph
- blueprint: logo-assemble-lockup
- asset_candidates:

narrativeRole: The ask, in the brand's own words. Banner language closes the loop opened in frame 1.
keyMessage: Get the app. Win more banners.

- blueprint: logo-assemble-lockup (Adapt — Brand_Outro, wordmark lockup + CTA extension)
- sfx: riser, impact-soft

Adapt: keep the clear-stage → mark-draws-on → wordmark-completes signature; the "mark" is a gold rosette-ribbon banner icon (stroke-drawn) and the lockup extends to store badges + URL instead of fading out (this is the ad's ask).
Scene 1 (0.0–1.2s): navy ink field, empty after the zoom-through arrival. On "Get ProFeeder," a simple gold banner-rosette icon draws itself on stroke-by-stroke (`svg-path-draw`) just above center; "Get ProFeeder." reveals per-word beneath it in cream display serif (`dynamic-content-sequencing`) — Centered stack, ~55% width.
Scene 2 (1.2–2.4s): on "win more banners," the payoff line "Win more banners." lands in gold italic display serif below, slightly larger (`kinetic-beat-slam`, single beat, smooth settle); the rosette's ribbon tails flick once as the stroke completes.
Scene 3 (2.4–3.5s): App Store + Google Play badge pills and "profeeder.ag" in mono fade up in a row beneath (`gsap-effects` stagger, subtle) — kept above the caption band; a soft gold glow blooms behind the lockup (`ambient-glow-bloom`). End-card HOLDS dead static.

