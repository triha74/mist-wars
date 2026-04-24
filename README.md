# mist-wars

This document outlines the core mechanics for your strategic TTRPG. It is designed to be stored in a git repository and iterated upon as the design evolves.

---

# Rulebook: [Project Name Pending]
**Version:** 0.1  
**Core Concept:** A Grand Strategy Wargame resolved through a Tag-based Narrative System.

---

## 1. The Core Resolution
All actions (except simple movement into empty regions) are resolved by rolling **2D6** plus or minus modifiers from **Tags** and **Statuses**.

| Result | Outcome | Power Spent |
| :--- | :--- | :--- |
| **6 or less (Miss)** | Failure / Hard Consequence | 0 |
| **7 – 9 (Weak Hit)** | Success at a cost / Consequence | 1 – 2 |
| **10 or more (Strong Hit)** | Complete Success | 3 |

* **Power:** Used "inline" during the action to reduce Region Objectives or apply/remove Tags and Statuses.
* **Consequences:** Applied by the GM. Can include negative Statuses, losing a Temporary Tag, or environmental changes.

---

## 2. Unit Anatomy
To prevent "Tag Bloat," units follow a strict structure. An army typically consists of 4–8 units.

* **Permanent Strength Tags (1–3):** Defining traits (e.g., *Armored, Elite, Long-Range*).
* **Permanent Weakness Tag (1):** A baked-in flaw (e.g., *Slow, Inexperienced, Fuel-Hungry*).
* **Positive Status Slot (Max 1):** A tiered bonus (e.g., *Entrenched-2*).
* **Negative Status Slot (Max 1):** A tiered penalty (e.g., *Suppressed-3*). **If any Negative Status reaches Level 5, the unit is destroyed/captured.**
* **Temporary Tag Slots (Max 2):** Circumstantial modifiers (e.g., *High-Ground, Out of Position*).

---

## 3. Actions
Players take actions with their units one at a time.

### **I. Move Action**
* **Empty Region:** 1 square per turn. No roll required.
* **Occupied Region (Engagement):** Requires a roll.
    * **Strong Hit:** Enter square, gain positioning/momentum.
    * **Weak Hit:** Enter square, but take a consequence (e.g., *Suppressed-1*).
    * **Miss:** Movement fails. Unit is pinned in the previous square.

### **II. Logistics Action**
* *Requires Logistics Unit.*
* **Hit:** Spend Power to "Heal" statuses, add defensive Tags to a region, or increase Objective Strength (fortifying).

### **III. Recruit Action**
* *Requires Logistics Unit.*
* **Hit:** Spend Power to bring new units onto the board or recover "Routed" units.

### **IV. Covert Ops Action**
* *Requires Covert Unit.*
* **Hit:** Spend Power to apply/remove tags on units or regions. Can affect distant regions if targeting an HQ (e.g., *Exposed-2*).

### **V. Military Ops Action**
* *Requires Military Unit.*
* **Hit:** The primary way to spend Power to reduce **Region Objectives**.

---

## 4. Region Objectives
Regions are not "captured" by killing all units, but by completing Objectives.
* **Objective Points:** Each region has a value (e.g., *Bridge: 10 pts*).
* **Resolution:** When points reach 0, the defender must retreat.
* **Modifiers:** Enemy units in a region act as negative modifiers to Military Ops actions targeting the Objective.

---

## 5. Examples of Play

### **Example A: The Tank Assault**
* **Unit:** 1st Armored (*Tags: Armored, HE-Ammo; Weakness: Fuel-Hungry*)
* **Target:** Infantry in a *Town* objective.
* **The Roll:** +2 (Strengths) -1 (Town Cover) = **+1 Modifier**.
* **Result:** 10 (Strong Hit). 3 Power gained.
* **Spend:** Player spends 3 Power to reduce the *Town* objective from 10 to 7. Because it was a Strong Hit, no consequence is applied.

### **Example B: The Saboteur**
* **Unit:** Ghost Squad (*Tags: Stealthy; Weakness: Fragile*)
* **Action:** Infiltrate enemy HQ to help a battle 3 squares away.
* **Result:** Weak Hit. 2 Power gained.
* **Spend:** Player spends 2 Power to give a distant enemy Tank the status *Radio-Silence-2*.
* **Consequence:** The GM gives the Ghost Squad the Temp Tag *[Low-Batteries]* (filling one of their two slots).

---

## 🗒️ TODO List
- [ ] **Define Unit Tiers:** Determine exactly how many Strength tags Tier 1 (Infantry) vs Tier 3 (Special Forces) get.
- [ ] **Power Menu:** Create a standardized "Price List" for what 1, 2, and 3 Power can buy (e.g., Is "Retreat" 2 power or 3?).
- [ ] **Global Tags:** Draft a list of "National Doctrines" that players choose at the start of the game.
- [ ] **Fog of War:** Brainstorm mechanics for hidden units/statuses (e.g., only "revealed" if a Covert Ops or Engagement roll happens).
- [ ] **Map Scale:** Decide on the grid type (Hex vs Square) and how Logistics "reach" is calculated.
- [ ] **Turn Structure:** Determine if it is I-Go-You-Go or alternating unit activations.
