# Limitations

This document describes current architectural limitations, unresolved problems, and research uncertainties within ASD.

The purpose of this document is to maintain realistic expectations and clarify the experimental nature of the project.

---

## Conceptual Status

ASD is currently a conceptual and research-oriented architecture.

Most mechanisms described in this repository remain:
- theoretical
- partially modeled
- experimentally unresolved
- not production validated

The architecture should not be interpreted as a finished defensive platform.

---

## Observer Reconstruction Uncertainty

Observer-state reconstruction is inherently uncertain.

ASD can only estimate:
- observer intent
- confidence
- assumptions
- interpretation state
- suspicion level

Complete observer cognition reconstruction is not possible.

---

## Projection Drift Risk

ProjectionWorld may degrade over time through:
- semantic inconsistency
- uncontrolled adaptation
- artifact accumulation
- pacing failures
- observer-model mismatch

Projection Drift remains one of the primary unresolved architectural risks.

---

## AI Reliability Constraints

AI systems may:
- hallucinate
- generate incoherent outputs
- overfit to context
- create unstable semantic structures
- violate pacing expectations

ASD therefore requires deterministic safety enforcement outside the AI layer.

AI alone is not considered a trusted security boundary.

---

## Scalability Uncertainty

Long-term ProjectionWorld maintenance may become increasingly difficult as:
- interaction depth increases
- artifact history expands
- observer complexity grows
- semantic continuity requirements accumulate

Scalable projection consistency remains unresolved.

---

## Suspicion Modeling Limitations

Human suspicion and interpretation are difficult to model reliably.

Different observers may:
- tolerate inconsistency differently
- interpret ambiguity differently
- escalate at different speeds
- form radically different hypotheses

ASD cannot assume deterministic observer behavior.

---

## Realism Constraints

ProjectionWorld is not intended to achieve perfect realism.

Excessive realism may:
- increase complexity
- destabilize projection behavior
- reduce explainability
- increase adaptation fragility

ASD prioritizes semantic coherence over full environmental simulation.

---

## Defensive Scope

ASD is not intended to:
- replace traditional security controls
- function as standalone defense
- guarantee intrusion prevention
- eliminate adversarial success
- operate without human oversight

The architecture is intended as a complementary active-defense research direction.

---

## Measurement Challenges

It remains difficult to objectively measure:
- deception effectiveness
- observer uncertainty
- defensive time acquisition
- semantic plausibility
- projection quality
- suspicion accumulation

Reliable evaluation metrics remain an open research problem.

---

## Ethical And Operational Boundaries

Adaptive semantic projection systems may introduce:
- ethical concerns
- operational misuse risks
- escalation risks
- attribution ambiguity
- unintended behavioral consequences

ASD therefore emphasizes:
- bounded defensive environments
- explainability
- deterministic constraints
- human oversight
- defensive-only orientation

---

## Current Research Position

ASD currently exists as:
- a conceptual architecture
- a semantic-system research framework
- an active-defense modeling project
- an experimental observer-state architecture

The project remains exploratory and intentionally incomplete.
