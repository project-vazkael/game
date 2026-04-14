# Project Vazkael — Founding Document

> Version 1.0 — April 2026  
> The reference document for all contributors, maintainers, and community members.

---

## Table of Contents

1. [Preamble](#1-preamble)
2. [Project Identity](#2-project-identity)
3. [Game Design Document](#3-game-design-document)
4. [Art Direction](#4-art-direction)
5. [Community Charter](#5-community-charter)
6. [Contribution Pipeline](#6-contribution-pipeline)
7. [Voting System](#7-voting-system)
8. [Technical Infrastructure](#8-technical-infrastructure)
9. [Legal & Financial](#9-legal--financial)
10. [Launch Plan](#10-launch-plan)

---

## 1. Preamble

This document is a **guiding thread**, not a rulebook.

It represents the founding vision of Project Vazkael and exists solely to give the community a concrete starting point — not to impose a fixed direction. Every mechanic, system, and narrative choice described here can be questioned, enriched, or replaced by a community vote.

**Only two elements are immutable** and cannot be changed by any vote, ever:

1. The medieval / fantasy universe
2. The 3D manga / anime art direction

Everything else belongs to you.

---

### Our vision

> That anyone with the desire to contribute can do so safely, that all participants have fun, and are proud to be part of this community.

Project Vazkael is a unique experiment: an ambitious video game developed without a studio, without a fixed budget, without a rigid hierarchy — built solely by passionate individuals contributing at their own pace, according to their own skills.

The question we're asking: *can a sufficiently passionate community build a great game, simply by organizing around a shared vision?*

---

## 2. Project Identity

| Element | Decision |
|---|---|
| Code name | Project Vazkael |
| Final name | To be voted on by the community |
| Genre | Hack & Slash Action-RPG |
| Perspective | Isometric 3D · fixed tilted camera |
| Universe | Medieval / Fantasy |
| Art direction | 3D manga / anime |
| Tone | Epic and vivid — between Fairy Tail and Elden Ring |
| Engine | Godot 4 (open source, MIT license) |
| License | MIT — the game belongs to everyone |
| Language | English (all public documents and official decisions) |

### Gameplay references

**Campaign:** Fast and fluid progression, constant sense of power growth, no unnecessary friction. Primary reference: *Torchlight Infinite*.

**Endgame loop:** Deep and replayable. Inspired by:
- *Path of Exile* — build depth and crafting
- *Diablo IV* — accessibility and readability
- *Torchlight Infinite* — speed and fluidity

### Design pillars

- Infinitely customizable builds
- Cohesive and original 3D manga/anime art direction
- Campaign with no downtime
- Replayable and evolving endgame
- Accessible in solo and co-op
- A living, expandable world
- Open source MIT community

---

## 3. Game Design Document

> Everything in this section is a **guiding thread**. All systems are open to community discussion and modification by vote.

### 3.1 Class system — weapon-based

The player's class is determined by their equipped weapon. Two weapon sets can be switched during combat.

| Weapon | Role | Traits |
|---|---|---|
| One-handed sword | Duelist / Speed | Fast combos, Dash, Bleed |
| Dual blades | Assassin / Crit | Critical hits, Poison, Stealth |
| Sword & Shield | Guardian / Tank | Parry, Taunt, Auras |
| War staff | Titan / Impact | Stun, AoE, Armor |
| Grimoire | Summoner / Spells | Spells, Summons, Support |
| Bow / Crossbow | Ranger / Range | Distance, Traps, Fire |

### 3.2 Skill system — 4 specialization tiers

Each skill gains XP through use and kills. At each tier, the player chooses a specialization that modifies the skill's behavior.

**Tier I — Unlock:** The skill is unlocked. Base damage, simple animation.

**Tier II — First spec:** Choice between 2 orientations that modify the skill's fundamental behavior (e.g. wider area vs. concentrated damage).

**Tier III — Modifier:** Addition of a secondary effect (e.g. bleed on hit, shockwave on end, pull toward center).

**Tier IV — Transcendence:** Deep transformation of the skill, can change its fundamental mechanic (e.g. becomes a movement skill, summons a spectral clone).

**System rules:**
- Each character has 6 active skill slots
- Tier choices can be reset in town against a craftable resource
- Skills share XP when multiple are equipped in rotation

### 3.3 Generic talent tree — 3 branches

| Branch | Focus | Effects |
|---|---|---|
| Body | Defense / Survival | Max HP, regeneration, resistances, armor |
| Spirit | Spells / Passives | Mana, cooldown reduction, spell amplification |
| Forge | Attack / Critical | Physical damage, attack speed, critical hits |

Inter-branch synergy nodes at the intersection of branches enable unique combos — the signature of a fully realized build.

### 3.4 Loot & Craft

**Item quality:**

| Rarity | Color | Feature |
|---|---|---|
| Common | Gray | Fixed stats, base for crafting |
| Rare | Blue | 2–4 random affixes |
| Epic | Purple | Powerful affixes + 1 craft slot |
| Legendary | Orange | Unique effect that modifies a skill |

**Deterministic craft:** Guarantees a specific affix via craftable runes. Costly but predictable — for finishing a build.

**Random craft:** Reroll orbs, fracturing, corruption. Risky, can improve or destroy the item — for min-maxers.

**Loot philosophy:** The ground must be readable — little junk, every drop deserves a look. Legendaries are rare but transformative. No pay-to-win ever.

### 3.5 Character creation

Full character editor inspired by *Black Desert Online* and *Elden Ring*: morphology, face, skin color, hair, eyes, scars, tattoos.

**Absolute rule:** All playable characters and NPCs must have adult proportions. Minimum height equivalent to an adult in the game's scale. No character with childlike proportions will be accepted under any narrative justification. This rule is non-negotiable and cannot be changed by vote.

### 3.6 Multiplayer

Community-hosted dedicated server model — exactly like *Minecraft* or *Valheim*. The game provides the open source server code in the repository. Players or groups can host wherever they choose. Recommended solutions: **Nakama** or **Colyseus** (both open source).

No central infrastructure to manage or finance. Zero ongoing cost for the project.

---

## 4. Art Direction

### 4.1 Locked elements — non-negotiable

| Element | Decision |
|---|---|
| Rendering | Full 3D (characters and environments) |
| Camera | Isometric, slightly tilted, fixed |
| Style | Manga / anime aesthetic |
| Characters | Vivid and saturated colors, shonen proportions |

### 4.2 Open to community vote

The precise rendering style (cel-shading, toon shading, stylized semi-realistic, etc.) will be determined by a community vote in Week 2 with visual reference proposals from artists.

**Vote process if no consensus in Week 2:** First round on all proposals. If no clear majority, runoff between the top 2 options. 51% wins the second round.

### 4.3 Visual identity — the core contrast

Project Vazkael's visual identity rests on a deliberate contrast: **vivid, expressive manga characters in a dark, architectural medieval world**.

This is not a colorful world. These are colorful characters in a dark world. This contrast is the game's visual signature.

**World references:** Dark Souls, Elden Ring (dense Gothic architecture, dramatic lighting, zone-based atmosphere)

**Character references:** Fairy Tail, Black Clover, Hunter x Hunter (tall and slender, saturated colors, expressive design)

**In practice:** A gray stone castle with flickering torches — and a warrior with electric blue hair unleashing a bright orange spinning strike. Spells and characters literally illuminate the world.

### 4.4 Environments

Architecture must feel functional and inhabited, not cardboard. Each zone has its own color palette defined by its lore. The lighting is dynamic — torches, spells, raking sunlight. Player spells are light sources in dark environments.

### 4.5 Strict content rules

**Forbidden — no exceptions:**
- Characters with childlike proportions
- Deviations from the medieval universe without a 75% community vote
- Photorealistic rendering without artistic stylization
- AI-generated visual assets (see AI policy in section 5)

**Encouraged:**
- Manga expressiveness — exaggerated impact effects, strong facial expressions, dynamic lines
- High contrast between characters and environments
- Style shader proposals (until the community vote in Week 2)

---

## 5. Community Charter

### 5.1 Our vision

> Anyone with the desire to contribute can do so safely, that all participants have fun, and are proud to be part of this community.

### 5.2 Who can contribute

**Everyone.** There is no application, no selection, no gatekeeping. If you want to contribute, you contribute.

### 5.3 Roles

| Role | Condition | Rights |
|---|---|---|
| Visitor | Found the project | Report bugs, comment on PRs, vote on open proposals |
| Contributor (Builder) | First accepted contribution | Submit PRs, counted vote on all decisions, Discord access |
| Veteran (Forger) | 10 contributions in one category | Approve PRs in their specialty, double vote weight in their category, mentoring |
| Maintainer (Guardian) | Elected by community vote (1 per category) | Final merge, conflict moderation, 3-month renewable mandate |
| Game Director | Founder | Vision guardian, veto only on violations of the 2 locked pillars |

### 5.4 AI policy

The use of AI tools is **tolerated** for all contribution types **except visual assets**.

- **Code, game design, lore, translations:** AI tools freely tolerated.
- **Visual assets (sprites, textures, UI, VFX, 3D models):** Must be original human creations. No AI-generated images permitted, regardless of the tool or quality.

**Why:** The legal framework around AI-generated images remains unstable across international jurisdictions. This rule exists to protect all contributors — especially minors — from legal risk. It is non-negotiable.

### 5.5 Age minimum

**Minimum age to contribute: 16 years old.**

This threshold covers the GDPR age of digital consent across European jurisdictions and provides legal protection across most contributing countries. Contributors under 16 cannot participate in any capacity.

### 5.6 Violence & content guidelines

- Stylized manga violence: **allowed** (impact effects, exaggerated deaths, stylized blood)
- Realistic gore: **forbidden**
- Sexual or suggestive content: **forbidden** (characters of any age)
- Hateful or discriminatory content: **forbidden**
- All content passes through the automated moderation bot before any PR can be merged

### 5.7 Contributor financial responsibility

Participation in this project is entirely voluntary. Any investment of time, money, or resources (tools, software, hardware, hosting, subscriptions, etc.) is made at the contributor's own discretion and risk. The project, its founder, and its maintainers cannot be held responsible for any costs incurred by contributors in the course of their participation.

Note: all core tools required to contribute to this project are free and open source. No contributor should feel obligated to spend money to participate.

### 5.8 Behavior

- **Respect:** Criticism addresses contributions, never people
- **Honesty:** Report problems, propose solutions
- **Patience:** The community moves at its own pace
- **Coherence:** Every contribution must serve the GDD vision

Toxic, discriminatory, or malicious behavior results in permanent exclusion by maintainer vote.

### 5.9 Languages

**English is the official language** for all public documents, GitHub contributions, PR descriptions, and official votes.

Discord: English required for all official decisions and votes. Other languages are freely tolerated in general conversation — a `#francophone` or similar channel is welcome.

---

## 6. Contribution Pipeline

Every contribution follows this lifecycle:

**Step 1 — Submission**
Open a pull request on GitHub with a clear description: what it is, why it belongs, how it relates to the GDD. Use the PR template.

**Step 2 — Automated AI moderation**
Upon PR opening, a GitHub Actions workflow automatically runs:
- Visual asset analysis (nudity, graphic violence, hate content) via Sightengine
- Art style consistency check (palette, proportions)
- JSON data schema validation
- GDScript lint

Result posted as a bot comment within 5 minutes: ✅ approved / ⚠️ needs review / ❌ blocked. A PR cannot be merged while ❌.

If the AI confidence score is in the gray zone (40–70%), a maintainer is automatically tagged for manual review. The AI never blocks alone in ambiguous cases.

**Step 3 — Community review window**
72 hours open for comments and votes from contributors. Veterans in the relevant category are automatically notified.

**Step 4 — Decision**
- ≥60% positive votes → the category maintainer can merge
- Contested → 48-hour extended vote
- Rejected → maintainer must provide written feedback

**Step 5 — Merge & credit**
The contribution is integrated. The contributor's name is added to `CONTRIBUTORS.md` and to the in-game credits screen. Permanently.

**Emergency revert**
Any maintainer can revert a merged contribution if it causes a critical bug — without prior vote. The PR must be reopened with fixes within 48 hours.

### PR template

```
## Summary
Describe in 2-3 sentences what this PR adds or fixes.

## Contribution type
- [ ] Code / game mechanic
- [ ] Visual asset (sprite, UI, VFX, 3D model)
- [ ] Data (item, skill, enemy)
- [ ] Lore / narrative
- [ ] Bugfix
- [ ] Translation

## Link to GDD
Which section of the GDD does this contribution respect?

## Screenshots / demo
Screenshot or video if visual asset or mechanic.

## Checklist
- [ ] I have read CHARTER.md
- [ ] My asset respects the art style guide
- [ ] My code passes GDScript lint
- [ ] My JSON data respects the schema
- [ ] No AI-generated visual assets included
```

---

## 7. Voting System

### Three levels based on decision weight

**Level 1 — Standard vote**
- Required majority: **60%**
- Duration: **72 hours**
- Who votes: All contributors
- Quorum: **5 voters minimum**
- Examples: PR merges, bug fixes, new skills/items, lore additions

**Level 2 — Important vote**
- Required majority: **75%**
- Duration: **7 days**
- Who votes: Veterans and Maintainers
- Quorum: **10 voters minimum**
- Examples: GDD modifications, maintainer elections, charter rule changes, DA shader adoption

**Level 3 — Critical vote**
- Required majority: **90%**
- Duration: **14 days**
- Who votes: Entire community
- Quorum: **30 voters + Game Director agreement**
- Examples: License change, monetization model, project fork, modification of the 2 locked pillars

### Special cases

**Tie (50/50):** The relevant category maintainer has the casting vote. If the maintainer has been inactive for more than 7 days, the Game Director decides or delegates to a designated veteran.

**Multi-option vote (e.g. shader style):** First open round on all options. If no clear majority, runoff between the top 2. 51% wins the second round.

**Quorum not reached:** Vote extended by 48 hours. If quorum still not met, PR is held and reopens at the next monthly vote cycle.

**Game Director veto:** Only applicable when a contribution directly violates one of the 2 immutable pillars. Cannot be used to block technical improvements, lore additions, or game design proposals.

### Game Director succession

If the founder becomes durably inactive (no activity for more than 30 days with no prior notice), the maintainers trigger an emergency community vote to designate a successor. The successor inherits all Game Director rights and responsibilities.

### Where votes happen

- **Official decisions:** GitHub Discussions (permanent, traceable record)
- **Standard PR votes:** Automated Discord bot announcing each open vote in `#votes` with remaining time

---

## 8. Technical Infrastructure

### Repository structure

```
project-vazkael/
├── README.md
├── CONTRIBUTING.md
├── CHARTER.md
├── CONTRIBUTORS.md
├── LICENSE (MIT)
├── docs/
│   ├── GDD.md
│   ├── art-style-guide.md
│   ├── lore-bible.md
│   └── combat-system.md
├── game/
│   ├── project.godot
│   ├── scenes/
│   ├── scripts/
│   ├── assets/
│   │   ├── sprites/
│   │   ├── audio/
│   │   ├── ui/
│   │   └── vfx/
│   └── data/
│       ├── items.json
│       ├── skills.json
│       └── enemies.json
├── .github/
│   ├── workflows/
│   │   ├── moderation.yml
│   │   ├── tests.yml
│   │   └── build.yml
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
└── tools/
    ├── moderation-bot/
    └── balance-checker/
```

### Key technical rule — data separated from code

All skills, items, and enemies are defined in `.json` files in `game/data/`, not in code. This allows contributors without programming skills to add content by filling in a structured text file.

### Branch strategy

- `main` — stable branch, always playable, what players download
- `develop` — integration branch, all validated PRs land here first
- `feature/name` — individual contribution branches

**Naming convention:** `art/sprite-goblin-archer`, `gameplay/ice-nova-skill`, `fix/wall-collision-bug`

**Release cycle:** One public release per month with patch notes listing all contributors of the cycle.

### GitHub labels

`🎮 gameplay` `🎨 art` `⚙️ code` `📖 lore` `🐛 bugfix` `🔥 breaking` `📋 data` `🚫 blocked` `⚠️ review required` `🗳️ in vote` `✅ approved` `🌍 translation`

### Tech stack

| Element | Choice |
|---|---|
| Engine | Godot 4 |
| Primary language | GDScript |
| Game data | JSON (`game/data/`) |
| CI/CD | GitHub Actions |
| AI moderation | Sightengine (free tier) |
| Community | GitHub Discussions + Discord |
| Multiplayer | Nakama or Colyseus (open source, community-hosted) |

---

## 9. Legal & Financial

### License

MIT License. The game, its code, and its assets are free to use, modify, and redistribute, provided the license notice is retained and no patents are filed on project elements.

Under MIT, anyone can fork the project. In practice, the community and reputation remain with the original repository.

### Financial model

**At launch: zero cost, zero donations.**

All tools used are free (GitHub, Discord, GitHub Actions, Sightengine free tier). No funding mechanism is active at launch. The question of community donations may be submitted to a community vote in the future if the community wishes to introduce it.

### AI-generated assets — legal note

The legal framework for AI-generated visual assets remains in active evolution across international jurisdictions. The prohibition on AI visual assets protects all contributors from potential legal exposure, regardless of their country of residence.

### Contributor responsibility

Participation is voluntary. The project cannot be held liable for any personal expenses incurred by contributors. No contributor is required to purchase any tool or service to participate — all core tools are free.

### Age & data protection

Minimum contributing age: 16 years. This covers GDPR digital consent requirements across European jurisdictions. Contributors are responsible for accurately representing their age.

### Project name

"Project Vazkael" is a code name for development purposes. The final game name will be chosen by community vote. A trademark clearance search will be conducted before any final name is publicly adopted.

---

## 10. Launch Plan

Project Vazkael launches in two distinct phases. There is no timeline, no deadline, no pressure. Every milestone happens when the community is ready — not before.

---

### Phase 1 — Setting the stage

*This phase is handled by the founder before opening the project to the community.*

Everything needed for contributors to arrive and feel immediately at home:

- [ ] Create GitHub organization "project-vazkael"
- [ ] Publish README, CHARTER, GDD, CONTRIBUTING
- [ ] Create and configure Discord server (channels + roles)
- [ ] Initialize empty Godot 4 project with defined folder structure
- [ ] Configure AI moderation workflow (Sightengine + GitHub Actions)
- [ ] Open the first "good first issues" to give newcomers an immediate entry point

Once this foundation is in place, the project opens its doors. No roadmap is published yet. The community comes first.

---

### Phase 2 — The community takes over

*Everything from here is decided by the community, at the community's pace.*

There is no imposed schedule. The first people to join are invited to explore, discuss, share ideas, and contribute at whatever rhythm feels natural to them. Every contribution — however small — matters and is permanently credited.

Once enough people have joined and feel ready, the community itself initiates:

- A vote on the **shader / rendering style** (cel-shading, toon, etc.) with visual proposals from artists
- The creation of the **visual art style reference** with the first artists
- The election of the **first maintainers** by category
- A vote on the **first roadmap** — what to build, in what order, at what pace

The roadmap belongs to the community. It is written by the people who build the game, not before they arrive.

---

## Community roadmap

The following phases are a vision, not a commitment. Timing and priorities will be defined by community vote.

| Phase | Vision | Status |
|---|---|---|
| v0.1 | First playable experience — 1 character, 1 zone, core feel | ⏳ Community decides |
| v0.2 | 3 weapon archetypes, skill specialization system | ⏳ Community decides |
| v0.3 | First endgame loop — procedural maps, full loot, craft | ⏳ Community decides |
| v1.0 | Full campaign, 6 weapons, stable endgame | 🎯 Long-term vision |

The roadmap is revisited and updated by community vote every quarter.

---

*Forged by the community · Driven by passion · Free forever*

*Project Vazkael — 2026*
