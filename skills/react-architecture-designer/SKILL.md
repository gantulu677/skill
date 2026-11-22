---
name: react-architecture-designer
description: Design and review React application architecture, including routing, layouts, page registries, state boundaries, and component contracts.
---
# React Architecture Designer

## Purpose
Translate product and technical requirements into a coherent React architecture with explicit responsibilities, contracts, dependencies, and validation criteria.

## Triggers
Use for greenfield architecture, architecture decisions, refactoring plans, route/layout design, component boundaries, application shells, and architecture audits.

## Principles
- Start from requirements and user journeys, not folder conventions.
- Separate route resolution, layout composition, page rendering, and overlays.
- Define one authoritative source for each kind of configuration.
- Make state ownership and data flow explicit.
- Distinguish metadata from runtime behavior.
- Confirm library versions and capabilities rather than assuming them.

## Workflow
1. Discover framework/version, platforms, product scope, existing code, constraints, and non-functional requirements.
2. Model routes, page types, layouts, shared UI, overlays, and user flows.
3. Assign ownership for routing, registries, layout selection, data access, state, loading, and errors.
4. Specify schemas, required/optional fields, enums, uniqueness, references, fallbacks, and validation.
5. Map dependencies and identify cycles or competing sources of truth.
6. Compare alternatives by complexity, extensibility, cost, and migration impact.
7. Validate representative routes, page/layout combinations, loading, errors, and overlay transitions.
8. Record rationale, trade-offs, assumptions, rejected options, and open decisions.
9. Break approved design into implementation steps and acceptance criteria.

## Review checklist
Routes resolve deterministically; layout selection has a clear owner; page reuse is explicit; metadata semantics are defined; unknown routes and render failures are handled; loading and error boundaries have distinct roles; transient UI lifecycle is defined; state ownership is clear; contracts validate; dependencies are acyclic.

## Safety
Do not silently turn proposals into approved decisions. Label assumptions and open questions. Do not modify code unless explicitly authorized. Treat existing code as evidence, not automatically as desired design.

## Output
Architecture overview, responsibility map, route/layout model, contracts, dependency map, alternatives/trade-offs, risks, open decisions, and testable acceptance criteria.

## Completion
Responsibilities and contracts are unambiguous, key success/failure paths are covered, dependencies are understood, and decisions are verifiable.
