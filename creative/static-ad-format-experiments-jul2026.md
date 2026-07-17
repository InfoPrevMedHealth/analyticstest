# Static Ad Format Experiments — July 2026

The four confirmed Tier 1 pain points (#3, #16, #8, #20) run through four
static-ad format frameworks (Bold Typography, Ugly/DIY, Hero, Meme), with
every output filtered through the PRIME DIRECTIVES compliance gate before
ranking. Winners at the bottom are ImageGen-ready.

## Pipeline

1. **Extract** — campaign brief (below).
2. **Transform** — each pain point through each format framework.
3. **Compliance gate** — auto-kill anything that breaks a prime directive.
4. **Rank** — survivors scored on: proven-signal fit (does it extend what the
   Jul 16–17 data already validated?), pattern interrupt, and rejection risk.

## Extracted brief

- **PRODUCT/SERVICE:** Free YouTube video content — heart disease prevention
  education (PrevMed / Dr. Ford Brewer). No purchase at the ad layer.
- **TARGET AUDIENCE:** Adults ~45–70 on Facebook; the "good patient," the
  bereaved/scare-adjacent, and the data-driven professional (assumed from
  pain-point copy and channel audience).
- **MAIN PROBLEM / DESIRE:** Fear that heart disease is silent; exhaustion
  with reassurance that isn't backed by evidence; grief converting into
  self-directed vigilance.
- **PRIMARY MESSAGE / PROMISE:** Identification only — "this is me" → click.
  No promise is made at the ad layer (Prime Directive #3).
- **PRICE / OFFER DETAILS:** None shown. Free content. All format "price"
  fields render as (price not shown).
- **CALL TO ACTION:** Soft — the "True or False?" device itself is the CTA;
  button copy "Watch the video" / "Learn More."
- **VISUAL ELEMENTS:** Proven green/blue color block; narrator's face
  (channel data validates it); no body/condition imagery ever.
- **TONE / STYLE HINTS:** Confessional, plain, first person, unpolished over
  glossy.

## Compliance gate (auto-kill rules)

- Second-person copy or viewer-condition imagery → kill (Directive #1).
- Outcome/timeline/reverse-cure-unclog language → kill (Directive #3).
- Humor applied to the bereavement block #3 → kill (brand + sensitive-event
  flag; a dead loved one is never a meme).
- Fake product shots (supplement jars, devices) → kill; there is no product,
  and a placeholder implies a health product that doesn't exist → health-claims
  review path.
- **AI-generating the narrator's face → kill.** He is a real, identifiable
  physician; synthesizing his likeness is deepfake territory and Meta flags
  it. Face variants use real photos or channel stills only.
- Illegible-by-design treatments for a 55+ audience → soften. Ugly framework's
  "contrast may fail standards" clause is overridden: DIY aesthetic yes,
  unreadable no.

---

## Format runs

### A. Bold Typography (strongest natural fit)

The confession statements ARE typography ads — this format is the proven
color block with the volume turned up.

**A1 — #3:**
- TEXT BLOCK 1: HE SEEMED FINE.
- TEXT BLOCK 2: I've had someone close to me die from a heart attack I didn't
  see coming. True or false?
- Visual: text only, no imagery. Color: near-black charcoal / cream / one red
  accent word ("FINE."). Layout: 3-word headline fills top two-thirds, support
  line small beneath, wide margins.

**A2 — #16:**
- TEXT BLOCK 1: PROOF. NOT PROMISES.
- TEXT BLOCK 2: I want to know whether I'm actually safe. True or false?
- Visual: text only. Color: navy / cream / gold accent on "PROOF." Layout:
  centered, stacked, generous negative space.

**A3 — #20:**
- TEXT BLOCK 1: I DID EVERYTHING RIGHT.
- TEXT BLOCK 2: And still found out something was seriously wrong. True or
  false?
- Visual: text only. Color: charcoal / white / lime accent underline on
  "RIGHT." Layout: headline centered, support line lighter weight below.

**A4 — #8:**
- TEXT BLOCK 1: I WANTED NUMBERS.
- TEXT BLOCK 2: Not opinions. The actual data about what's happening inside
  my body. True or false?
- Visual: text only. Color: black / white / cyan accent. Layout: left-aligned
  editorial grid, tight tracking.

### B. Ugly / DIY (native-feed camouflage)

The flat color block already wins partly because it doesn't look like an ad.
Ugly pushes that further. Constraint: readable-ugly, not chaotic-ugly, for the
55+ eye. Not applied to #3 (rawness reads as disrespect next to a death).

**B1 — #20 "The Checklist":**
- Headline (scrawled marker): I did everything right.
- Visual: hand-drawn checklist on notebook paper — "statin ✓ diet ✓ walking ✓
  checkups ✓" — every box ticked; below, in different pen, smaller: "so why
  did I still find out something was wrong?"
- CTA: True or False?
- Color: notebook white / black ink / one red pen circle.
- Layout note: crooked photo-of-paper angle, uneven margins, two clashing
  handwriting styles. Objects only — no bodies, no compliance exposure.

**B2 — #8 "The Napkin Graph":**
- Headline (Arial, plain, off-center): I wanted to SEE the numbers.
- Visual: crude hand-drawn axes on a napkin/whiteboard, one wobbly line, no
  labels, no values (a labeled chart implies a claim; an unlabeled doodle is
  texture).
- CTA: True or False?
- Color: whiteboard white / marker black / red underline.
- Layout note: looks like a photo snapped in one second; ties natively to the
  narrator's whiteboard format.

**B3 — #16 "The Sticky Note":**
- Headline: "You're fine." — printed, formal, centered like a form letter.
- Visual: a yellow sticky note slapped crooked over it, handwriting: "then
  show me."
- CTA: True or False?
- Color: white / yellow sticky / black+blue ink clash.
- Layout note: two voices, two typefaces, deliberate overlap. First person
  preserved (the note is the narrator's own hand).

### C. Hero (narrator as the product)

There is no product; the narrator is the hero asset. Command modes become
portrait-plus-statement; Stealth modes test the face natively; the Wildcard
bridges the proven block to the face hypothesis.

**C1 — COMMAND HERO — "Portrait + Statement" (#16):**
- HEADLINE: Proof. Not promises.
- SUBHEADLINE: True or false? — I want to know whether I'm actually safe.
- Visual: narrator, studio realism (real photo), level gaze, statement set
  beside him in heavy sans. Color: navy / cream / gold accent.
- ASSET TYPE: Person Only. DETAIL: real channel portrait, softbox realism —
  never AI-generated.

**C2 — STEALTH HERO — "UGC Phone POV" (#16 or #20):**
- On-image caption (social-overlay style, casual): true or false — I'm done
  accepting "don't worry about it" as an answer
- Visual: real handheld/selfie-style still of the narrator (from channel
  b-roll), natural indoor light, imperfect framing. Feels like a creator post,
  not an ad.
- ASSET TYPE: Person Only. DETAIL: authentic channel still, candid crop.

**C3 — WILDCARD / COLLIDER — "The Torn Block" (#3):**
- Visual: the proven green/blue color block with "True or False?" and the #3
  statement — but one corner of the green field is torn away like paper,
  revealing the narrator's face looking through.
- HEADLINE (in block, as shipped): I've had someone close to me die from a
  heart attack I didn't see coming.
- Color: exact campaign green/blue + photographic tear.
- Rationale: a literal A/B bridge — keeps every pixel of the winning control
  and introduces the face in one image. Pattern interrupt without abandoning
  the proven format.
- ASSET TYPE: Person Only. DETAIL: real still behind a paper-tear mask.

### D. Meme (cautious, quarantined test only)

Most of this framework is inadmissible here: humor + death (#3) is an
auto-kill, and "doctors are lying to you" punchlines walk into the
misinformation reviewer path. Two gentle, self-aware survivors — both aimed
at reassurance fatigue, both first person, no doctor villainized:

**D1 — #16 "See You Next Year" (Classic layout):**
- TEXT BLOCK 1 (top): MY CHECKUP: "LOOKS GOOD. SEE YOU NEXT YEAR."
- TEXT BLOCK 2 (bottom): ME, IN THE PARKING LOT: "...BASED ON WHAT?"
- CTA (on image, small): True or False?
- Visual: stock-style photo of an empty parking lot through a windshield —
  no doctor depicted, no exam room, no body. Impact font, white with black
  stroke.
- Layout note: Classic top/bottom. Tone: self-aware, not anti-doctor — the
  joke is on the narrator's own unease, not on medicine.

**D2 — #8 "Spreadsheet Guy" (Single-Caption):**
- SINGLE LINE: I TRACK MY 401(k) DAILY. MY ARTERIES? NEVER SEEN A NUMBER.
- CTA: True or False?
- Visual: cartoon-style sketch of a man at a laptop surrounded by charts —
  stylized figure, not the narrator, not a patient. Wait—"my arteries" names
  a body condition context; keep as-is? It names the narrator's own curiosity,
  first person, no claim. Borderline: ship only if legal/compliance signs off;
  fallback line: "MY MONEY GETS A DASHBOARD. MY HEALTH GETS A SHRUG."
- Layout note: Single-caption, Impact font. Tone: absurd-sincere.

---

## 🏆 What emerged as winners (ranked)

1. **A1 — "HE SEEMED FINE." (Bold, #3).** The strongest new concept in the
   batch. Three words carry the entire grief-identification payload of the
   account's best-performing ad, in a format that is a direct heir to the
   winning color block (typography-only, zero imagery risk). Ships in the #3
   isolation campaign.
2. **C3 — "The Torn Block" (Wildcard, #3).** The single best test design
   available: it holds the proven control constant and introduces the face
   hypothesis inside one image. Whatever it does against the flat block is
   information you can act on account-wide.
3. **A2 — "PROOF. NOT PROMISES." (Bold, #16).** The best-CTR copy of the
   four, compressed to its most commanding form. Cleanest compliance profile
   of any concept in this document.
4. **B1 — "The Checklist" (Ugly, #20).** The betrayal-by-compliance story
   told entirely with a ticked checklist — an object, not a body. DIY realism
   should camouflage in-feed the way the flat block already does, and it's
   the cheapest concept here to produce.
5. **C2 — "UGC Phone POV" (Stealth Hero, #16/#20).** The purest test of the
   face-vs-block question, in the format Facebook's 55+ feed treats as a
   person, not an ad. Requires real channel stills — never synthesized.
6. **B3 — "The Sticky Note" (Ugly, #16).** "You're fine." / *"then show me"*
   is the whole reassurance-fatigue argument in two voices and five words.
7. **D1 — "See You Next Year" (Meme, #16).** Worth a small, quarantined
   test: memes are the one format this account has never validated, and this
   is the only pain point where humor is safe. Own campaign, minimal budget,
   kill fast if CTR doesn't clear the block control.

**Not advanced:** all meme treatments of #3 (death is never a punchline);
Hero product/pedestal modes (no product exists — a placeholder jar implies a
supplement and invites health-claims review); D2 as written (artery reference
is borderline — use the fallback line if tested at all); any AI-generated
likeness of the narrator; Ugly treatments of #3; the ImageGen template's
"CTA must dominate" instruction (our ad layer is identification-only — the
True/False device IS the CTA, and a loud SHOP-NOW-style button would break
the native camouflage that is currently winning).

## Test plan

- **Campaign 1 (isolated — #3):** flat block control vs. A1 vs. C3.
- **Campaign 2 (#16 + #8 + #20):** each ad set = block control vs. its bold
  variant (A2/A4/A3) vs. one DIY/stealth variant (B3 or C2 / B2 / B1).
- **Campaign 3 (quarantine sandbox):** D1 meme alone at minimal budget.
- Success bar: beat the pain point's own block control on link CTR at ≥300
  impressions before scaling; kill anything under 3% CTR at that volume.
- Landing pages unchanged: same first-person confession voice as the ad
  (Prime Directive #2).
