# Contributing to ADSS

ADSS defines the system design standard for multi-agent workflows.

This is not a general-purpose AI standard.

Contributions must align with the core purpose of ADSS.

---

## Scope of ADSS

ADSS defines:

- system structure
- flows
- stages
- agents
- decision points
- transitions
- feedback loops

ADSS does NOT define:

- decision logic
- execution authorization
- runtime enforcement
- policy evaluation

Those belong to SIS.

---

## Contribution Principles

All contributions must:

1. Preserve separation between ADSS (structure) and SIS (decision)
2. Improve clarity of system design
3. Avoid introducing runtime or governance logic into ADSS
4. Maintain simplicity and composability

---

## What Will Be Rejected

Submissions will be rejected if they introduce:

- execution control logic
- policy enforcement mechanisms
- runtime APIs
- decision evaluation logic

---

## Contribution Types

Accepted contributions include:

- schema improvements
- new node or flow modeling patterns
- additional examples
- documentation clarity improvements

---

## Versioning

All accepted changes will be versioned.

Breaking changes will result in a new version of the schema.

---

## Process

1. Open an issue describing the change
2. Submit a pull request with:
   - clear rationale
   - schema or documentation updates
3. Maintainer review and approval required

---

## Guiding Principle

ADSS defines how systems are structured before they are executed.

If a proposal affects execution behavior, it likely belongs in SIS, not ADSS.