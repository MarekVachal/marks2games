---
title: "Resources"
description: "Understand the resources that drive your empire, from biomass and metals to research and expeditions."
---

## Resources

The economy of **Gravity Game** is built around a network of connected resources. Some are stored locally on a planet, some are global across the empire, and some are virtual outputs that must be used immediately.

The empire rules divide resources into several categories:
- stored resources with limited capacity
- temporary resources that cannot be stored
- resources with unlimited accumulation toward milestones
- special-purpose resources with unique rules

The resource flow diagram in the rules also shows that the system is intentionally interconnected: biomass supports research and progress, metals and organic sediments feed industry, and rocket materials feed both expansion and warship construction.

---

## Biomass

**Biomass** exists naturally on a planet and does not need to be mined. It can be consumed directly.

Its growth per turn is:

**capacity / 10 - organic sediments growth**

Capitol and Empty Districts increase biomass capacity. Small planets have 50% higher biomass capacity. Biomass cannot be transported or traded.

---

## Metals

Each planet has a limited amount of **Metals reserves**. To use metals, they must first be extracted by **Prospectors**.

Extracted metals are stored separately from the planet’s natural reserve. Their storage capacity is increased by **Prospectors** and **Capitol**. Metals can be transported between planets and sold through Trade.

---

## Organic Sediments

**Organic Sediments** start at zero on each planet and grow based on biomass.

Their increase per turn is:

**biomass / 10**, rounded down

This same growth value is also used in the biomass calculation. The maximum planetary reserve of organic sediments is 1000.

Like metals, organic sediments must be extracted by **Prospectors** before they can be used. They can be transported, sold, and are also used to pay for transport.

---

## Rocket Materials

**Rocket Materials** are produced in **Industrials** from metals and organic sediments.

They are stored locally on the planet. Storage capacity is increased by **Industrials** and **Capitol**. Rocket materials are used for:
- colonization ships
- warship components

They can also be transported and sold.

---

## Infrastructure

**Infrastructure** is a virtual resource representing engineering and construction work.

It is required for:
- Progress
- Development
- building new districts
- changing district modes

Infrastructure cannot be stored between turns. Any unused infrastructure is converted into **Development** at the end of the turn.

---

## Influence

**Influence** is a temporary resource produced by **Urban Centers**.

It cannot be stored between turns. It is needed for:
- planetary progress
- warship maintenance

Each warship consumes 10 Influence per turn for upkeep. Unused Influence is converted into **Tradepower** for the next turn.

---

## Expeditions

**Expeditions** are created in an **Expedition Platform** from Rocket Materials.

They are stored globally in the empire and have no capacity limit. Once enough Expedition points are accumulated, the empire gains a new planet.

---

## Warship Materials

**Warship Materials** are also created in an **Expedition Platform** from Rocket Materials.

They are stored locally on the planet, have no capacity limit, and require no upkeep. Once enough are accumulated, they can be spent to create a warship.

---

## Research

**Research** is created in **Urban Centers** and is transferred into the empire-wide pool.

It has no storage limit and no upkeep cost. It is spent to unlock technologies. The technology tree in the rules shows that research unlocks new district modes, transport, influence generation, trade access, military ship production, synergies, and repeatable empire upgrades.

---

## Progress

**Progress** is generated in the **Capitol**.

It is used in two ways:
- larger planets consume it to maintain their level
- when enough is accumulated, the planet levels up and unlocks a new empty district

---

## Development

**Development** currently has no final role defined in the rules, but it is described as a likely future resource for defensive systems against alien attacks and raiders.

---

## Tradepower

**Tradepower** is generated from unused Influence in the previous turn.

Its role is to reduce taxes on Trade transactions.

---

## Related sections

- [Planets](../planets/)
- [Districts](../districts/)
- [Production](../production/)
- [Technologies](../technologies/)
- [Battles](../battles/)
