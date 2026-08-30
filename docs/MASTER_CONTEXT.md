AUREX — MASTER CONTEXT

Context 01 — AUREX 3D Game Project Foundation

«Purpose of this document:
This file preserves the current known project context for AUREX so that a future AI agent or developer can understand the project without access to the original ChatGPT conversation.

Future agents must read this document before making significant project decisions or implementation changes.»

---

1. PROJECT IDENTITY

Project Name

AUREX

AUREX is a new, separate game project being planned as a full 3D first-person adventure, puzzle, and exploration game.

The project direction emerged from the desire to move beyond the previous OOPS-style level-based trap/platform experience and create something significantly more immersive and cinematic.

AUREX is intended to be a flagship game project with a stronger focus on:

- Immersion
- Exploration
- Mystery
- Environmental storytelling
- Puzzle solving
- Cinematic moments
- Large-scale environments
- Visual atmosphere

---

2. RELATIONSHIP TO OOPS

CONFIRMED

AUREX and OOPS are separate projects.

OOPS is an existing game project with its own gameplay direction, deployment history, and development issues.

AUREX must NOT be implemented as a rewrite inside the OOPS codebase.

AUREX should be treated as a new project with its own:

- Codebase
- Architecture
- Gameplay systems
- Visual identity
- World design
- Development roadmap

Do not automatically reuse OOPS gameplay concepts inside AUREX.

The previous OOPS development experience is useful as a lesson, especially regarding project scope and gameplay validation, but AUREX itself is a separate product.

---

3. CORE GAME DIRECTION

CURRENT PROJECT DIRECTION

AUREX is planned as a:

«First-Person 3D Adventure / Puzzle / Exploration Game»

The player experiences the game through a first-person perspective.

The game should emphasize being physically present inside large and visually distinctive worlds.

The player experience should not revolve around repetitive:

«Trap → Death → Restart»

Instead, the intended gameplay loop is:

«Explore → Observe → Discover → Solve → Survive → Progress»

This loop represents the current intended backbone of the AUREX experience.

---

4. PLAYER EXPERIENCE GOAL

The player should feel that they are entering and exploring unknown worlds.

Important intended feelings include:

- Curiosity
- Discovery
- Mystery
- Scale
- Immersion
- Suspense
- Satisfaction from solving environmental problems

The game should encourage players to look around and understand their surroundings.

Environmental design should have gameplay meaning.

The player should not simply move through a long sequence of disconnected traps.

Instead, gameplay should combine:

- Exploration
- Observation
- Environmental interaction
- Puzzle solving
- Environmental danger
- Discovery
- Progression

---

5. DEVELOPMENT PHILOSOPHY

CONFIRMED DEVELOPMENT DIRECTION

AUREX should use a:

«Prototype First → Validate → Expand»

development strategy.

Do NOT begin by building:

- Huge open worlds
- All worlds simultaneously
- Hundreds of levels
- Massive amounts of assets
- Complex story systems
- Large quantities of mechanics

Instead:

«Build one small playable area and make it genuinely good.»

The first prototype should prove that:

- Movement feels good
- First-person exploration feels good
- The environment is interesting
- Interaction feels meaningful
- Puzzle solving is enjoyable
- The overall experience has potential

Only after the core experience is validated should large-scale production expand.

---

6. FIRST DEVELOPMENT TARGET

PROPOSED: A SMALL VERTICAL SLICE

The first major playable target should not be a complete world.

Instead, build a small approximately 5–10 minute playable experience.

The purpose is to validate the core game.

The vertical slice may include:

- First-person movement
- Exploration
- A visually impressive environment
- One environmental problem
- One interaction or puzzle
- Environmental danger
- A cinematic or visually memorable moment

The goal is for the player to experience a small but complete sequence.

---

7. PROPOSED FIRST WORLD

WORLD 1 — FLOATING SKY CIVILIZATION

STATUS: PROPOSED

The first world concept discussed is a large and visually striking sky environment.

Potential visual elements include:

- Floating islands
- Clouds
- Large open skies
- Ancient ruins
- Broken structures
- Broken bridges or routes
- Massive distant architecture
- Strong vertical scale
- Mysterious civilization

The player should experience a sense of height and scale.

The environment should create an early visual "wow" moment.

---

8. PROPOSED FIRST VERTICAL SLICE FLOW

A possible sequence discussed:

Step 1 — Arrival / Exploration

The player begins in a visually striking sky environment.

The player is allowed to look around and absorb the scale of the environment.

---

Step 2 — Environmental Obstacle

The player's route forward is blocked.

For example, a broken bridge or inaccessible path.

The obstacle should encourage observation rather than immediately presenting a simple button.

---

Step 3 — Discovery

The player explores the surrounding environment.

The player discovers a mechanism or environmental clue.

