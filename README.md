# GAME PROJECT BASE
Use this as to clone as an engine-agnostic base for your game-dev projects. This includes all necessary documentation templates to start.

## FILE STRUCTURE
/
├── README.md
├── adrs/
├── dev-diaries
├── gdds
│   ├── art-style.md
│   ├── master-gdd.md
│   ├── setting.md
│   ├── story.md
│   ├── scope.md
│   ├── systems/
│   │   ├── combat.md

## DOCS AND THEIR PURPOSES
- adrs/
  - List of technical design decisions made and why, so that standards can be enforced
- dev-diaries/
  - Optional, but helpful for solo/education projects. Should contain file(s) listing progress and/or what was learned
- gdds/art-style.md
  - describes art direction, intended player feel, and inspirations
- gdds/master-gdd.md
  - lists design pillars, high-level goals and intended experience/feelings when playing
- gdds/setting.md
  - describes setting to give context and continuity so story + systems adhere to master design
- gdds/story.md
  - describes what's being done in the world, and should make sense as something someone would want to do in this world
- gdds/scope.md
  - feature list required for MVP, story events, and intended play time
- systems/
  - contains an individual doc for every system in the game (combat is supplied for an example)
