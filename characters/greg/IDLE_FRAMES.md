# GREG — Idle Breathing Animation · 4-Frame Prompt Pack (ChatGPT)

A subtle 4-frame breathing loop for the neutral fighting stance.
Loop order: F1 -> F2 -> F3 -> F4 -> back to F1, ~7 fps. He breathes in place --
nobody takes a step, the guard and stance hold, only the upper body gently rises and falls.

## How to run it (this is what keeps the loop clean)
1. Attach the LOCKED neutral sprite (your transparent base) to ChatGPT EVERY time as the
   reference. Don't chain edits off the previous frame -- always start from the base so he doesn't drift.
2. Ask for ONLY the tiny change listed per frame. Everything else stays pixel-identical:
   face, cap, glasses, beard, sweater + turtle, shorts, socks, Crocs, M4, knife, latte, colors,
   outline, and size.
3. Keep the same canvas size and the feet in the same spot across all 4. If ChatGPT nudges
   them, send them over and I'll align them by the feet.
4. Transparent or flat solid background.

---

### FRAME 1 — NEUTRAL (base, low point of the breath)
Use the locked base sprite as-is. No generation needed.

### FRAME 2 — INHALE (rising)
> Same character, pixel-identical, transparent background. This is one frame of a subtle idle
> BREATHING animation. Shift the upper body UP by about 2-3 pixels: shoulders lift slightly, chest
> expands a little as he inhales, head rises a touch. The raised guard fist and the hand holding
> the iced latte both rise the same small amount. Knees straighten VERY slightly. Feet stay planted
> in the exact same position. Do not change the pose, outfit, colors, or facing -- only this small
> upward breathing motion.

### FRAME 3 — PEAK (top of the breath)
> Same character, pixel-identical, transparent background. Top of the breathing cycle: upper body at
> its HIGHEST, about 4 pixels up from neutral, chest fullest, shoulders highest. Same guard fist and
> latte, both lifted to match. Feet planted in the exact same spot. Only the peak-inhale lift
> changes; everything else identical.

### FRAME 4 — EXHALE (settling back down)
> Same character, pixel-identical, transparent background. He's exhaling and settling back down:
> upper body about 2 pixels up from neutral (between the peak and the base), shoulders dropping,
> chest deflating. Same guard fist and latte. Feet planted in the same spot. Only this small
> downward settle; everything else identical.

---

## Then send the 4 PNGs to Claude
Auto-align by the feet -> characters/greg/frames/idle/ -> looping GIF + wired into the Sprite Studio.

If the loop drifts/jitters: derive a guaranteed-consistent 4-frame breathe directly from the
locked base sprite instead.
