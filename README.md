Project Vazkael
> A community-built hack & slash action-RPG set in a medieval fantasy world with a 3D manga/anime art direction.
![Status](https://img.shields.io/badge/status-setting%20up-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Engine](https://img.shields.io/badge/engine-Godot%204-478cbf)
![Contributions](https://img.shields.io/badge/contributions-open-orange)
---
What is Project Vazkael?
Project Vazkael is a unique experiment: an ambitious video game developed without a studio, without a fixed budget, without a rigid hierarchy — built solely by passionate individuals contributing at their own pace, according to their own skills.
The question we're asking: can a sufficiently passionate community build a great game, simply by organizing around a shared vision?
The game
Genre: Hack & Slash Action-RPG
Perspective: Isometric 3D · fixed tilted camera
Universe: Medieval / Fantasy
Art direction: 3D manga / anime — vivid expressive characters in a dark architectural world
Gameplay feel: Fast fluid campaign (Torchlight Infinite) + deep endgame loop (Path of Exile, Diablo)
Multiplayer: Community-hosted dedicated servers
Our vision
> That anyone with the desire to contribute can do so safely, that all participants have fun, and are proud to be part of this community.
---
Two things are locked forever. Everything else is yours.
Only two elements are immutable and cannot be changed by any vote:
The medieval / fantasy universe
The 3D manga / anime art direction
Every mechanic, system, lore decision, and gameplay feature described in our Founding Document is a guiding thread — a starting point, not a constraint. The community shapes everything else.
---
How to get involved
No application. No selection. No gatekeeping. If you want to contribute, you contribute.
Step 1 — Read the founding documents
Before anything else, get familiar with the project:
`docs/GDD.md` — The full founding document (vision, game design, charter, voting system)
`CHARTER.md` — Community rules at a glance
`docs/art-style-guide.md` — Visual art direction reference
Step 2 — Find your place
You don't need to be a developer to contribute.
If you enjoy...	You can contribute...
💻 Coding (GDScript / Python)	Game mechanics, systems, tools
🎨 Illustration / 3D art	Characters, enemies, environments, UI, VFX
🎮 Game design	New skills, items, dungeons (via JSON files)
✍️ Writing	Lore, dialogues, item descriptions
🌍 Translating	Localization in any language
🐛 Playing & testing	Bug reports, feedback, playtesting
> **No coding experience?** All game content (skills, items, enemies) is defined in simple `.json` files in `game/data/` — structured text files anyone can edit.
Step 3 — Fork, contribute, get credited
```bash
# Clone the repository
git clone https://github.com/[org]/project-vazkael.git

# Create your branch (follow the naming convention)
git checkout -b art/character-knight-sprite
git checkout -b gameplay/ice-nova-skill
git checkout -b fix/collision-wall-bug

# Open a Pull Request toward develop
```
Every accepted contribution adds your name to `CONTRIBUTORS.md` and to the in-game credits screen. Permanently.
---
How decisions are made
Project Vazkael is governed by community vote. No one decides alone.
Decision type	Majority	Duration	Who votes
Standard PR, content additions	60%	72h	All contributors
GDD changes, maintainer elections	75%	7 days	Veterans + Maintainers
License, monetization, critical changes	90%	14 days	Entire community
Votes happen in GitHub Discussions (official decisions) and via a bot in our Discord `#votes` channel.
For the full voting system details, see the Founding Document.
---
Community roles
Role	How you get it
Visitor	You found the project
Contributor	Your first contribution is accepted
Veteran	10 accepted contributions in one category
Maintainer	Elected by community vote
Game Director	Founder — vision guardian only
The Game Director holds a veto only on direct violations of the 2 locked pillars. On everything else, they vote like any other contributor.
---
Content & safety rules
Not allowed — ever:
AI-generated visual assets (sprites, textures, UI, 3D models, VFX)
Characters with childlike proportions — all characters must have adult proportions
Sexual or suggestive content
Realistic gore — stylized manga violence is fine
Hateful or discriminatory content
Why no AI for visual assets? The legal framework around AI-generated images remains unstable across international jurisdictions. This rule protects every contributor from legal exposure regardless of their country.
Minimum age: 16 years old.
Financial responsibility: Participation is entirely voluntary. The project cannot be held responsible for any personal expenses you choose to make. All core tools required to contribute are free.
---
Tech stack
Element	Choice
Engine	Godot 4 (open source, MIT)
Primary language	GDScript
Game data	JSON (`game/data/`)
CI/CD	GitHub Actions
Visual moderation	Sightengine (automated on every PR)
Multiplayer	Community-hosted dedicated servers (Nakama / Colyseus)
License	MIT — free forever
Why Godot and not Unity?
Godot is fully open source under the MIT license. No royalties, no restrictions on sharing code, no company that can change the rules mid-way. It's the only choice that truly aligns with an open community project.
---
Repository structure
```
project-vazkael/
├── docs/               # GDD, art style guide, lore bible
├── game/
│   ├── scenes/         # Godot scenes
│   ├── scripts/        # GDScript code
│   ├── assets/         # Sprites, audio, UI, VFX, 3D models
│   └── data/           # items.json, skills.json, enemies.json
├── tools/              # Moderation bot, validation tools
└── .github/            # CI/CD workflows, PR templates
```
---
Code of conduct
This project welcomes everyone who shares the vision, regardless of experience level. We expect every member to:
Respect — Criticism addresses contributions, never people
Honesty — Flag problems, propose solutions
Patience — The community moves at its own pace
Coherence — Every contribution serves the shared vision
Toxic, discriminatory, or malicious behavior results in permanent exclusion by maintainer vote.
---
Where we are
Project Vazkael is in its foundation phase. The infrastructure is being set up. There is no roadmap yet — the first roadmap will be written and voted on by the community once people arrive.
This is an invitation to build something together, not a sprint. Come as you are, contribute what feels right to you, at the pace that suits you.
---
Join the community
GitHub Discussions — Proposals, questions, game design debates
Discord — [Link coming soon] — Real-time conversation, channels by specialty
Wiki — [Link coming soon] — Collaborative knowledge base
---
Contributors
Every person who has contributed to the project is listed in `CONTRIBUTORS.md` and will appear in the game's credits screen.
Project Vazkael exists because of you.
---
License
MIT License — See `LICENSE` for details.
The game, its code, and its assets are free to use, modify, and redistribute, provided the license notice is retained.
---
<p align="center">
  <i>Forged by the community · Driven by passion · Free forever</i>
</p>
