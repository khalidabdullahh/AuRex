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


AUREX — MASTER CONTEXT 02

Implementation Strategy & AI-Assisted Development Plan

---

1. PROJECT STATUS

AUREX is a completely new and independent game project.

It is NOT a continuation, conversion, or rewrite of OOPS.

OOPS remains a separate existing project and should not be mixed with AUREX.

AUREX is being developed as a new long-term game IP with its own:

- Brand identity
- Game architecture
- Gameplay systems
- Worlds
- Visual direction
- Technology stack
- Development workflow

The project is currently entering the actual game development phase, but development must begin with planning and prototyping rather than immediately building the full game.

---

2. CORE PROJECT VISION

Game Name

AUREX

AUREX is intended to become an immersive and cinematic game experience.

The project direction is:

«First-Person 3D Adventure + Exploration + Puzzle + Environmental Survival»

The goal is to create a game where the player feels physically present inside the world.

The intended experience is:

«Explore → Observe → Discover → Understand → Solve → Survive → Progress»

AUREX should not feel like a traditional repetitive level-based trap game.

The focus is not:

«Trap → Die → Restart → Repeat»

Instead, the focus should be:

«Enter an unknown world → Explore → Notice something unusual → Understand the environment → Solve problems → Face environmental danger → Discover what lies ahead.»

---

3. FIRST-PERSON IMMERSION

AUREX will be a full 3D game experienced primarily from a first-person perspective.

The player should feel as though they are looking through the character's eyes.

Core first-person experience:

- Look around freely
- Walk
- Run
- Jump
- Explore environments
- Observe distant structures
- Interact with objects
- Solve environmental puzzles
- Encounter environmental hazards
- Discover hidden locations

The visual and movement experience should prioritize immersion.

The design goal is not to copy any existing game, but to achieve a high level of environmental immersion, cinematic presentation, spatial depth, lighting, animation, and player presence.

---

4. WORLD PHILOSOPHY

AUREX is planned as a multi-world game universe.

Each world must have its own:

- Visual identity
- Environmental atmosphere
- Gameplay philosophy
- Puzzle style
- Environmental dangers
- Audio identity
- Story discoveries

Worlds must not simply be different colored versions of the same gameplay.

A mechanic or concept should not automatically be repeated across worlds.

Each new world should make the player feel:

«"I have entered a completely different place."»

Current high-level world concepts:

---

WORLD 1 — FLOATING SKY CIVILIZATION

Core feeling:

- Discovery
- Height
- Scale
- Awe
- Mystery
- Isolation

Possible environment elements:

- Floating islands
- Ancient ruins
- Broken temples
- Bridges between structures
- Clouds
- Massive distant architecture
- Waterfalls falling into the sky or unknown depths

Primary emotional experience:

«"Where am I, and how is this place even possible?"»

---

WORLD 2 — MYSTICAL GIANT FOREST

Core feeling:

- Exploration
- Wonder
- Mystery
- Living environment

Possible environment elements:

- Giant trees
- Massive roots
- Giant plants
- Fog
- Glowing vegetation
- Hidden pathways
- Ancient structures absorbed by nature

Primary emotional experience:

«"This world feels alive."»

---

WORLD 3 — ABANDONED MECHANICAL WORLD

Core feeling:

- Industrial mystery
- Scale
- Danger
- Mechanical systems

Possible environment elements:

- Massive machinery
- Moving gears
- Steam
- Industrial ruins
- Broken robots or unknown machines
- Giant mechanical structures

Primary emotional experience:

«"Something enormous used to operate here."»

---

WORLD 4 — LOST ANCIENT CIVILIZATION

Core feeling:

- Discovery
- Ancient mystery
- Hidden history
- Large-scale architecture

Possible environment elements:

- Ancient temples
- Underground chambers
- Massive statues
- Forgotten cities
- Secret passages
- Collapsing structures

Primary emotional experience:

«"Someone built this. What happened to them?"»

---

5. IMPORTANT SCOPE RULE

Do NOT attempt to build all worlds at once.

Do NOT begin with:

- Four complete worlds
- Huge maps
- Hundreds of levels
- Large amounts of story
- Hundreds of gameplay systems

The first objective is to prove that the game is genuinely fun and immersive.

Development must follow:

SMALL PROTOTYPE → TEST → IMPROVE → VALIDATE → EXPAND

---

6. GAME ENGINE

The current planned engine is:

UNITY

Unity will be used as the primary game engine for:

- 3D rendering
- First-person gameplay
- Physics
- Collision
- Lighting
- Animation
- Scene construction
- Audio
- UI
- Gameplay systems
- Puzzle systems
- Environmental hazards

Unity is the actual runtime environment where AUREX will become a playable game.

AI tools do not replace the game engine.

---

