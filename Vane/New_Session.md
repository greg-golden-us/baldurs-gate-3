# Vane — New Session Prompt & Logging Template

Use this file as the exact prompt to provide a new AI collaborator. It contains the current party snapshot, the goal for the next session, constraints, and the output+log templates the AI must follow.

---

## Current Party (provide current snapshot; fill before asking)
- Vane: Level 5 Lore Bard / Warlock 2-equivalent (Cha 18 after Ethel Hair). Key gear: Phalar Aluve, Spellthief (slotted), Adamantine Shield, Potent Robe.
- Karlach: Level 5 Berserker (Con 18). Key gear: Kushigo Gloves, Caustic Band, Ring of Flinging, Returning Pike.
- Astarion: Level 5 Open Hand Monk (Dex 16). Key gear: Gloves of Thievery, Ring of Protection, Knife of the Undermountain King.
- Shadowheart: Level 5 Light Cleric (Wis 16). Key gear: Luminous Armour, Sword of Justice, Sentinel Shield.
- Bench: Wyll (Lvl 1 Hexblade economy engine), Gale & Lae'zel (buffers)

Map Status: Act 1 Wilderness 100% cleared; Underdark (Upper) 100% cleared. Current location example: Grand Mausoleum entry hall (X: -190, Y: 110).

Next Chapter Options (examples): Grymforge Descent OR Mountain Pass / Githyanki Crèche

---

## Instructions for the AI Agent (strict)
1. Propose a single next-chapter plan that prioritizes "high XP, low risk" pathing. Avoid optional high-risk ambushes unless they yield disproportionate guaranteed XP.
2. Keep recommendations tactical and mechanical — routing, waypoint coordinates, and expected XP sources.
3. Validate all suggestions against these guardrails: no multi-enemy ambushes, avoid low time-to-value detours, preserve camp buffer integrity, and prefer non-concentration secondary effects.
4. Output must follow the exact Chapter template below (do not deviate):

Chapter X: [Title]

* [The Action Subheading]: Step-by-step routing and dialogue choices executed (use coordinates where useful).
* [The Mechanic Subheading]: Exact spells/turn-1 actions, DCs, and mechanics used.
* Gear & Stats Secured: Exact item names and which companion receives them.

---

## After-Run Logging Template (fill this and return to the master document)
- Date & Time:
- Start Location & Waypoint:
- Party Composition (levels & key gear):
- Objective pursued:
- Path taken (waypoints, coordinates):
- Encounters (list, note if Turn-1 surprise achieved):
- XP gained (approx):
- Loot & Gear acquired:
- Casualties / near-misses:
- Short mechanical notes (what worked, what failed):
- Chapter Entry (paste the exact Chapter X entry using the Chapter template above):

---

Provide this New_Session.md content as the prompt to the new AI. After the run, copy the completed After-Run Logging Template into Vane/ and ask this assistant to integrate it into Playthrough_Guide.md and Leveling_Guides.md as appropriate.
