# Rulebook: Mist Wars
**Version:** 0.2  
**Core Concept:** A Grand Strategy Wargame resolved through a Tag-based Narrative System.

---

## 1. The Core Resolution
Actions are resolved by rolling **2D6** plus or minus modifiers from relevant **Tags** and **Statuses**.

| Result | Outcome | Power Spend Allowed |
| :--- | :--- | :--- |
| **10+ (Strong Hit)** | Complete Success | **100%** of Potential Power |
| **7 – 9 (Weak Hit)** | Success at a cost | **50%** of Potential Power (Round Up) |
| **6 or less (Miss)** | Failure | **0** Power |

### **1.1 The Power Formula**
When a hit (7+) is scored, calculate the **Potential Power**:
> **$\text{Sum of Strength Tags} - \text{Sum of Weakness Tags}$** > * **The Floor Rule:** Potential Power is **always at least 1**, even if weaknesses outweigh strengths.

### **1.2 Standard Power Costs**
Power must be spent immediately on the action's targets:
* **1 Power:** Reduce Objective by 1; Add/Remove 1 Status Level; Clear 1 Temp Tag.
* **2 Power:** Create a new Temp Tag; Force an enemy unit to retreat 1 square.
* **3 Power:** Create a persistent Region Tag (e.g., *Fortified, Scorched Earth*).

---

## 2. Unit Anatomy
Units are defined by a limited number of slots to prevent "Tag Bloat."

### **2.1 Permanent Traits**
* **Tier 1 (Basic/Militia):** 1 Strength Tag, 1 Weakness Tag.
* **Tier 2 (Professional):** 2 Strength Tags, 1 Weakness Tag.
* **Tier 3 (Elite/Specialized):** 3 Strength Tags, 1 Weakness Tag.

### **2.2 Status & Tag Slots**
* **Positive Status (Max 1):** A tiered bonus (e.g., *Entrenched 2*).
* **Negative Status (Max 1):** A tiered penalty (e.g., *Suppressed 3*). 
* **Temporary Tag Slots (Max 2):** Circumstantial modifiers (e.g., *High Ground*).

### **2.3 The Breaking Point (Level 5)**
If a Negative Status reaches **Level 5**, the unit is removed. The status type determines the outcome:
* **Damage 5:** Unit is **Destroyed**.
* **Exposed 5:** Unit is **Captured** (Enemy may gain a Strategic Intel tag).
* **Disarray 5:** Unit is **Routed** (May be recovered via Recruit action later).

---

## 3. Actions

### **I. Move Action**
* **Empty Region:** 1 square per turn. No roll required.
* **Occupied Region (Engagement):** Requires a roll using Military tags.
    * **Hit:** Spend Power to retreat the enemy or gain a tactical Status (*Flanking 1*).
    * **Weak Hit:** Enter square, but GM applies a consequence (e.g., *Suppressed 1*).
    * **Miss:** Movement fails. Unit is pinned or forced back.

### **II. Logistics Action**
* *Requires Logistics Unit.*
* **Hit:** Spend Power to "Heal" status levels, add defensive Tags, or fortify Objectives.

### **III. Recruit Action**
* *Requires Logistics Unit.*
* **Hit:** Spend Power to bring new units to the HQ or recover "Routed" units.

### **IV. Covert Ops Action**
* *Requires Covert Unit.*
* **Hit:** Spend Power to apply/remove tags. Targeting an enemy HQ can project statuses (e.g., *Exposed 2*) to distant regions.

### **V. Military Ops Action**
* *Requires Military Unit.*
* **Hit:** The primary way to spend Power to reduce **Region Objectives**.

---

## 4. Region Objectives & Global Tags
Regions are not "captured" by killing all units, but by completing Objectives.

* **Objective Points:** Regions are captured by reducing Objectives (e.g., *Supply Hub: 10*) to 0.
* **Resolution:** When points reach 0, the defender must retreat.
* **Modifiers:** Enemy units in a region act as negative modifiers to Military Ops actions targeting the Objective.
* **Global Tags:** Each nation starts with a **Doctrine** (e.g., *Blitzkrieg: +1 to Move rolls, -1 to Logistics Power*) that applies to all relevant rolls.

---

## 🗒️ TODO List
- [ ] **Fog of War:** Define "Scanning" vs "Hidden" mechanics for Covert Ops.
- [ ] **Map Scale:** Finalize grid type and Logistics "tether" range.
- [ ] **Turn Structure:** Finalize Alternating Activation vs Full Phase.
- [ ] **Unit Catalog:** Create starter profiles for "Standard Infantry" and "Standard Armor."
