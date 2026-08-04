# street-friends-sprites

Character sprite factory for **Street Friends Fighter**. We build one character at a
time, one animation stage at a time, so every fighter looks great before we move on.

## Pipeline
1. Lock a **neutral idle base sprite** (Gemini) from the character's master prompt.
2. Derive the **idle breathing loop** (4 frames) from the locked base.
3. Expand to the full engine set: walk, jump, punch, kick, special, block, hit, KO.
4. Preview everything animated in `studio/sprite-studio.html`.

## Layout
```
characters/<name>/MASTER_PROMPT.md   the Gemini generation prompt for that fighter
characters/<name>/reference/         source refs (design sheets, photos)
characters/<name>/frames/            individual animation frames (PNG)
characters/<name>/sheets/            assembled sprite sheets
studio/sprite-studio.html            drop frames in, watch them animate
```

## Roster
- [ ] **GREG "THE DESIGNER"** — millennial edition (backwards cap, abstract TMNT sweater,
      khaki chino shorts, salmon Crocs, M4 sling, hip knife, iced latte, AirPods). Special: BRO-BEAM. *(in progress)*
