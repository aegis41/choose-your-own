# Codex Brief

## Project Summary

This project is a small hypertext solo adventure built using plain HTML, CSS, and JavaScript.

The current goal is to create a lightweight playable prototype for Nodes 001–002 before expanding further.

The emphasis is:
- readability
- narrative flow
- modular structure
- experimentation
- simplicity

Do not overengineer the implementation.

---

# Technical Constraints

Use:
- plain HTML
- plain CSS
- plain JavaScript

Do NOT use:
- frameworks
- TypeScript
- build tools
- databases
- routing libraries
- React/Vue/Angular
- save/load systems
- inventory systems
- combat systems

---

# Initial Required Files

Create:

- index.html
- style.css
- script.js

---

# Prototype Goals

The prototype should support:

- rendering passages
- rendering choices
- moving between nodes
- passing input labels between nodes
- displaying different entry passages based on input
- displaying shared passages after entry passages

---

# Current Structural Model

## Nodes
Nodes are logical containers.

Each node may contain:
- inputs
- persistent state checks
- entry passages
- shared passages
- choices

---

## Passages
Passages are the actual text displayed to the player.

Example passage types:
- FORWARD
- PAUSE
- SHARED

---

## Inputs
Inputs are passed between nodes based on player choices.

Example:
- Continue forward → 002 (FORWARD)

---

# Current Nodes

## Node 001
"The Road"

Supports:
- START input
- FORWARD choice
- PAUSE choice

---

## Node 002
"The Fog"

Supports:
- FORWARD input
- PAUSE input
- shared fog passage
- multiple choices leading into Node 003

---

# UI Goals

The UI should be:
- readable
- atmospheric
- minimalist
- easy to expand

Recommended:
- centered text column
- dark/light atmospheric styling
- clickable buttons or links for choices
- smooth readability on desktop

No advanced styling required yet.

---

# Architecture Goals

The architecture should prioritize:
- simplicity
- easy editing
- easy node expansion
- understandable flow

The code should remain approachable for a beginner/intermediate developer.

---

# Immediate Deliverable

A functioning prototype where:

1. Node 001 displays
2. Player selects FORWARD or PAUSE
3. Node 002 renders the correct entry passage
4. Shared fog passage renders
5. Player can continue toward Node 003

The prototype does not need a completed Node 003 implementation yet.
