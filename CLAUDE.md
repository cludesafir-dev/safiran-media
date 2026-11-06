# Safiran — video production rules (read before making ANY video)

These are standing rules from the owner. They apply to every video, reel and story, in every session.

## 1. Pinterest research FIRST — videos must never look alike  (MANDATORY)
Before building a series (or a single video that belongs to a series), Claude MUST:
1. Browse Pinterest video search (see `tools/pinterest-refs/README.md` — works from the cloud container with headless Chromium).
2. Pick **one different reference video per video to be made** (7 videos -> 7 different references), covering clearly different
   visual languages (e.g. paper cut-out, vintage collage, flat 2D, isometric timeline, calligraphy/ink, geometric, watercolor...).
3. Download a short sample of each, extract frame sheets, and analyse: layout, type, colour, motion, transitions, sound.
4. Derive a **distinct style spec per video** from its reference (different layout, composition, type treatment, transitions,
   music). Reusing one engine/template with only a colour swap is NOT acceptable.
5. Record the chosen references (pin URLs + what was taken from each) next to the videos (e.g. `stories/<series>-references.md`).
Inspiration only: never copy or re-publish the reference videos.

## 2. Storytelling
- Biography-style story arc like the Molana video: birth date & place, family trade, childhood, youth, turning points, death.
- Show an image for each keyword **when it is spoken** (old bakery for "bakery", camel caravan for "merchant"...).
- Prefer real historical images (black & white / sepia photos, miniatures, engravings, maps) from public-domain / CC0 sources
  (Wikimedia Commons; check the licence field), shown as old photo cards. Keep a credits file.
- Dates and legends are uncertain: hedge ("حدود", "روایت است", "می‌گویند") and list uncertain facts for the owner to verify.

## 3. Feel: alive, warm, harmonious
- Every element enters/exits with motion AND a matching sound (pop, whoosh, key clicks for typing, counter ticks, dings).
- Words appear one by one in sync with sound; keywords get a highlight box; scene changes use sweeping transitions with whoosh.
- A soft, pleasant, continuous music bed in tune with the SFX (never a bare drone). Master about -14 LUFS.
- 9:16, 1080x1920, safe zones (keep key text out of top ~12% and bottom ~14%). Stories <= 60 s.

## 4. Publishing safety
- `queue/*.json` items are published only when `approved_by == "Amirhossein"`. Never write that approval on his behalf.
- Never push to `main` or open a PR unless asked; work on the session branch.

## 5. Where finished videos are saved (owner's rule)
- Every finished video must ALSO be saved on the owner's computer in the **Video folder on drive D** (`D:\Video`), and its
  file names / sub-folders / metadata must follow what is already in that folder (look at it first, match its conventions).
- Claude can only write there when the owner's computer is connected to the session (Claude desktop app -> Settings -> Claude Code ->
  Remote Control -> add the folder `D:\Video`). If it is not connected, say so and hand the files over via chat / zip instead.
