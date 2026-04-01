# ADSS — Agentic Decision System Specification

The system design standard for multi-agent workflows.

ADSS defines how autonomous systems are structured, how agents interact, and where decisions occur within a system.

---

## Relationship to SIS

ADSS and SIS operate at different layers of the same system.

- **ADSS defines the system structure**
- **SIS defines the decision contract within that structure**

ADSS describes:

- flows
- stages
- agents
- transitions
- feedback loops

SIS defines:

- how each decision is evaluated
- whether it is admissible
- whether it can be executed

> ADSS structures the system.  
> SIS governs each decision inside it.

---

## Why ADSS Exists

Most AI systems fail due to poor structure, not poor intelligence.

Common failure points:

- unclear process flows
- undefined agent responsibilities
- hidden or inconsistent decision points
- lack of feedback loops
- fragmented orchestration across systems

Traditional process design tools were built for human workflows.

They do not translate well to:

- autonomous agents
- continuous decision systems
- dynamic, state-driven environments

ADSS exists to define:

> how multi-agent systems are designed before they are built and executed

---

## What ADSS Standardizes

ADSS introduces a canonical structure for designing agent systems:

- **Flows** — ordered sequences of system activity
- **Stages** — logical groupings of behavior
- **Agents** — actors responsible for execution
- **Decision Points** — where SIS evaluation is required
- **Transitions** — how systems move between stages
- **Feedback Loops** — how systems adapt and re-enter flows

---

## Where ADSS Fits

```text
[ System Design ]
        ↓
====== ADSS ======
(structure + flow)
        ↓
[ Decision Points ]
        ↓
====== SIS ======
(decision contract)
        ↓
[ Execution Systems ]

⸻

## Specification

The full specification is available in:
/spec/adss.md

⸻

## Status
	•	Version: Draft v0.2.0
	•	This standard is under active development and open for feedback

⸻

## License

This project is released under the MIT License.

⸻

## Contributing

Contributions, feedback, and implementation discussions are welcome.
This standard is intended to be open and implementation-agnostic.

