# Dynamics

Dynamics defines how design changes across time, interaction, and transformation. Motion is not decoration — it is structural revelation. Animation exists to encode causality, preserve continuity, and reduce cognitive friction during state transitions.

Design must evolve without spectacle. Every transition must justify itself through epistemic necessity: does this motion clarify structure, reveal relationship, or reduce interpretive load? If not, it is removed.

## Temporal Hierarchy

[IMAGE 29: Motion sequence diagram showing hierarchical animation - primary elements (structural anchors) moving last while secondary elements (content) move first, with causal dependencies illustrated]

Not all elements move at the same rate. Temporal hierarchy governs **what moves first, what follows, and what remains static** during a transition.

**Primary elements** (structural anchors, navigation, persistent context) move last or remain fixed. They provide orientation during change.

**Secondary elements** (content, detail, transient states) move first. They signal that transformation is occurring without destabilizing the user's spatial model.

**Causal dependencies** determine sequence. If Element `B` depends on Element `A`, `A` must complete its transition before `B` begins. Motion must encode logical ordering, not aesthetic preference.

Simultaneous motion is permitted only when elements share equivalent semantic weight and the transition involves no causal dependency. Otherwise, motion must sequence hierarchically.

---

## Causal Encoding

[IMAGE 30: Causality visualization showing expansion from point of selection, deletion with surrounding elements filling space, and filter application with visible state transition - contrasted with discontinuous jumps]

Motion must make causality visible. When a user acts, the system's response must structurally demonstrate **why** the change occurred, not merely **that** it occurred.

- If selection causes expansion, the expansion must originate from the point of selection.
- If deletion removes an element, surrounding elements must move to occupy the absence — not snap instantly into new positions.
- If a filter is applied, content must visibly transition between states rather than replace itself without continuity.

**Motion as explanation:** Animation should function as a visual proof. The path an element takes during transformation encodes the relationship between initial and final states. Discontinuous jumps imply no relationship; smooth transitions imply structural continuity.

**No unmotivated transitions.** If there is no causal relationship between states, there should be no animated transition. Immediate replacement is preferable to false continuity.

---

## Transition Invariance

Transitions must preserve **identity, hierarchy, and orientation** across transformation. No motion may introduce cognitive discontinuity or spatial disorientation.

**Identity preservation:** An element must remain recognizable as _the same element_ throughout its transition. Shape, proportion, and internal structure may transform, but the user must be able to track continuity. If an element cannot be tracked visually, the transition has failed.

[IMAGE 31: Element transformation sequence showing continuous identity tracking - the same element remaining recognizable throughout its transition versus loss of identity/trackability]

**Hierarchical consistency:** Relative importance must remain stable during motion. A primary element must not temporarily appear subordinate to a secondary element due to animation timing or path.

**Spatial coherence:** Users must maintain their sense of location during transitions. If a view changes, the transformation must encode the spatial relationship between old and new states. Fades, dissolves, and cuts obscure spatial relationships and should be avoided except when no spatial relationship exists.

[IMAGE 32: Spatial relationship encoding in transitions - showing transformation that encodes spatial relationship between old and new states versus fades/cuts that obscure relationships]

**Scale invariance:** Transitions must function correctly across device scales, interaction speeds, and accessibility settings. A transition that requires 400ms to be comprehensible is a failed transition. Motion must encode structure clearly even when reduced, slowed, or disabled.

---

## Cognitive Continuity

[IMAGE 33: Motion duration and predictability examples - showing structurally inevitable motion paths versus arbitrary/decorative effects, with appropriate durations (150-300ms) indicated]

Motion exists to **reduce interpretive load**, not to add aesthetic interest. Every animation must decrease the effort required to understand state change.

**Predictable motion:** Paths, durations, and easing must follow physical or logical consistency. Arbitrary curves, bounces, or elastic effects introduce cognitive noise. Motion should feel structurally inevitable, not stylistically chosen.

**Interruptible transitions:** Users must be able to interrupt motion without breaking the system. If a transition cannot be interrupted safely, it should not exist. Motion must never hold cognition hostage.

**No decorative delays.** If a transition takes longer than necessary to encode causality, it is ornamental. Duration must be the minimum required for comprehension — typically 150–300ms. Longer durations are permitted only when spatial complexity demands additional processing time.

**Reduced motion compatibility:** All transitions must degrade gracefully to instantaneous state changes. Users who disable motion must lose no semantic information. If meaning depends on animation, the design has violated equivalence.

---

## Operational Rules

1. **Motion encodes structure, not style.** If animation does not clarify causality or preserve continuity, it is removed.
2. **Transitions sequence hierarchically.** Dependent elements move only after their dependencies complete.
3. **No element may lose identity during transformation.** Continuity must be visually trackable.
4. **Duration is minimized.** Motion takes only as long as cognition requires.
5. **All motion must function when disabled.** Meaning persists in the absence of animation.

---

Dynamics enhance cognition by making structure visible across time. A correct transition reduces effort, preserves orientation, and encodes causality. A failed transition disorients, delays, or decorates.

Motion is epistemic. Animation is proof.