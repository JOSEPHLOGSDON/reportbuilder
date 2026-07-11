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
- duration: 3.563s
- transition_in: cut
- status: animated
- src: compositions/frames/01-hook.html
- type: hook
- persuasion: Pattern interrupt — reframes where winning actually happens
- beat: curiosity + conviction
- blueprint: kinetic-type-beats
- asset_candidates:

narrativeRole: Stops the scroll with an insider truth every show family already feels — the daily grind decides the banner. Sets up chore time as the battleground ProFeeder owns.
keyMessage: The daily work decides the win.

- blueprint: kinetic-type-beats (Adapt — sub-shape B, multi-beat statement build / escalation)
- sfx: impact-soft

Adapt: keep the beats-replace-each-other engine and the spring-pop payoff signature; escalate energy — each beat is a full-screen slam with its own entrance and hard background flips, built for a muted Facebook scroll-stop.
Scene 1 (0.0–0.9s): the VO opens on "Banners" — the single oversized word BANNERS slams in dead-center on a percussive beat (`kinetic-beat-slam`), cream display serif filling ~85% of frame width on navy ink, arriving with a motion-blur fly-in that resolves sharp (`motion-blur-streak`); a gold particle burst kicks off behind it (`css-marker-patterns` burst). Camera locked.
Scene 2 (0.9–1.7s): on "aren't won on show day," a hard bg-invert flip — navy flips to GOLD field, type inverts to ink (`discrete-text-sequence` whole-state swap): "aren't won" slams in big, then "on show day." hard-cuts beneath it at half scale, both landing on their spoken beats (`kinetic-beat-slam`), each with a distinct entrance (bottom-up masked slide, letter-spacing collapse).
Scene 3 (1.7–2.6s): on "They're won," flip BACK to navy — the prior beat zooms past the camera and blurs off (`motion-blur-streak` exit into the seam, velocity-matched); "They're won" flies in sharp and huge in cream.
Scene 4 (2.6–3.669s): on "at chore time," the payoff — "at chore time." SPRING-POPS in below in gold italic display serif at hero scale (`spring-pop-entrance`, the sanctioned playful overshoot — this is the one bell-hit of the video); gold motes drift outward once (`css-marker-patterns` burst, finite) and the full lockup holds dead still to the end.


## Frame 2 — The guesswork

- scene: Three short pain lines land solo on cream canvas — "Scribbled feed notes." / "Guessed weights." / "A dewormer date you missed."
- voiceover: "Scribbled feed notes. Guessed weights. A dewormer date that slipped."
- duration: 4.053s
- transition_in: crossfade
- status: animated
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
Scene 3 (2.6–4.0s): on "a dewormer date that slipped," the final pain line replaces it the same way and HOLDS — the last two words "that slipped." tinted ember and dropping a few pixels on a long-tail settle, like the date itself slipping. Still to the end.


## Frame 3 — Meet ProFeeder

- scene: Phone mockup rises center on dark navy; "Feeding Time" checklist UI on screen; wordmark "ProFeeder" locks in above with gold italic accent
- voiceover: "Meet ProFeeder — the whole barn, in your pocket."
- duration: 3.264s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/03-intro.html
- type: product_intro
- persuasion: Friction reduction — one app replaces the mess
- beat: relief + intrigue
- blueprint: device-surface-showcase
- asset_candidates:

narrativeRole: The turn. Product named by frame 3, promise landed: everything the barn needs, one app. Phone UI recreated as styled HTML (feeding checklist per site hero).
keyMessage: One app runs the whole barn.