7. AI-ASSISTED DEVELOPMENT STRATEGY

AUREX will use AI extensively.

However:

«AI will accelerate development.
Unity will run the actual game.
Human playtesting will determine whether the game is fun.»

AI can assist with:

Visual Development

- Concept art
- Environment concepts
- World mood exploration
- Architecture ideas
- Object variations
- Texture concepts
- Material concepts
- Asset planning

Programming

- C# script assistance
- Gameplay system architecture
- Debugging
- Code review
- Refactoring suggestions
- Documentation

Game Design

- Puzzle concepts
- Environmental challenges
- Level flow
- Exploration design
- Progression design

Story

- Lore development
- World history
- Environmental storytelling
- Dialogue concepts if required
- Cinematic planning

Production

- Asset lists
- Development checklists
- Testing plans
- Documentation
- Bug analysis

AI-generated images or concepts should not automatically be treated as finished game assets.

Playable game environments may require:

- 3D models
- Materials
- Textures
- Collision
- Optimization
- Lighting
- Animation
- LOD or equivalent performance systems

---

8. DEVELOPMENT WORKFLOW

The development pipeline should operate as follows:

HUMAN VISION

↓
Game design and final decisions

AI ASSISTANCE

↓
Concepts, planning, code assistance, asset assistance, debugging

UNITY IMPLEMENTATION

↓
Scenes, gameplay, physics, interaction, lighting, animation

PLAYTESTING

↓
Evaluate fun, immersion, difficulty and technical stability

ITERATION

↓
Improve the weakest part and test again

This cycle should repeat continuously.

---

9. PHASE 0 — PRE-PRODUCTION

Before building major gameplay content, the following must be clarified and documented:

- Core game identity
- Target platform
- Art direction
- Core gameplay loop
- Player role
- World connection philosophy
- Interaction philosophy
- Puzzle philosophy
- Environmental hazard philosophy
- Audio direction
- Progression philosophy

No major production content should begin until the core direction is sufficiently stable.

However, documentation must not become endless planning.

The goal is to reach a point where a prototype can be built.

---

10. PHASE 1 — UNITY FOUNDATION

Create the AUREX Unity project.

Establish a clean project structure.

Suggested conceptual organization:

AUREX

- Core
  
  - Game management
  - Scene management
  - Save system

- Player
  
  - Movement
  - Camera
  - Interaction

- Gameplay
  
  - Puzzle systems
  - Hazard systems
  - Interaction systems

- World
  
  - Environment
  - World management
  - Transitions

- UI

- Audio

- Cinematics

This structure should remain flexible.

Do not create unnecessary complex architecture before systems actually require it.

---

11. PHASE 2 — CORE PLAYER FEEL

Before creating beautiful environments, create and test the first-person player experience.

The initial prototype should include:

- Walking
- Running
- Jumping
- Looking around
- Collision
- Basic gravity

The player controller must then be tuned.

Important variables include:

- Movement speed
- Acceleration
- Deceleration
- Jump height
- Gravity
- Air control
- Camera sensitivity
- Camera smoothing
- Field of view

The core principle is:

«If movement does not feel satisfying in a simple prototype environment, graphics will not solve the problem.»

Player feel must be tested before major environment production begins.

---

12. PHASE 3 — FIRST PLAYABLE VERTICAL SLICE

The first major milestone is NOT World 1.

It is NOT a complete game.

It is:

ONE SMALL PLAYABLE AUREX EXPERIENCE

Target length:

Approximately 5–10 minutes.

Initial setting:

WORLD 1 — FLOATING SKY CIVILIZATION

The prototype should demonstrate the complete intended AUREX experience.

Suggested experience structure:

1. Player begins in a visually interesting location.

2. Player looks around and understands the scale of the world.

3. Player explores a small area.

4. Player discovers a blocked route or environmental problem.

5. Player observes the environment for clues.

6. Player interacts with a mechanism or solves a simple environmental puzzle.

7. The environment changes or introduces danger.

8. Player navigates through the danger.

9. The experience ends with a cinematic or visually memorable reveal.

The vertical slice should answer one question:

"Is AUREX actually fun and immersive to play?"

If the answer is no, improve the prototype.

Do not expand into a huge game until the answer is yes.

---

13. ART DIRECTION

The current preferred direction is:

STYLIZED REALISM + CINEMATIC PRESENTATION

Avoid two extremes:

- Completely cartoon-like visuals
- Attempting ultra-realistic AAA graphics immediately

The visual target should prioritize:

- Realistic proportions
- Strong environment composition
- Atmospheric lighting
- Depth
- Fog where appropriate
- Environmental scale
- Cinematic moments

The objective is not maximum polygon count.

The objective is:

«A visually beautiful world that performs well and creates atmosphere.»

