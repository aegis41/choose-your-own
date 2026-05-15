# Node Map

This document tracks the current narrative node structure for the opening playable slice.

---

# Node Structure Format

Each node contains:
- ID
- title
- responsibility
- inputs
- passages
- choices

---

# 001 — The Road (Narrative)

## Responsibility
Establish the player traveling toward a known destination and set tone.

## Inputs
- START

## Choices
- Continue forward → 002 (FORWARD)
- Pause and take in your surroundings → 002 (PAUSE)

---

# 002 — The Fog (Narrative)

## Responsibility
Introduce disorientation and transition from known to unknown.

## Inputs
- FORWARD (from 001)
- PAUSE (from 001)

## Passages

### FORWARD
The player continues forward immediately.

### PAUSE
The player takes time observing the road and environment before the fog arrives.

### SHARED — The Fog
The fog consumes the road and the world becomes obscured.

## Choices
- Push forward through the fog → 003 (FORWARD)
- Try to orient yourself → 003 (ORIENT)
- Wait for the fog to clear → 003 (WAIT)

---

# 003 — The Field (Choice)

## Responsibility
Reveal the harvest field and establish displacement and unease.

## Inputs
- FORWARD
- ORIENT
- WAIT

## Persistent States
- PAUSE

## Planned Features
- input-based entry passages
- optional PAUSE-based passage
- shared reveal passage
- first meaningful exploration choices

## Planned Choices
- Stay still and listen
- Walk toward distant movement
- Call out
- Examine familiar flowers (requires PAUSE)

---

# Planned Future Nodes

004 — Initial field reaction  
005 — Investigation  
006 — Meet Eldon  
007 — Meet grandchildren  
008 — Early exploration  
009 — Carnivorous Cobb encounter  
010 — Travel to farmstead  
011 — Farmstead arrival

---

# Current Structural Notes

The project uses:
- light divergence
- fast reconvergence
- input-driven entry variation
- conditional passages
- limited persistent state tracking

The goal is to preserve player agency without exponential branching.
