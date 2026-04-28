# Rulebook: Mist Wars
**Version:** 0.3  
**Core Concept:** A Grand Strategy Fantasy Wargame resolved through a Tag-based Narrative System.

---

## 1. The Core Resolution
Actions are resolved by rolling **2D6** plus or minus modifiers from relevant **Tags** and **Statuses**.

| Result | Outcome | Power Spend Allowed |
| :--- | :--- | :--- |
| **10+ (Strong Hit)** | Complete Success | **100%** of Potential Power |
| **7 – 9 (Weak Hit)** | Success at a cost | **50%** of Potential Power (Round Up) |
| **6 or less (Miss)** | Failure / Hard Consequence | **0** Power |

### **1.1 The Power Formula**
When a hit (7+) is scored, calculate the **Potential Power**:
> **$\text{Sum of Strength Tags} - \text{Sum of Weakness Tags}$** (Applied to the specific roll).
>
> * **The Floor Rule:** Potential Power is **always at least 1**, even if weaknesses outweigh strengths.

### **1.2 Standard Power Costs**
Power must be spent immediately on the action's targets:
* **1 Power:** Reduce Objective by 1; Add/Remove 1 Status Level; Clear 1 Temp Tag.
* **2 Power:** Create a new Temp Tag; Force an enemy unit to retreat 1 square.
* **3 Power:** Create a persistent Region Tag (e.g., *Fortified, Scorched Earth*).

---

## 2. Unit Anatomy
Units are defined by a limited number of slots to prevent "Tag Bloat" and ensure fast play.

### **2.1 Attributes**
* **Tier:** (1, 2, or 3) Defines number of Strength Tags
* **Aptitude:** Meta-tags that dictate narrative permissions and growth (e.g., `tactical`, `innate-magic`, `arcane-magic`).
* **Strengths:** (1–3 tags) Mechanical modifiers for the 2D6 roll.
* **Weakness:** (1 tag) A permanent mechanical penalty.

### **2.2 Tier Standards**
* **Tier 1 (Basic/Militia):** 1 Strength Tag.
* **Tier 2 (Professional):** 2 Strength Tags.
* **Tier 3 (Elite/Specialized):** 3 Strength Tags.

### **2.3 Status & Tag Slots**
* **Positive Status (Max 1):** A tiered bonus (e.g., *Inspired 2*).
* **Negative Status (Max 1):** A tiered penalty (e.g., *Damage 3*). 
* **Temporary Tag Slots (Max 2):** Circumstantial modifiers (e.g., *High Ground*).

### **2.4 The Breaking Point (Level 5)**
If a Negative Status reaches **Level 5**, the unit is removed. The status type determines the narrative outcome:
* **Damage 5:** Unit is **Destroyed**.
* **Exposed 5:** Unit is **Captured**.
* **Disarray 5:** Unit is **Routed**.

---

## 3. Magic & Aptitude
Magic is a narrative flavor for Tags, while Aptitude defines the scope of what a unit can achieve.

### **3.1 Aptitude as Permission**
Aptitudes do not modify the 2D6 roll. Instead, they provide "Narrative Permission."
* **Utility:** A unit with `innate-flight` can bypass "Chasm" regions without a roll.
* **Growth:** A unit can only gain Strength tags that align with their Aptitude (e.g., a `tactical` unit cannot learn *Fireball*).

### **3.2 Three Pillars of Aptitude**
1.  **Tactical:** Mastery through training, discipline, and physical tools. Not able to train any Abilites that require Innate-<Ability> or Arcane-<Ability>
2.  **Innate-<Ability>:** Natural untrained/tamed talent, limmited ability to the Ability. 
3.  **Arcane-<Ability>:** Natural talent that has trained and mastered the Ability. Can Grow this ability on their own.
---

## 4. Actions

### **I. Move Action**
* **Empty Region:** 1 square per turn. No roll required.
* **Occupied Region (Engagement):** Requires a roll using Military tags vs. Defender tags.
    * **Hit:** Spend Power to retreat the enemy or gain a tactical Status (*Superior Positioning 1*).
    * **Weak Hit:** Enter square, but take a consequence (e.g., *Suppressed 1*).
    * **Miss:** Movement fails. Unit is pinned or forced back.

### **II. Logistics Action**
* *Requires Logistics Unit.*
* **Hit:** Spend Power to "Heal" status levels, add defensive Tags, or fortify Objectives.

### **III. Recruit Action**
* *Requires Logistics Unit.*
* **Hit:** Spend Power to bring new units to an HQ or recover "Routed" units.

### **IV. Covert Ops Action**
* *Requires Covert Unit.*
* **Hit:** Spend Power to apply/remove tags. Targeting an HQ can project statuses to distant regions.

### **V. Military Ops Action**
* *Requires Military Unit.*
* **Hit:** The primary way to spend Power to reduce **Region Objectives**.

---

## 5. Factions & Regional Unions
---

### **I. The Highlanders (Mountain)**
* **Races:** Humans, Dwarfs, Snow Elves, Half-Orcs, Dragonborn.
* **Global Tag: [defend-the-highground-1]** - All units gain +1 to rolls when defending a position or a Region Objective.

#### **I. Units**

|Dwarf Ironbreaker|Military|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `sheild-wall`, `unshakable`|
|**Weakness**| `short-range`|

| Snow Elf Saboteur|Covert|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `snow-camouflage`, `vital-point-strike`|
|**Weakness**| `physically-fragile`|

| Human Sappers|Logistics|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `heavy-engineering`, `fortify-objective`|
|**Weakness**| `gear-dependent`|

| Half-Orc Tunnel-Runner Raiders|Mobile|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `close-quarters-fury`, `tunnel-maneuver`|
|**Weakness**| `reckless-abandon`|