- blueprint: device-surface-showcase (Adapt — static-tour variant)
- focal: assets/screen-feeding-time.png
- roles: screen-feeding-time = supporting (the phone's screen content — REAL app screenshot mounted inside an authored phone shell)
- sfx: riser, pop-soft

Adapt: keep the surface-as-hero + accent-shape-behind signature; single real screen (the actual Feeding Time screenshot) instead of a multi-screen cycle — the intro only introduces.
Scene 1 (0.0–1.5s): navy ink field. As the VO says "Meet ProFeeder," a phone mockup (authored navy shell whose screen IS `assets/screen-feeding-time.png`, full-bleed inside the shell, top-aligned so the "Feeding Time" header and Lucy card read clearly) slides up from the lower edge and settles (`spring-pop-entrance`, smooth settle, no overshoot) center-right at ~58% canvas height; a large gold-tinted disc scales up behind it (`scale-swap-transition` restrained form) — asymmetric 60/40, 3 depth layers (disc / phone / type).
Scene 2 (1.5–2.8s): on "the whole barn," the wordmark "ProFeeder" reveals per-word (`dynamic-content-sequencing`) in cream display serif upper-left, with ".ag" in gold.
Scene 3 (2.8–4.0s): on "in your pocket," a small gold italic tagline "the whole barn, in your pocket." fades up under the wordmark; everything settles and HOLDS — at most subtle jitter on the phone (`sine-wave-loop`, low amplitude).


## Frame 4 — Know every pig

- scene: Real Lucy profile screen (weight/ADG/days-on-feed stat cards) advancing to the Pace-vs-Target gauge screen inside the phone
- voiceover: "Track every pound of gain — and see exactly where every pig stands, days out from the show."
- duration: 5.525s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/04-weights.html
- type: feature_showcase
- persuasion: Show-don't-tell proof — live numbers doing the math for you
- beat: control + confidence
- blueprint: dataviz-countup
- asset_candidates:

narrativeRole: The hero feature — rate-of-gain math toward target show weight is the core magic. The count-up dramatizes certainty replacing guesswork.
keyMessage: You always know where every pig stands.

- blueprint: device-surface-showcase (Adapt — screen-cycling: pig profile → pace gauge)
- focal: assets/screen-pig-profile.png
- roles: screen-pig-profile = focal cutout (REAL Lucy profile screenshot, first screen in the shell); screen-pig-details-adg = supporting (REAL pace-gauge screenshot, second screen)
- sfx: tick-count, chime-soft

Adapt: keep the surface-as-hero signature and the screen-cycling engine — the phone's screen ADVANCES through a real flow (profile stats → pace gauge), with the camera pushing in continually.
Scene 1 (0.0–2.2s): cream canvas. On "track every pound of gain," the phone rises centered (`spring-pop-entrance`, smooth) showing `assets/screen-pig-profile.png` positioned so Lucy's header and the four stat cards (Current Weight 253 lbs, ADG, Days on Feed) read clearly — Centered, phone ~62% of frame height, upper-two-thirds; a gold callout chip "+1.74 lbs/day" fades in beside it (`discrete-text-sequence`); the continual camera push begins.
Scene 2 (2.2–3.8s): on "exactly where every pig stands," the SCREEN ADVANCES — the profile screen pushes up and out as `assets/screen-pig-details-adg.png` (positioned at the "Pace vs Target ADG" gauge region) pushes in from below inside the clipped shell (screen-cycling, velocity-matched internal seam per `3d-page-scroll`); the camera keeps closing toward the gauge (`multi-phase-camera` + `coordinate-target-zoom`); a gold accent underlines the gauge's green zone (`css-marker-patterns`).
Scene 3 (3.8–5.2s): on "days out from the show," a navy chip "25 DAYS TO SHOW" reveals beside the phone (`discrete-text-sequence`); glow blooms softly (`ambient-glow-bloom`); camera eases to a stop; HOLD still.


## Frame 5 — Rations & health

- scene: Two-up feature cards assemble — "Custom rations, blended on the fly" with feed-mix UI chips; "Vaccines & dewormers that never slip" with reminder rows checking off
- voiceover: "Blend custom rations on the fly. And health schedules? Never slip again."
- duration: 4.779s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/05-rations-health.html
- type: feature_showcase
- persuasion: Feature-to-benefit translation — capability stated as a promise kept
- beat: ease + peace of mind
- blueprint: grid-card-assemble
- asset_candidates:

narrativeRole: Widens the value: feeding precision plus health protocols — the two chores with the highest stakes — handled in the same app.
keyMessage: Rations and health protocols, handled.

- blueprint: grid-card-assemble (Adapt — two-up: real phone + authored health card)
- focal: assets/screen-ration-nutrition.png
- roles: screen-ration-nutrition = focal cutout (REAL ration/blended-nutrition screenshot in an authored phone shell, left slot); health card = supporting (authored HTML, right slot)
- sfx: pop-soft, check-tick

Adapt: keep the staggered assemble-into-slot signature; left slot is a REAL phone (screen = `assets/screen-ration-nutrition.png`, positioned so INGREDIENTS + the purple BLENDED NUTRITION summary read clearly), right slot an authored health card — each reveals ON its spoken cue.
Scene 1 (0.0–2.0s): cream canvas. On "blend custom rations on the fly," the phone fades + slides into the left slot (`center-outward-expansion`, direct-into-slot form) — split-screen two-up developing left→right, phone ~46% width, upper-two-thirds; a small gold callout "13.9% protein · blended live" fades in above it (`discrete-text-sequence`).
Scene 2 (2.0–3.6s): on "health schedules," the authored HEALTH card assembles into the right slot the same way (brand system: navy on cream); two reminder rows ("Matrix — due today", "Dedewormer — done") appear, and on "never slip again" their checkmarks draw on in gold (`svg-path-draw`) with the done-row dimming by position.
Scene 3 (3.6–4.5s): both settle level and HOLD; a single traveling gold glow sweeps once across the pair (`ambient-glow-bloom` traveling form) and dies out. Still to the end.


## Frame 6 — Show day, dialed in

- scene: Real Shows screen in a phone (McLean county fair — 19 days) beside the Teams & Collaboration card
- voiceover: "Every show — counted down, dialed in."
- duration: 2.944s
- transition_in: push-slide LEFT
- status: animated
- src: compositions/frames/06-showday.html
- type: benefit_highlight
- persuasion: Future pacing — the viewer sees their show season under control
- beat: anticipation + control
- blueprint: grid-card-assemble
- asset_candidates:

narrativeRole: Pays off the hook — chore-time discipline arriving at show day fully prepared. Echoes the site's own line verbatim.
keyMessage: Nothing sneaks up on you.

- blueprint: grid-card-assemble (Adapt — two-up: real Shows phone + real Teams card)
- focal: assets/screen-shows.png
- roles: screen-shows = focal cutout (REAL Shows screenshot in an authored phone shell, left slot); card-teams = supporting (REAL "Teams & Collaboration" feature-card image, right slot)
- sfx: tick-count

Adapt: keep the staggered assemble-into-slot signature; left slot is a REAL phone (screen = `assets/screen-shows.png`, positioned so "Upcoming Shows (2)" and both show cards with their "19 days" / "35 days" pills read clearly), right slot is the REAL Teams & Collaboration card image — each reveals ON its spoken cue.
Scene 1 (0.0–1.5s): cream canvas. On "every show," the Shows phone fades + slides into the left slot (`center-outward-expansion`, direct-into-slot form) — split-screen two-up, phone ~46% width, upper-two-thirds; a gold callout chip "19 DAYS OUT" pops beside the McLean row (`spring-pop-entrance` accent).
Scene 2 (1.5–2.4s): on "counted down," the Teams & Collaboration card (`assets/card-teams.png` as an <img> card with a hairline border) assembles into the right slot the same way — the whole show team stays synced.
Scene 3 (2.4–2.944s): on "dialed in," both settle level and HOLD; one traveling gold glow sweeps across the pair (`ambient-glow-bloom` traveling form) and dies out.


## Frame 7 — Start free

- scene: Calm title card on cream — "Start free." large serif; "$0 to start · Basic $5/mo · Pro $9/mo" small beneath
- voiceover: "Start free."
- duration: 4.045s
- transition_in: crossfade
- status: animated
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
Scene 3 (1.4–2.5s): a small qualifier line "$0 to start · Basic $5/mo · Pro $9/mo" translates up from below center and fades in beneath (`discrete-text-sequence` slide-up crossfade), "$0" in gold. Everything HOLDS dead still — no second phase, no drift.


## Frame 8 — Win more banners

- scene: Dark navy close — "Get ProFeeder." locks up, gold italic "Win more banners." lands beneath; App Store / Google Play badges + profeeder.ag
- voiceover: "Get ProFeeder — and win more banners."
- duration: 2.752s
- transition_in: zoom-through
- status: animated
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

