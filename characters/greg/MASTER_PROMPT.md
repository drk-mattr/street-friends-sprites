# GREG "THE DESIGNER" — Millennial Edition · Gemini Master Prompt

Character sprite pipeline for **Street Friends Fighter**. Build one stage at a time.
Style DNA (keep constant across every sprite): 16-bit SNK/Capcom arcade pixel art,
side profile, crisp pixels, black outlines, cel shading, 32-color palette.

---

## STAGE 1 — Neutral fighting-stance base sprite (generate this first, lock it before animating)

**Paste this into Gemini (image generation):**

> A 16-bit 2D fighting-game character sprite in the classic SNK / Capcom arcade pixel-art
> style (like Street Fighter / King of Fighters). A single full-body character in a
> **neutral FIGHTING stance** — the ready idle pose of a Street Fighter character: knees bent,
> weight low and balanced, one foot forward and one foot back, body bladed at an 80% side
> profile facing right, coiled and ready to fight. **NOT standing upright or relaxed** — this is
> a combat-ready guard pose. Authentic hand-drawn pixel art: crisp hard pixels, clean solid
> black outlines, cel shading, high contrast, NO blur, NO gradients, NO soft anti-aliased edges,
> NO 3D render, NO photo. Flat solid background (pure white) with a small soft oval contact
> shadow under the feet.
>
> Character: **GREG "THE DESIGNER"** — an unapologetically millennial creative who is secretly a
> disciplined fighter. The whole joke is the contrast between his chill hipster vibe and his
> serious combat stance. Medium athletic **cut / muscular build**, about 5'10". Short dark hair,
> neat dark beard, glasses, faint ironic half-smirk.
>
> Pose detail: **lead (front) hand raised in a fighting guard fist**; **rear hand casually holding
> an iced latte**, as if he refuses to put it down mid-fight. (Think Ryu's default idle stance --
> but he's holding a latte.)
>
> Outfit (follow exactly):
> - Worn **backwards baseball cap** (faded charcoal).
> - A slightly **oversized, comfy knit sweater** in a soft neutral color (oatmeal / heather grey),
>   with a **simple, abstract green cartoon-turtle graphic** on the chest -- stylized and low-detail,
>   just a loose suggestion of a ninja turtle, NOT a detailed illustration.
> - Plain **khaki chino shorts** -- flat front, **NO cargo or side pockets**, hem slightly above the knee.
> - **White ankle socks** + **pink / salmon foam Crocs**.
> - Gear: an **M4 carbine on a sling** worn across his body, hanging hands-free at his back/side
>   (NOT held, NOT aimed); a **fixed-blade knife holstered on his hip**. **NO axe, NO handgun.**
> - Millennial vibes: **wireless earbuds (AirPods)** in his ears and a couple of **beaded / friendship
>   bracelets** on the wrist.
>
> Technical: ONE character, centered, full body fully in frame with a little headroom and
> footroom. ~32-color limited arcade palette. NO text, NO labels, NO UI, NO logos, NO border,
> NO grid, NO extra characters. Just the single character on the flat white background,
> arcade sprite quality, consistent pixel density.

**Background note:** for an easier cut-out, swap "pure white" for
"flat solid magenta (#FF00FF)" -- that color never appears on the character, so I can key it
out perfectly for a transparent PNG.

---

## After Stage 1 is approved

- **Stage 2 — Idle breathing loop (4 frames):** from the locked fighting stance, breathe in place
  (shoulders/chest rise and settle) while holding the guard + latte. I can derive these from the
  base to keep him pixel-identical.
- **Stage 3+ — Full action set the game engine needs, one at a time:**
  walk, jump, punch, kick, **special (BRO-BEAM)**, block, hit, KO.

Consistency rule: reuse the locked fighting-stance sprite as the base for every other pose;
keep the same proportions, pixel density, black outlines, and 32-color palette.