### **II. The Tidal Alliance (Coastal)**
* **Races:** Humans, Tritons, Coastal Elves, Water Genasi, Harpies.
* **Global Tag: [costal-trade-1]** - Example usage: +1 Power to Actions on coast. Could also be to recruiting and logistics.

|Triton Phalanx|Military|
|---|---|
|**Tier**| 2|
|**Aptitude**| `innate-amphibious`|
|**Strength**| `pressure-resistant-armor`, `throw-the-net`|
|**Weakness**| `dry-land-fatigue`|

|Human Merchant-Marines|Military|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `disciplined-volleys`, `carries-supplies`|
|**Weakness**| `tethered-to-waterways`|

|Coastal Elf Saboteurs|Special|
|---|---|
|**Tier**| 2|
|**Aptitude**| `arcane-illusion`|
|**Strength**| `stealth-movement`, `confusing-mist`|
|**Weakness**| `low-physical-presence`|


|Water Genasi Supply Ship|Logistics|
|---|---|
|**Tier**| 2|
|**Aptitude**| `innate-amphibious`|
|**Strength**| `fluid-logistics`, `hydro-healing`|
|**Weakness**| `tethered-to-waterways`|


|Harpie Storm-Screechers|Mobility|
|---|---|
|**Tier**| 2|
|**Aptitude**| `innate-flight`|
|**Strength**| `dive-bomb-harassment`, `aerial-scouting`|
|**Weakness**| `hollow-bones`|



### **III. The Wardens of the Wild (Forest)**
* **Races:** Humans, Dryads, Wood Elves, Treants, Halfling Human Shifters.
* **Global Tag: [ambush-in-the-wild]** - Example usage: +1 Power to first Defensive Actions in wilderness.

|Treant Guardians|Military|
|---|---|
|**Tier**| 2|
|**Aptitude**| `innate-nature-magic`|
|**Strength**| `egenerative-bark`, `deep-roots`|
|**Weakness**| `very-large`|

|Wood Elf Archers|Military|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `woodland-sprint`, `precision-shot`|
|**Weakness**| `lightly-armored`|

|Human Shifter Stalkers|Covert|
|---|---|
|**Tier**| 2|
|**Aptitude**| `innate-shapeshifting`, `innate-senses`|
|**Strength**| `scent-tracker`, `feral-agility`|
|**Weakness**| `instinct-driven-distraction`|

|Dryad Ritualists|Logistics|
|---|---|
|**Tier**| 2|
|**Aptitude**| `innate-magic`|
|**Strength**| `nature-mending`, `summon-pixies`|
|**Weakness**| `bound-to-the-wilds`|

|Scout Pixies|Covert|
|---|---|
|**Tier**| 1|
|**Aptitude**| `innate-magic`|
|**Strength**| `teleport`|
|**Weakness**| `fragile-manifestation`|

|Saboteur Pixies|Covert|
|---|---|
|**Tier**| 1|
|**Aptitude**| `innate-magic`|
|**Strength**| `tinker-with-gadgets`|
|**Weakness**| `fragile-manifestation`|


### **IV. The United Tribes (Plains)**
* **Races:** Humans, Orcs, Ogres, Tabaxi, Goliaths.
* **Global Tag: [riders]** - Example usage: +1 to Attacks in the open or +1 to disengaging.

|Human Rider|Military|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `mounted-bow-shot`, `stealthy-moves`|
|**Weakness**| `no-retreat`|

|Tabaxi Prowler|Covert|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `sent-tracker`, `stealthy-moves`|
|**Weakness**| `impulsive`|

|Goliath Great-Load Bearers|Logistics|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `mountain-lungs`, `extreme-carrying-capacity`|
|**Weakness**| `massive-food-requirements`|

|Orc Warg-Riders|Mobile|
|---|---|
|**Tier**| 1|
|**Aptitude**| `tactical`|
|**Strength**| `thunderous-charge`, `swift-blow`|
|**Weakness**| `noisy-presence`|

|Human Caravan-Guard|Mobile|
|---|---|
|**Tier**| 2|
|**Aptitude**| `tactical`|
|**Strength**| `coordinated-thrust`, `swift-retreat`|
|**Weakness**| `exposed-in-tight-terrain`|

---
## 6. Renown & Growth
Every unit has a Renown Track with 3 slots. When the track is filled, the unit may "Evolve."

### **I Earning Renown
A unit gains 1 Renown mark when any of the following occur:

The Struggle (Weakness): The player voluntarily invokes the unit's Weakness as a negative modifier to a roll to represent a significant struggle.

The Burden (Status): The unit attempts a roll while suffering a Negative Status of Level 3 or higher.

The Heroic Hit: The unit scores a Strong Hit (10+) on a roll where they were at a mechanical disadvantage (more negative modifiers than positive).

### **II Evolution (Filling the Track)
When a unit earns 3 Renown marks, reset the track and choose one:

Tier Up: If the unit is below its Tier cap, increase its Tier and add a new Strength Tag (aligned with its Aptitude).

Shed the Burden: Permanently remove one Level 1 Negative Status or clear all Temporary Tags.

Adaptation: Replace its current Weakness with a new, different Weakness that reflects its recent history.
---

## 🗒️ TODO List
- [ ] **Aptitude Glossary:** List specific permissions for tags like `innate-flight` or `heavy-engineering`.
- [ ] **Growth Triggers:** Define the exact requirements for a Tier increase.
- [ ] **Unit Catalog:** Generate the starting rosters for the three Unions.
- [ ] **Fog of War:** Mechanics for hidden units.

---

**Next Step:** Since the rules are now fully documented, would you like to start the **Unit Catalog** for the first faction, or should we define the **Growth Triggers** (how units actually level up)?