---

Step 4 — Puzzle

The player interacts with the environment and solves a small puzzle.

The solution should feel connected to the world.

---

Step 5 — Environmental Change or Danger

After the puzzle, the environment changes.

Possible examples include:

- A route changing
- A structure moving
- A bridge becoming unstable
- A new danger emerging

Exact mechanics remain undecided.

---

Step 6 — Survival / Escape

The player must respond to the changing environment.

This should create a short moment of tension.

---

Step 7 — Cinematic Reveal

The player reaches or sees a new large location.

The game creates a strong visual moment that suggests a larger world beyond the initial area.

This sequence is a proposed vertical-slice concept and is NOT yet confirmed production content.

---

9. PROPOSED WORLD CONCEPTS

The following world concepts were discussed.

Their final order and inclusion are still subject to future decisions.

---

World 1 — Floating Sky Civilization

Focus:

- Discovery
- Height
- Scale
- Mystery
- Exploration

Status:

PROPOSED

---

World 2 — Mystical Giant Forest

Possible focus:

- Exploration
- Living environment
- Mystery
- Large-scale nature
- Distinct environmental identity

Status:

PROPOSED

---

World 3 — Abandoned Mechanical World

Possible focus:

- Machinery
- Environmental puzzles
- Mechanical systems
- Industrial danger
- Abandoned technology

Status:

PROPOSED

---

World 4 — Lost Ancient Civilization

Possible focus:

- Ancient mystery
- Monumental structures
- Environmental storytelling
- Exploration
- Historical secrets

Status:

PROPOSED

---

10. VISUAL DIRECTION

PROPOSED ART DIRECTION

The current visual recommendation is:

«Stylized Realism + Cinematic Lighting»

The intention is to create an immersive and premium visual experience without attempting to directly reproduce the exact technical complexity of a photorealistic AAA game.

Desired characteristics:

- Realistic proportions
- Cinematic lighting
- Atmospheric environments
- Strong environmental scale
- Visually distinctive worlds
- High-quality presentation

Avoid:

- Overly cartoonish visual design
- Direct imitation of another game's exact visual identity
- Unrealistic scope caused by trying to build full AAA photorealism immediately

The project should aim for:

«High visual impact with practical development constraints.»

---

11. FIRST-PERSON CORE GAME FEEL

Before building large environments, the basic player experience should be tested.

The prototype should evaluate:

- Walking
- Running
- Jumping
- Looking around
- Camera feel
- Movement acceleration
- Air control if appropriate
- Collision
- Gravity
- Jump feel
- Mouse sensitivity
- Camera smoothing
- Field of View

A key development principle discussed:

«If moving around an empty prototype environment does not feel good, adding beautiful graphics will not solve the core problem.»

Movement and interaction should therefore be tested early.

---

12. PROPOSED GAMEPLAY SYSTEMS

The following systems were discussed as possible future components.

Their exact implementation is NOT yet confirmed.

---

Player Interaction

Possible player actions include:

- Inspecting objects
- Activating objects
- Interacting with environmental mechanisms
- Pulling or pushing objects where appropriate
- Other world-specific interactions

Exact mechanics remain pending.

---

Puzzle System

Puzzles should be integrated into the environment.

Avoid generic puzzles that could be placed in any world without changing.

Prefer:

«World → Environment → Problem → Discovery → Solution»

---

Hazard System

Environmental dangers should not simply reproduce OOPS-style repetitive traps.

Instead, danger should ideally involve:

«Environment → Warning → Player Observation → Player Reaction → Consequence»

The exact hazard mechanics remain undecided.

---

Checkpoint System

A checkpoint system is planned as a possible gameplay quality feature.

The goal would be to avoid unnecessary replay of large sections after failure.

Exact implementation remains pending.

---

Save / Progression System

Saving world and progression state is planned as a future system.

Potential information:

- World progress
- Checkpoint progress
- Player settings

Exact design remains pending.

---

13. PROPOSED TECHNICAL DIRECTION

GAME ENGINE

The current recommended engine is:

«Unity»

STATUS:

PROPOSED / CURRENT RECOMMENDATION

Unity was considered because of its support for:

- 3D development
- First-person gameplay
- Physics
- Lighting
- Animation
- Large development ecosystem
- Multiple platform possibilities

However:

«Unity installation is NOT confirmed as completed in this context.»

«AUREX Unity project creation is NOT confirmed as completed in this context.»

Therefore, future agents must NOT assume that a Unity project already exists unless the repository itself confirms it.

---

14. PROPOSED PROJECT ARCHITECTURE

A conceptual project organization was discussed.

STATUS:

PROPOSED — NOT YET IMPLEMENTED

