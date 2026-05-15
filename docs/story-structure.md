# Story Structure

## Project Overview

This project is an experimental solo hypertext adventure designed to explore both narrative structure and production workflow.

The story is being developed directly in implementation format rather than through a large pre-production framework. The goal is to learn where systems, templates, and tooling become necessary through practical production experience.

---

# Core Premise

The player is traveling toward a known destination along a familiar road when an unnatural fog rolls in.

When the fog finally clears, the player finds themselves standing in an unfamiliar harvest field beneath an unfamiliar sky.

After navigating the strange countryside, the player encounters a nearby farmstead occupied by an old farmer named Eldon and his grandchildren.

That night, the grandson disappears into the fields.

The player and the granddaughter set out to find him.

---

# Tone

The tone is:
- quiet
- uncanny
- atmospheric
- grounded before supernatural escalation

The fields themselves should feel subtly wrong before overt danger appears.

Inspirations include:
- harvest horror
- folk horror
- liminal spaces
- isolated rural landscapes

---

# Narrative Structure

The adventure currently uses:
- linear progression
- light divergence
- fast reconvergence

Choices primarily:
- alter perspective
- reveal optional information
- affect tone and context

The structure intentionally avoids large branching complexity during early development.

---

# Failure Philosophy

Failure and death are not punitive.

Failure nodes should:
- reinforce tone
- encourage replay
- reveal information
- invite experimentation

---

# Current Playable Slice

The current vertical slice covers:

1. The road
2. The fog
3. The strange field
4. Early investigation
5. Meeting Eldon and his grandchildren
6. Initial combat encounter
7. Arrival at the farmstead

---

# Hypertext Structure Model

The project currently uses the following structure:

## Nodes
Nodes are containers for:
- inputs
- persistent state checks
- passages
- choices

Nodes are structural/logical units.

---

## Passages
Passages are the actual text displayed to the player.

Types of passages include:
- entry passages
- shared passages
- conditional passages

---

## Inputs
Inputs represent how a player entered a node.

Example:
- FORWARD
- PAUSE
- CALL

Inputs allow nodes to display different entry passages without requiring fully separate branches.

---

## Persistent States
Persistent states track meaningful earlier choices.

Example:
- PAUSE = TRUE

Persistent states allow future nodes to react to earlier player behavior.

---

# Current Threats

## Carnivorous Cobbs

Small predatory creatures resembling twisted corncobs.

They are intended to:
- introduce danger early
- reinforce the hostility of the fields
- suggest the environment itself may be alive or corrupted

---

# Current Development Philosophy

The project currently prioritizes:
- fast iteration
- playable prototypes
- learning through implementation
- minimal technical overhead
- avoiding premature systems
