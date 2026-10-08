# Profile style guide

How to keep this profile consistent when it changes. It's short on purpose.

## Identity

I make apps, tools, and skills for AI agents that other people can use. The profile should help a visitor see that quickly, find one thing worth trying, and know how to give feedback.

The mascot is an Old English Sheepdog who supervises the workshop. It has no name and no backstory. Keep it that way.

## Mood

Welcoming, curious, inventive, calm, lightly mischievous. A capable independent builder sharing useful things. Playful, not childish. Confident, not self-important.

## Palette

Design references for future artwork, not CSS. GitHub controls the page styling.

| Role | Color |
|---|---|
| Warm paper | `#F4EDDF` |
| Graphite | `#282624` |
| Sunflower accent | `#E9B44C` |
| Soft orange | `#E68A46` |
| Pencil violet | `#9A78C8` |
| Muted green | `#79A176` |

Paper and graphite are the foundation. Use one or two accents at a time. The supplied artwork comes first: don't recolor it to match this table.

## Imagery

- Style: a cozy software workshop drawn in a sketchbook. Graphite lines, colored pencil, cross-hatching, visible paper grain, subtle anime-inspired illustration.
- The artwork is an aesthetic. Don't describe it as literally hand-drawn by me.
- **Banner** (`assets/banner.jpg`, 1600 x 800): the one big visual. Keep the 2:1 shape. Don't add a "Built by Cesar" line.
- **Avatar** (set in account settings, not stored here): I'm keeping my existing profile picture. If the sheepdog mascot is ever used elsewhere, it's the dog behind a laptop: no person, no other breed, no redrawing. Resizing and compressing is fine; keep the face prominent.
- The same warm-paper artwork works in light and dark mode. Make a second version only if testing shows a real problem.
- Add an image only if it helps someone understand a project. One screenshot or demo thumbnail in "Start here" at most.

## Writing voice

- First person, as Cesar. Not "we", not a company.
- Direct, warm, lightly witty. Say what it does for the person before saying what it's built with.
- Specific over impressive. No invented hobbies, jobs, users, numbers, or expertise.
- One small sheepdog joke per surface. Currently it lives in the closing line and the bio.
- Never: "visionary", "revolutionizing", "10x", "rockstar", "passionate about leveraging cutting-edge...".
- Don't promise support, response times, or release dates.

## Layout

One column, in this order:

1. Banner
2. `# Hey, I'm Cesar.` and two short sentences
3. Start here: one project
4. More things I've made: up to three more, only if they're real
5. On my workbench: optional, only for a current public focus I can point to
6. Feedback, then the closing line

Use GitHub's own typography and Markdown. No custom fonts, CSS, JavaScript, centered walls of text, or HTML beyond what's necessary. The text should read fine with images switched off. Aim for roughly 200 to 400 words, and treat that as a ceiling, not a quota.

## Project entry pattern

```markdown
### [Project name](verified URL)

One sentence: who it helps and what it does.

Status: what's verifiably true. [Clear action](verified URL)
```

- Use the project's real name and a link that works.
- Status comes from evidence: a tagged release, a version in the manifest, a license file. If it's unclear, leave status out.
- Only say "open source" if the repo has a license that says so.
- Describe agent skills as reusable instructions or workflows, not trained models, unless that's true.
- Don't claim compatibility or platform support the project doesn't state.

## Adding a project

1. Is it public, working, and documented well enough that a stranger could try it? If not, wait.
2. Does it do something distinct from what's already listed? If not, skip it.
3. Check the name, URL, license, install path, and any status line against the repo.
4. Add it under "More things I've made". If that already has three, replace the weakest one instead of adding a fourth.
5. Update pins if it should be one of them. Pins are separate from this README.

## Do and don't

| Do | Don't |
|---|---|
| "Snaps windows into place with a keyboard shortcut." | "A revolutionary window management solution." |
| "Status: early, version 0.2.0." | "Production-ready" with no evidence. |
| Link to the repo's issue tracker. | Invent an email address or social handle. |
| One banner, then text. | Stack logos, badges, stat cards, or a contribution snake. |
| Leave a section out when there's nothing real to say. | Fill it with placeholders. |

Also avoid: neon or glowing dashboards, glassmorphism, glossy 3D mascots, corporate gradients, animated typing banners, visitor counters, and walls of technology logos.

## Maintenance checklist

- [ ] Every link opens (projects, releases, issues)
- [ ] Every status line is still true
- [ ] Banner path and alt text still work; image isn't distorted
- [ ] Headings go in order, one H1
- [ ] Nothing reads like a placeholder, and no "Built by Cesar" line has crept back in
- [ ] "On my workbench" is current, or removed
- [ ] Bio is still 160 characters or fewer
- [ ] Pins match the featured projects