Performance must be considered from the beginning.

---

14. GRAPHICS AND ASSET STRATEGY

AUREX may use a combination of:

- Original assets
- AI-assisted concepts
- AI-assisted asset creation where technically suitable
- Existing legally usable assets
- Manually created Unity environments

Every asset used must be evaluated for:

- Technical compatibility
- Performance
- Licensing/commercial usage rights
- Visual consistency

Do not fill the game with random assets from different visual styles.

Each world needs a coherent visual identity.

---

15. CORE GAMEPLAY SYSTEMS — FUTURE IMPLEMENTATION

After the vertical slice is validated, expand the gameplay systems gradually.

Potential systems include:

Interaction

- Inspect
- Activate
- Pull
- Push
- Trigger mechanisms

Only add interaction types that genuinely improve gameplay.

Puzzles

Puzzles should primarily emerge from the environment.

Avoid inserting unrelated generic puzzles into every location.

Environmental Hazards

The game should avoid relying on repetitive:

«Instant trap → Death → Restart»

Environmental danger should instead create:

- Observation
- Tension
- Reaction
- Consequence

Checkpoints

Checkpoints should be fair.

The player should not repeatedly replay long sections because of poorly placed checkpoints.

Save System

Eventually track:

- Progress
- World state where necessary
- Settings
- Checkpoints where appropriate

---

16. TESTING PHILOSOPHY

Every major system must be tested before expanding the project.

Test:

- Movement
- Collision
- Physics
- Interaction
- Puzzle flow
- Player recovery
- Checkpoints
- Performance
- Scene loading

Do not build large amounts of content on top of broken foundations.

The development loop is:

BUILD SMALL
↓
PLAY
↓
FIND PROBLEMS
↓
FIX
↓
PLAY AGAIN
↓
EXPAND

---

17. PERFORMANCE STRATEGY

AUREX is a 3D project.

Therefore performance must be considered from the beginning.

Avoid:

- Excessive high-poly objects
- Excessive dynamic lights
- Unnecessary real-time effects
- Extremely large scenes without optimization
- Hundreds of active objects when unnecessary

Visual quality must be balanced with:

- Target hardware
- Frame rate
- Memory usage
- Loading time

The first prototype should remain relatively small and optimized.

---

18. PRODUCTION EXPANSION RULE

Only after the vertical slice successfully demonstrates:

- Good movement
- Good gameplay feel
- Visual appeal
- Immersion
- Stable technical performance

should major World 1 production begin.

Production flow:

CORE FOUNDATION
↓
PLAYER PROTOTYPE
↓
VERTICAL SLICE
↓
PLAYTEST
↓
ITERATE
↓
VALIDATE
↓
WORLD 1 PRODUCTION
↓
POLISH
↓
NEXT WORLD

---

19. PROJECT SEPARATION

AUREX and OOPS must remain separate.

OOPS:

- Existing project
- Existing codebase
- Existing gameplay identity
- Existing web deployment

AUREX:

- New game
- New architecture
- New Unity project
- New gameplay philosophy
- New visual identity

Do not attempt to convert the OOPS codebase into AUREX.

Do not mix OOPS mechanics into AUREX unless a specific concept is intentionally redesigned and approved.

---

20. MASTER DEVELOPMENT PRINCIPLE

The most important rule for AUREX is:

DO NOT BUILD BIG BEFORE PROVING THE EXPERIENCE IS GOOD.

Do not repeat the mistake of creating a large amount of content before confirming that the core game is enjoyable.

The first major goal is not:

«Build World 1.»

The first major goal is:

«Build a small 5–10 minute experience that makes the player genuinely want to continue.»

Once that experience works, AUREX can expand confidently.

---

CURRENT IMPLEMENTATION STATUS

AUREX is currently in:

PRE-PRODUCTION → TECHNICAL SETUP → CORE PROTOTYPE

Immediate next steps:

1. Finalize core vision details.
2. Install and configure Unity.
3. Create the AUREX Unity project.
4. Build and test the first-person controller.
5. Create a simple prototype environment.
6. Validate movement and core player feel.
7. Design the first World 1 vertical slice.
8. Begin visual/environment implementation only after the core experience is validated.

---

FINAL PROJECT MINDSET

AUREX should be developed as a long-term game project.

The goal is not to generate a large amount of content quickly.

The goal is to gradually build:

«A stable foundation
→ a satisfying player experience
→ a visually memorable world
→ a complete game universe.»

AI should be used aggressively as a development accelerator, but final gameplay decisions must be validated through actual playtesting.

AUREX DEVELOPMENT PRINCIPLE

«SMALL EXPERIENCE.
TEST EVERYTHING.
KEEP WHAT IS FUN.
REMOVE WHAT IS NOT.
THEN EXPAND.»
