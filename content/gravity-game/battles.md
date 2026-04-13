---
title: "Battles"
description: "Understand the tactical combat system and battle flow."
---

## Battles

Battles in **Gravity Game** are turn-based tactical encounters between two players. Each match represents a single battle, where both sides move their fleets, meet on contested fields, and fight for control.

The system is designed around planning, prediction, and risk management. Success depends not only on fleet composition, but also on positioning, timing, and deciding how much loss you are willing to accept.

---

## Battle structure

Each round consists of two phases:

1. **Fleet movement**
2. **Fleet encounters**

During the movement phase, both players reposition their fleets on the battlefield. After both players confirm their moves, all encounters are resolved.

A full battle ends when one player captures the enemy base.

---

## Units

Each player controls a fleet of **11 units**. There are four unit types in the game, each with its own role.

<div class="m2g-info-grid">

{{< m2g-card
  image="images/gravity-game/ships/cruiser.png"
  title="Cruiser"
>}}

- **Firepower:** 1
- **Shields:** 10

Cruisers are the basic backbone of a fleet. They provide stable combat value and high durability.

{{< /m2g-card >}}


{{< m2g-card
  image="images/gravity-game/ships/destroyer.png"
  title="Destroyer"
>}}

- **Firepower:** 2
- **Shields:** 10
- **Ability:** The total firepower of Destroyers cannot exceed the number of enemy units on the battlefield.

Destroyers are powerful offensive units, but their effectiveness depends on the size of the opposing fleet. Their strength is limited when facing only a small number of enemies.

{{< /m2g-card >}}


{{< m2g-card
  image="images/gravity-game/ships/ghost.png"
  title="Ghost"
>}}

- **Firepower:** 1
- **Shields:** 5
- **Ability:** Each Ghost disables one enemy Destroyer.

A disabled Destroyer is not destroyed, but it does not participate in combat as long as the Ghost that disables it remains alive. Ghosts are therefore a key counter-unit against Destroyer-heavy fleets.

{{< /m2g-card >}}


{{< m2g-card
  image="images/gravity-game/ships/warper.png"
  title="Warper"
>}}

- **Firepower:** 2
- **Shields:** 1
- **Ability:** Can move to any field during the movement phase.

Warpers are fragile but highly mobile. Their ability to move anywhere makes them useful for surprise attacks, reinforcement, or sudden repositioning.

{{< /m2g-card >}}

</div>

---

## Movement

Units move across the battlefield one field per turn, with one exception: the **Warper** can move to any field during the movement phase.

Additional movement rules:

- each player has **11 units total**
- a maximum of **6 units from one player** can occupy a single field
- this means up to **12 total units** may be present on one field at the same time
- units on a field controlled by the enemy cannot move to another enemy-controlled field

After both players finish planning their movement, the encounter phase begins.

---

## Fleet encounters

Whenever units from both players are present on the same field, a **fleet encounter** takes place.

Encounters are resolved in rounds until one side reaches its limit of acceptable losses.

---

## Maximum tolerable losses

Before combat, each player sets a value called **maximum tolerable losses**.

This represents the number of units that player is willing to lose in the encounter.

The encounter ends when one player reaches this limit. The player who reaches their tolerable losses loses the encounter.

This creates one of the most distinctive features of the battle system: players are not only deciding how to fight, but also how much risk they are willing to take.

---

## Fleet firepower

A fleet’s firepower is the sum of the firepower of all units currently able to fight.

Firepower is applied against the enemy unit type that is **most numerous** in the enemy fleet.

If multiple unit types are tied for the highest number, the following targeting priority is used:

**Cruiser > Destroyer > Ghost > Warper**

This means that fleet composition affects not only raw strength, but also which units are likely to take damage first.

---

## Attacks and damage

In each combat round, both fleets deal damage equal to their current firepower.

Damage is subtracted from the shields of the targeted unit type. If a unit loses all of its shields, any remaining damage continues to the next eligible unit according to the targeting priority.

Destroyed units are removed from the encounter and no longer contribute firepower.

Because fleet strength changes as units are destroyed, combat power can shift rapidly during an encounter.

---

## Firepower reduction

As enemy units are destroyed, the total firepower of a fleet may decrease.

This is especially important for **Destroyers**, because their total firepower cannot exceed the number of enemy units present on the battlefield.

As a result, removing enemy units is not just a matter of survival — it can directly reduce the opponent’s offensive potential.

---

## After the encounter

When an encounter ends:

- all surviving units are restored to their maximum shield values
- the winner gains control of the field
- if the encounter ends in a draw, the field remains under the control of its original owner

This means that each encounter is self-contained in terms of damage, but still has lasting strategic consequences through field control.

---

## Controlled field bonus

A player who controls a field receives a **+1 firepower bonus** in all future encounters fought on that field.

This makes territorial control important not only for movement and expansion, but also for direct combat effectiveness.

---

## Victory condition

Each player begins on their own **base field**.

If a player loses an encounter on their base and the opponent takes control of that field, the game is over.

In other words, victory is achieved by breaking through the enemy’s defenses and capturing their base.

---

## Why battles are different

The battle system in Gravity Game is not only about raw numbers. It is built around several interacting decisions:

- how to compose your fleet
- where to move and when
- which fields to defend or abandon
- how many losses you are willing to tolerate
- when to push forward and when to retreat

This creates battles where prediction, positioning, and risk management matter as much as direct force.

---

## Related sections

To understand how battles fit into the wider game, continue with the other parts of the guide:

- [Planets](../planets/)
- [Districts](../districts/)
- [Production](../production/)
- [Resources](../resources/)
- [Technologies](../technologies/)
