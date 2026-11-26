# Photo plan · Embodied Work Solutions

The site is ready to share **today** with the photos it already has. Every new
photo below has a reserved spot. Until the file exists, the page shows a
stand-in (one of SK's nature photos or a credited Centre for Ageing Better /
Unsplash photo) or quietly hides that spot. Nothing looks broken.

## ⚠️ Reference images in use right now (replace or license before going live)

These nine files were cropped from the visual-inspiration page in SK's brief so
the preview shows the intended look. **They aren't SK's photos, and their
licenses are unknown.** The hero image is credited there to elevify.com. Before
merging to `main`, either replace each one with your own photo (same filename)
or confirm you have a license to use it.

| File | Where |
|---|---|
| `hero-team-collaboration.webp` | Home hero |
| `entrepreneur-messy-middle.webp` | Home card + How I can help → Entrepreneurs |
| `scattered-systems.webp` | Home card + How I can help → Business owners |
| `organizational-change-team.webp` | Home card + How I can help → Organizations |
| `approachable-ai-learning.webp` | Home AI card + How I can help → AI |
| `experience-recognition.webp` | Home experience strip |
| `experience-perspective.webp` | Home experience strip |
| `experience-action.webp` | Home experience strip |
| `finally-able-to-exhale.webp` | Home experience strip |

The four `experience-*` / exhale images are small (about 230 px wide), so they're
fine as thumbnails but will look soft if used larger.

## How to add a photo (no code changes needed)

1. Export the photo as **WebP** at the size listed (or close to it). Free:
   [squoosh.app](https://squoosh.app) → WebP, quality ~80. Aim for under 250 KB.
2. Name it **exactly** as listed (lowercase, hyphens).
3. Put it in `assets/photos/`.
4. Search the HTML for the filename and update its `alt="..."` text so it
   describes what's actually in *your* photo.
5. Commit and push. The stand-in and its Unsplash credit disappear on their own.

Keep the main subjects near the **center** of the frame: some spots crop to a
wider or taller shape on phones.

**Before shooting:** get written OK from everyone pictured to use their image on
the website. Keep screens and papers free of real names, finances, passwords,
or client information. These are illustrative scenes, so the site labels them
that way; don't caption them as real client work.

## Priority order (shoot these first)

| # | Filename | Where it appears | Export size | Scene | Feeling | Stand-in now |
|---|---|---|---|---|---|---|
| 1 | `hero-team-collaboration.webp` | Home, hero (top of the page) | 1600 × 1200 | SK and one other adult at a kitchen table or home office, reviewing a laptop or notebook together. One explaining, one leaning in. | Partnership, capability, warmth | Unsplash: two colleagues at a computer |
| 2 | `entrepreneur-messy-middle.webp` | Home, "Entrepreneurs & creators" card | 1200 × 900 | One adult at a kitchen table: laptop, open notebooks, scattered notes, a mug. Thinking about what to do next. | Recognizable overload, not distress | Nature: new leaf |
| 3 | `scattered-systems.webp` | Home, "Business owners" card | 1200 × 900 | One adult at a desk with laptop, phone, papers, a wall or paper calendar. Searching across tools. | Frustration you recognize | Nature: tangled roots |
| 4 | `organizational-change-team.webp` | Home, "Teams & organizations" card | 1200 × 900 | 3–5 adults around a table mapping a process: paper, sticky notes, a laptop. | Professional credibility, engagement | Nature: two bees on a sunflower |
| 5 | `approachable-ai-learning.webp` | Home "Curious about AI" card **and** How I can help → AI | 1200 × 900 | SK beside someone of a different age, both looking at a laptop, the moment something makes sense. Show the learner as capable. | Curiosity, growing confidence | Unsplash: woman at laptop on phone |
| 6 | `sk-working-with-client.webp` | About, next to "I see how things connect" | 1200 × 900 | SK listening or explaining while someone points at a step. Hands and faces both visible. | Competence, care | Hidden until added |
| 7 | `finally-able-to-exhale.webp` | Home, "When was the last time your mind took a vacation?" | 1200 × 800 | One adult closing a laptop or leaning back, smiling after finishing something. | Relief, ease | Hidden until added |
| 8 | `sk-headshot.webp` | Home "Hi, I'm SK" and About | 720 × 720 | **Already have it.** Replace only if you want a newer portrait. | Warmth, confidence | n/a |

## Also reserved (nice to have)

| Filename | Where | Size | Scene | Stand-in now |
|---|---|---|---|---|
| `finding-the-start-button.webp` | Home, Finding the Start Button | 1200 × 1200 | Two people at a table with notebook and laptop, just beginning to sketch where to start. | SK's magnolia bud, opening |
| `entrepreneur-vision-to-action.webp` | Home "Bring me the messy middle" **and** How I can help → Entrepreneurs | 1200 × 1500 (portrait) | Two people at a table covered in notebooks and sticky notes, sorting ideas into a plan. | SK's leaves on water / new leaf |
| `systems-implementation.webp` | How I can help → Business owners | 1200 × 900 | SK and a business owner at a laptop, mapping how calendar, inbox, and records connect. | SK's tangled roots |
| `ai-adoption-working-session.webp` | How I can help → Organizations | 1200 × 900 | SK demonstrating a tool on a shared screen while a small team asks questions. | Unsplash: two colleagues at a computer |

| `hands-on-problem-solving.webp` | Home, "I help you do it" | 1200 × 1500 (portrait) | Close-up of hands arranging sticky notes or mapping a process. | Hidden until added |

## Your own photography, already in use

- **The lens section** pairs `ease.webp` (inside the forest) with
  `clarity.webp` (the mountain overlook). The overlook starts slightly blurred
  and comes into focus as you scroll to it. People who've set their device to
  reduce motion see it sharp from the start.
- **Exhale feelings:** `relief.webp`, `pride.webp`, `thrill.webp`.
- **Magnolia sequence** (`q1`–`q4`) on the How it works steps; `q2` also stands in for Finding the Start Button until that photo exists.
- **About:** `rcsd-mushrooms.webp` and the page header.
- **Headers:** every inner page header still uses your nature photo as its background (green overlay kept), with a people photo or your headshot set into it.

## One efficient photo session

You can get most of the list in about two hours with **SK + 2–4 friends** and
two settings.

**Setting A: kitchen table or home office** (natural window light, side-lit)
1. Friend alone, scattered notes and laptop → #2
2. Same friend, add phone and calendar, searching → #3
3. Same friend, laptop closed, leaning back and laughing → #7
4. SK sits down beside them, laptop + notebook → #1 (shoot wide, leave space)
5. SK sketching a process, friend pointing → #6
6. Swap in a different-age friend, exploring an AI tool → #5
7. Notebook + sticky notes spread out, both sorting → `entrepreneur-vision-to-action`
8. First few minutes of a conversation, notebook open → `finding-the-start-button`

**Setting B: meeting room, library study room, or coworking space**
9. 3–5 people around a table, process on paper → #4
10. SK at a shared screen, others taking notes → `ai-adoption-working-session`

Tips: shoot landscape and portrait of each scene. Ask people to actually do the
task (real conversation, real sticky notes) rather than pose. Skip direct eye
contact with the camera. Natural range of ages, bodies, and backgrounds.