AUREX
│
├── Core
│   ├── GameManager
│   ├── SaveSystem
│   └── SceneManager
│
├── Player
│   ├── Movement
│   ├── Camera
│   └── Interaction
│
├── World
│   ├── WorldManager
│   ├── Environment
│   └── Transitions
│
├── Gameplay
│   ├── PuzzleSystem
│   ├── InteractionSystem
│   └── HazardSystem
│
├── UI
│
├── Audio
│
└── Cinematics

This is NOT established code architecture.

Before implementing anything, future developers or AI agents must inspect the actual repository.

---

15. DEVELOPMENT ROADMAP

The current proposed development sequence is:

Phase 0 — Pre-Production

Define and confirm:

- Core game identity
- Player experience
- Game concept
- World concepts
- Visual direction
- Technical direction
- Target platforms
- Core gameplay loop

---

Phase 1 — Technical Foundation

After technology decisions are confirmed:

- Set up the game project
- Establish a clean project structure
- Prepare a minimal development environment

---

Phase 2 — Core Game Feel

Build and test:

- First-person movement
- Camera
- Physics
- Interaction basics

The focus should be gameplay feel rather than graphics.

---

Phase 3 — Vertical Slice

Build one small playable environment.

Include:

- Visual atmosphere
- Exploration
- Interaction
- Puzzle
- Environmental danger
- Cinematic moment

Then playtest and evaluate.

---

Phase 4 — Validate

Determine:

- Is the movement satisfying?
- Is exploration enjoyable?
- Is the puzzle interaction interesting?
- Does the environment create immersion?
- Is the game actually fun?

Do NOT expand significantly before answering these questions.

---

Phase 5 — Production Expansion

Only after validation:

- Expand World 1
- Build supporting systems
- Improve visuals
- Add progression
- Continue to future worlds

---

16. IMPORTANT DEVELOPMENT RULE

A principle discussed for AUREX:

«NO FEATURE WITHOUT A PURPOSE»

Before adding a mechanic, system, animation, puzzle, visual effect, or feature, determine:

«Does this improve the player experience?»

Do not add systems only because they appear technically impressive.

---

17. COMPLETED WORK

As of Context 01:

Completed / Discussed

- AUREX project direction has been established at a planning level.
- AUREX has been separated conceptually from OOPS.
- First-person 3D direction has been discussed.
- Prototype-first development has been selected as the preferred development approach.
- Unity has been identified as the current recommended engine candidate.
- Multiple world concepts have been proposed.
- A visual direction of stylized realism and cinematic lighting has been proposed.
- GitHub has been selected as the intended persistent memory location for project continuity.

---

18. NOT YET COMPLETED

The following are NOT confirmed as completed:

- Unity installation
- Unity project creation
- First-person controller implementation
- Gameplay implementation
- Environment implementation
- World implementation
- Puzzle implementation
- Hazard implementation
- Animation implementation
- Asset pipeline
- Production development
- Final technical architecture

Future agents must inspect the repository before claiming otherwise.

---

19. KNOWN LESSONS / RISKS

AUREX development should avoid repeating the previous problem of building large quantities of content before validating the actual player experience.

The primary risk is:

«Building many levels, systems, or assets before confirming that the core game is genuinely enjoyable.»

Therefore:

«Prototype first. Validate the fun. Then expand.»

---

20. PENDING DECISIONS

The following decisions remain open:

- Final narrative premise
- Player identity
- Why the player enters or explores the worlds
- How the worlds are connected
- Final world order
- Final world list
- Exact core mechanics
- Exact puzzle mechanics
- Exact hazard mechanics
- Final engine/version
- Target platforms
- Asset creation pipeline
- Performance targets
- Monetization model
- Distribution model
- Final story structure

Future agents must not assume these decisions are finalized.

---

21. IMMEDIATE NEXT STEP

The next development-oriented step is:

«Continue AUREX pre-production and lock the core game vision before beginning full production implementation.»

After the core vision is sufficiently clear:

«Confirm the technical setup and create a small first-person prototype.»

The first major goal should remain:

«ONE SMALL PLAYABLE AREA → MAKE IT GOOD → TEST IT → EXPAND»

---

CONTEXT HISTORY

Context 01 — Current Chat

This context established the currently documented AUREX direction:

- AUREX as a separate project from OOPS
- Full 3D game direction
- First-person perspective
- Adventure / puzzle / exploration gameplay direction
- Prototype-first development philosophy
- Unity as current recommended engine
- Stylized realism + cinematic lighting as proposed visual direction
- Floating Sky Civilization as proposed first-world concept
- Additional proposed worlds
- Small vertical slice before full production
- GitHub as persistent project memory

Future contexts must preserve this history.

Do not silently overwrite confirmed or historical decisions.

If future decisions change any part of this document, mark the previous decision as superseded and record the new decision with its context number.
