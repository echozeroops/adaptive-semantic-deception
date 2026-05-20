# Core Concepts

This document defines the primary conceptual objects used throughout the ASD architecture.

The goal of ASD is not merely to generate responses, but to manage observer perception through adaptive semantic environments.

---

## Observer

The external entity interacting with the system.

An observer may:
- probe
- explore
- validate
- test assumptions
- search for inconsistencies
- build an internal model of the environment

ASD treats the observer as a cognitive process rather than a simple event source.

---

## ObserverModel

ObserverModel is the system's internal representation of the observer's inferred cognitive state.

It contains estimated information about:
- current assumptions
- explored structures
- perceived environment
- interaction history
- confidence patterns
- apparent objectives
- suspicion indicators

ObserverModel is continuously updated during interaction.

---

## ReconstructedHypothesis

ReconstructedHypothesis represents the system's current estimate of what the observer believes about the environment.

This object is central to ASD.

ASD does not optimize for:
- response correctness
- protocol realism alone
- isolated interaction quality

ASD optimizes for:
- controlled belief evolution
- semantic continuity
- bounded perception shaping

---

## ProjectionWorld

ProjectionWorld is the semantic environment presented to the observer.

It is not a collection of isolated fake responses.

It is:
- persistent
- stateful
- internally consistent
- adaptive
- bounded by defensive constraints

ProjectionWorld evolves over time based on:
- observer behavior
- exposure pacing
- strategic objectives
- safety boundaries

---

## Artifact

An Artifact is any emitted object capable of influencing observer perception.

Artifacts may include:
- responses
- files
- metadata
- structures
- timing patterns
- environmental details
- semantic inconsistencies
- controlled imperfections

Every artifact contributes to future ProjectionWorld consistency.

---

## ExposureBudget

ExposureBudget controls how much semantic information may be revealed over time.

The goal is to prevent:
- overexposure
- accelerated discovery
- unrealistic projection density
- projection instability
- semantic collapse

ExposureBudget is one of the core defensive stabilizers of ASD.

---

## IllusionStrategy

IllusionStrategy determines how ASD attempts to influence the observer's evolving hypothesis state.

This may involve:
- reinforcement
- redirection
- delay
- ambiguity
- controlled discovery
- containment
- uncertainty shaping

IllusionStrategy never overrides SafetyBoundary constraints.

---

## SafetyBoundary

SafetyBoundary defines the hard constraints of the system.

Its role is to:
- prevent unsafe escalation
- avoid leakage of real operational structure
- constrain projection behavior
- enforce defensive limitations
- maintain bounded system behavior

SafetyBoundary always has higher priority than strategy.

---

## RealityBoundary

RealityBoundary separates:
- real operational assets
from
- projected semantic assets

This separation is critical for maintaining controlled defensive environments.

---

## DecisionTrace

DecisionTrace is the auditable history of:
- observer-state updates
- strategy selections
- artifact emissions
- safety decisions
- projection transitions

DecisionTrace enables:
- explainability
- debugging
- projection analysis
- consistency auditing
- behavioral reconstruction

---

## Semantic Continuity

Semantic Continuity is the requirement that ProjectionWorld remains internally coherent across time and interaction depth.

A failure of semantic continuity increases:
- observer suspicion
- projection instability
- detection probability

Maintaining semantic continuity is one of the primary architectural goals of ASD.

---

## Controlled Imperfection

ASD intentionally allows bounded imperfection inside ProjectionWorld.

Perfect environments often appear artificial.

Controlled imperfection improves:
- realism
- observer confidence
- environmental plausibility
- projection stability

Imperfection itself becomes part of the semantic strategy.

---

## Cognitive Surface

The Cognitive Surface is the total observable semantic interface experienced by the observer.

This includes:
- visible structures
- interaction timing
- environmental responses
- artifacts
- continuity patterns
- apparent operational logic

ASD operates primarily on the Cognitive Surface rather than directly on the observer.

---

## Active Semantic Defense

ASD defines defense as:
- perception shaping
- bounded semantic control
- observer-state management
- controlled environmental projection
- adaptive cognitive containment

The objective is not destruction or exploitation.

The objective is controlled defensive interaction.
