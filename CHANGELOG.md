# ADSS Changelog

All notable changes to the Agentic Decision System Specification (ADSS) are documented here.

---

## [0.1.0] — 2026-04-01

### Added
- Initial ADSS schema (`adss-v0.1.schema.json`)
- Example system definition (`adss-v0.1.example.json`)
- Core concepts:
  - flows
  - stages
  - agents
  - decision nodes (SIS-referenced)
  - transitions
  - feedback loops

### Changed
- Redefined ADSS as a system design (BPR) standard for multi-agent systems
- Removed decision authorization and runtime governance from scope

### Removed
- Execution authorization model (moved to SIS)
- Pre-execution governance framing
- Runtime API references (e.g., `/can_execute`)

### Notes
- ADSS now operates as the structural layer above SIS
- SIS defines decisions; ADSS defines where they occur