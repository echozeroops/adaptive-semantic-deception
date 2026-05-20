# ASD System Flow Diagrams

This document contains simplified conceptual diagrams for the Adaptive Semantic Deception architecture.

The diagrams are intentionally abstract.

They describe semantic control flow, not implementation details.

---

## High-Level System Flow

```text
┌──────────────────┐
│    Observer      │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│ Observation Layer│
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│  ObserverModel   │
└────────┬─────────┘
         │
         ▼
┌────────────────────────┐
│ ReconstructedHypothesis│
└────────┬───────────────┘
         │
         ▼
┌──────────────────┐
│ IllusionStrategy │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│ SafetyBoundary   │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│ ProjectionWorld  │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│ Artifact Emission│
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│  DecisionTrace   │
└──────────────────┘
```

---

## Observer-State Control Loop

```text
Observer Action
      ↓
Signal Interpretation
      ↓
ObserverModel Update
      ↓
Hypothesis Reconstruction
      ↓
Projection Strategy Selection
      ↓
Safety Validation
      ↓
ProjectionWorld Update
      ↓
Artifact Exposure
      ↓
Observer Belief Update
      ↓
Next Observer Action
```

---

## ProjectionWorld Lifecycle

```text
ProjectionWorld Created
        ↓
Initial Semantic Boundaries Defined
        ↓
Controlled Artifacts Introduced
        ↓
Observer Interaction Observed
        ↓
Projection Consistency Evaluated
        ↓
Pacing Adjusted
        ↓
ProjectionWorld Updated
        ↓
DecisionTrace Recorded
        ↓
Projection Continues / Stabilizes / Terminates
```

---

## Defensive Time Acquisition Flow

```text
Hostile Exploration
        ↓
Controlled Interaction Sustained
        ↓
Observer Assumptions Shaped
        ↓
Exploration Redirected
        ↓
Confidence Delayed
        ↓
Adversarial Resources Consumed
        ↓
Defensive Reaction Window Extended
```

---

## Safety Priority Model

```text
Candidate Projection Action
          ↓
Strategic Value Evaluation
          ↓
SafetyBoundary Check
          ↓
RealityBoundary Check
          ↓
ExposureBudget Check
          ↓
Semantic Consistency Check
          ↓
Allowed / Rejected
```

---

## Minimal Runtime Components

```text
┌─────────────────────┐
│ ObserverEvent        │
├─────────────────────┤
│ ObserverModel        │
├─────────────────────┤
│ ReconstructedHyp.    │
├─────────────────────┤
│ ProjectionWorld      │
├─────────────────────┤
│ IllusionStrategy     │
├─────────────────────┤
│ SafetyBoundary       │
├─────────────────────┤
│ DecisionTrace        │
└─────────────────────┘
```

---

## Conceptual Boundary

```text
REAL OPERATIONAL ENVIRONMENT
        │
        │ protected by RealityBoundary
        ▼
PROJECTED SEMANTIC ENVIRONMENT
        │
        │ experienced by Observer
        ▼
OBSERVER COGNITIVE SURFACE
```

---

## Notes

These diagrams are not final implementation diagrams.

They represent the current public conceptual structure of ASD as an active semantic defense architecture.
