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
