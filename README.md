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
* **Tier:** (1, 2, or 3)
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

## 5. Factions & Regional Caps
Each Union has a "Global Tag".

---

## 🗒️ TODO List
- [ ] **Aptitude Glossary:** List specific permissions for tags like `innate-flight` or `heavy-engineering`.
- [ ] **Growth Triggers:** Define the exact requirements for a Tier increase.
- [ ] **Unit Catalog:** Generate the starting rosters for the three Unions.
- [ ] **Fog of War:** Mechanics for hidden units.

---

**Next Step:** Since the rules are now fully documented, would you like to start the **Unit Catalog** for the first faction, or should we define the **Growth Triggers** (how units actually level up)?
