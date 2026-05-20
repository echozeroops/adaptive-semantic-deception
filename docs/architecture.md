# ASD Architecture

Adaptive Semantic Deception (ASD) is an active defensive architecture designed to guide an observer through a controlled semantic projection environment.

The core architectural goal of ASD is not to block interaction, but to shape the observer's reconstructed model of the environment.

ASD does not ask:

> What should the system answer?

It asks:

> What should the observer believe after this interaction?

---

## Architectural Orientation

ASD is built around observer-state reconstruction and adaptive projection-world management.

The central object of the system is not a network request, a session, or a single event.

The central object is the observer's reconstructed hypothesis.

This means that every interaction is treated as an opportunity to update, reinforce, redirect, or constrain the observer's current model of the environment.

---

## Core Cycle

```text
Observation
    ↓
ObserverModel Update
    ↓
ReconstructedHypothesis
    ↓
IllusionStrategy
    ↓
SafetyBoundary / RealityBoundary
    ↓
ProjectionWorld Update
    ↓
Artifact Emission
    ↓
DecisionTrace Logging
```

---

## Main Layers

### Observation Layer

Normalizes incoming interaction signals into observer events.

This layer does not define the meaning of an interaction by itself. It only provides structured evidence for observer-state reconstruction.

### Observer Modeling Layer

Maintains an internal model of what the observer appears to know, test, assume, and believe.

This layer updates the ObserverModel and tracks changes in the ReconstructedHypothesis.

### Strategy Layer

Determines how the system should influence the observer's next belief state.

The strategy layer does not simply select a response. It selects a projection direction.

### Projection Layer

Maintains the ProjectionWorld, including semantic continuity, apparent structure, exposed artifacts, and locally consistent environmental state.

### Safety Layer

Constrains all projection behavior.

It prevents uncontrolled exposure, semantic leakage, unsafe escalation, and projection drift outside defensive boundaries.

### Audit Layer

Records decisions, hypothesis transitions, emitted artifacts, and safety decisions through DecisionTrace.

---

## ProjectionWorld

ProjectionWorld is the controlled semantic environment experienced by the observer.

It is not a collection of fake responses.

It is a persistent and internally consistent model of an apparent operational reality.

A ProjectionWorld should preserve:

- local consistency
- narrative coherence
- controlled imperfection
- gradual discovery
- bounded exposure
- separation from real operational assets

---

## ReconstructedHypothesis

ReconstructedHypothesis is the system's current estimate of what the observer believes.

It represents the observer's perceived environment, not the real environment.

ASD uses this object to decide whether the observer should be reinforced, redirected, slowed down, or constrained.

---

---

## AI Orchestration Core

AI is a central reasoning component in ASD, but it is not the security boundary.

The AI Orchestration Core is responsible for semantic reasoning tasks such as:
- interpreting ObserverModel state
- reconstructing ReconstructedHypothesis
- proposing IllusionStrategy
- assisting with projection planning
- supporting adaptive narrative control
- generating candidate artifacts for ProjectionWorld

AI is used because deterministic rules alone are not sufficient for reconstructing observer belief states or planning coherent semantic projection paths.

However, AI must operate inside strict isolation.

---

## Defensive Root Environment

ASD requires a separated defensive root environment.

The defensive root environment contains the real operational truth of the system and must remain isolated from ProjectionWorld.

This root environment may include:
- real infrastructure state
- defensive policies
- RealityBoundary enforcement
- SafetyBoundary logic
- telemetry and DecisionTrace storage
- allowlisted snapshots for AI reasoning

ProjectionWorld must never be allowed to directly access or modify the defensive root environment.

---

## AI Isolation Principle

AI must never receive direct access to real operational assets.

AI should only receive allowlisted, read-only context such as:
- ObserverModel
- ProjectionWorld snapshot
- ExposureBudget state
- selected DecisionTrace context
- sanitized semantic constraints

AI must not receive:
- real infrastructure configuration
- privileged operational data
- secret topology
- raw defensive control state
- unrestricted telemetry
- RealityBoundary internals

If AI can access the real environment, then compromise or failure of the AI layer may become compromise of the Truth Core.

---

## Deterministic Safety Boundary

SafetyBoundary and RealityBoundary must be implemented as deterministic, testable system components.

They must not exist only as AI instructions or prompt rules.

A prompt such as:

> do not reveal real data

is not a security boundary.

A real boundary must be enforced by code, validation, allowlists, deny rules, and auditable checks outside the AI layer.

All AI outputs must pass through:
- SafetyBoundary validation
- RealityBoundary validation
- ExposureBudget validation
- semantic consistency checking
- forbidden-pattern checking

Only validated outputs may update ProjectionWorld or become emitted artifacts.

---

## Environment Separation Model

```text
DEFENSIVE ROOT ENVIRONMENT
(real state, policies, telemetry, boundaries)
        │
        │ allowlisted read-only snapshots
        ▼
AI ORCHESTRATION CORE
(semantic reasoning, hypothesis reconstruction, strategy proposal)
        │
        │ validated candidate actions
        ▼
SAFETY / REALITY BOUNDARY
(deterministic validation and enforcement)
        │
        │ approved projection updates
        ▼
PROJECTION WORLD
(controlled semantic environment observed by the observer)
```

The observer interacts only with ProjectionWorld.

AI reasons only over sanitized snapshots.

The defensive root environment remains isolated and authoritative.

## Defensive Nature

ASD is an active-defense architecture.

It is designed for controlled defensive environments where adversary interaction is observed, shaped, constrained, and audited.

ASD is not designed for unauthorized access, exploitation, intrusion, or offensive deployment.

---

One of the operational goals of ASD is defensive time acquisition.

By maintaining controlled semantic environments and managing observer perception, ASD attempts to:
- slow hostile progression
- delay confident decision-making
- increase exploratory uncertainty
- reduce rapid escalation
- extend defensive reaction windows

The objective is not merely deception.

The objective is to create enough controlled temporal space for defensive observation, analysis, containment, and response.

Unlike traditional defensive systems focused primarily on rapid detection and blocking, ASD treats interaction itself as a defensive resource.

ASD does not necessarily attempt to immediately terminate observer interaction.

Instead, the architecture attempts to:
- sustain controlled interaction
- shape observer assumptions
- redirect exploration
- delay confident escalation
- consume adversarial attention and operational resources
- increase uncertainty
- extend defensive reaction windows

The objective is not passive defense.

The objective is controlled active-defense interaction inside bounded semantic environments.

## Design Principles

1. The observer's belief state is the primary control surface.
2. Projection must remain semantically coherent.
3. Safety boundaries override strategy.
4. Exposure must be paced and limited.
5. The system must remain auditable.
6. ProjectionWorld must not leak real operational structure.
7. ASD should be transport-agnostic and adapter-based.
8. Every emitted artifact becomes part of future consistency.

---

## Minimal Runtime Shape

A minimal ASD runtime would contain:

```text
ObserverEvent
ObserverModel
ReconstructedHypothesis
ProjectionWorld
IllusionStrategy
SafetyBoundary
DecisionTrace
```

This minimal form is enough to test the central architectural idea:

> Can a defensive system shape an observer's evolving model of an environment through controlled semantic projection?

---

## Current Status

This architecture is currently conceptual and research-oriented.

The next development step is a minimal simulation runtime capable of:

- tracking observer-state changes
- maintaining ProjectionWorld consistency
- generating bounded artifacts
- logging DecisionTrace
- testing basic deception-effectiveness metrics
