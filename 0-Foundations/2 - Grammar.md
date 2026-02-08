# Grammar

Structural grammar defines how visual and spatial elements are organized, composed, and related — independent of content domain, platform, or interface.

Design is constructed from a limited set of primitives. All compositions must be reducible to these primitives. No decorative or stylistic element may exist outside this grammar.

---

## Primitives

### Field

The spatial context in which information exists. A field defines boundaries, orientation, and scale. It is the containing structure within which all other elements operate.

A field may be bounded (a card, a panel, a screen) or unbounded (an infinite canvas, a scrollable surface). Fields may contain other fields, establishing nested contexts.

Fields define **reference frames** — the coordinate systems and proportional logic that govern how elements within them are positioned and scaled.

### Block

A bounded unit of meaning. A block is the atomic container of content — it cannot be subdivided without loss of semantic coherence.

Blocks encode **completeness** — they represent the smallest meaningful unit of information. A block may contain text, image, data, or a combination, but it must function as a unified conceptual element.

Blocks have edges. Edges define where meaning begins and ends. Ambiguous or bleeding edges indicate structural failure.

### Axis

The directional logic governing flow and alignment. An axis defines the primary reading path, the gravitational pull of alignment, and the ordering of attention.

**Primary axis** determines reading direction (typically horizontal, left-to-right or right-to-left, or vertical, top-to-bottom).

**Secondary axis** determines perpendicular organization (typically used for hierarchy, layering, or grouping).

Axes must remain consistent within a field. Arbitrary shifts in axial logic introduce cognitive disorientation.

### Interval

The controlled absence between elements. Interval is not "white space" — it is **active structural separation** that encodes relationships.

Intervals signal:

- **Belonging** (small intervals between related elements)
- **Distinction** (larger intervals between semantically separate elements)
- **Hierarchy** (proportional intervals that encode relative importance)

Intervals must be proportional and consistent. Random or arbitrary spacing introduces noise. If two elements share the same interval as two unrelated elements, the grammar has failed.

Interval is **not** decoration. It is relational encoding.

### Hierarchy

The relational ordering of emphasis. Hierarchy governs what is seen first, what is seen second, and what recedes into secondary awareness.

Hierarchy is encoded through:

- **Scale** (size differentiation)
- **Position** (spatial priority — top, center, leading edge)
- **Weight** (visual mass — bold vs. light, dense vs. sparse)
- **Isolation** (surrounded by interval, separated from competing elements)

**No visual dominance may exist without epistemic justification.** If an element appears primary, it must **be** primary in semantic terms. Visual hierarchy and informational hierarchy must correspond exactly.

If structure depends on color, decoration, or styling to establish hierarchy, the design is invalid.

---

## Combination Rules

Primitives do not exist in isolation. They combine according to structural logic, not aesthetic preference. The following rules govern how primitives interact:

### Field Nesting

Fields may contain other fields, establishing recursive contexts. Nested fields inherit the axial and proportional logic of their parent unless explicitly overridden.

**Rule:** A nested field must remain structurally coherent when extracted from its parent. If a nested field collapses when isolated, it is not a valid field — it is a styling artifact.

### Block Arrangement

Blocks are arranged along axes within fields. Arrangement follows one of three patterns:

1. **Linear sequence** — blocks aligned along a single axis (list, timeline, narrative flow).
2. **Grid** — blocks arranged along orthogonal axes (table, matrix, gallery).
3. **Radial** — blocks distributed around a central anchor (rare; used only when semantic relationships are non-linear).

**Rule:** Block arrangement must encode semantic relationships. If blocks are visually grouped but semantically unrelated, the arrangement is invalid. If blocks are semantically related but visually separated, the arrangement is invalid.

### Interval Proportions

Intervals scale according to semantic distance. Related elements have smaller intervals; unrelated elements have larger intervals.

**Rule:** Interval must be proportionally consistent within a field. If Interval A separates related elements and Interval B separates unrelated elements, then B > A across all instances. Random variation in interval breaks structural encoding.

**Rule:** Intervals must scale proportionally with content density. High-density fields (data tables, code) require tighter intervals. Low-density fields (prose, narrative) require looser intervals. Absolute spacing values are prohibited; all intervals must be proportional to field scale and content density.

### Hierarchical Conflict Resolution

When two elements compete for hierarchical dominance, the system must resolve priority through structural rules, not designer discretion.

**Primary hierarchy** (content structure — title > section > paragraph) takes precedence over **secondary hierarchy** (interaction affordances, metadata, navigation).

**Rule:** If a navigation element appears visually dominant over the primary content heading, the hierarchy is inverted and must be corrected. Content hierarchy governs; interface hierarchy supports.

**Rule:** Only one element per field may occupy the highest hierarchical level. If two elements compete for primary dominance, the design must restructure to eliminate ambiguity.

### Axis Consistency

All elements within a field must align to a consistent axial grid. Arbitrary deviations from the axis introduce noise.

**Rule:** If an element does not align to the primary or secondary axis, it must justify its misalignment through epistemic necessity (e.g., a marginal annotation that semantically exists outside the main flow). Decorative misalignment is prohibited.

**Rule:** Axis shifts must be explicit, not gradual. If the reading direction changes, the transition must be structurally encoded (e.g., a clear boundary, a shift in field context). Subtle or ambiguous axis changes create cognitive friction.

---

## Validity Constraints

A composition is **valid** if:

1. **It reduces to primitives.** Every element can be classified as Field, Block, Axis, Interval, or Hierarchy. No unclassifiable elements exist.
2. **It functions in wireframe.** Structure remains legible when reduced to grayscale boxes and lines. If structure collapses without styling, it is invalid.
3. **Hierarchy corresponds to meaning.** Visual emphasis matches epistemic importance. No decorative dominance exists.
4. **Intervals encode relationships.** Spacing is proportional, consistent, and semantically justified.
5. **Axes remain coherent.** Reading paths and alignment logic are predictable and structurally necessary.

A composition is **invalid** if:

1. **Structure depends on styling.** If removing color, typography, or decoration breaks comprehension, the grammar has failed.
2. **Hierarchy is arbitrary.** If visual dominance does not correspond to semantic importance, equivalence is violated.
3. **Intervals are inconsistent.** If spacing is random, relationships are obscured.
4. **Blocks are unbounded.** If content bleeds ambiguously into surrounding space, boundaries have failed.
5. **Axes shift without justification.** If alignment changes arbitrarily, cognitive continuity is broken.

---

## Operational Rules

1. **All design reduces to primitives.** Field, Block, Axis, Interval, Hierarchy. Nothing else.
2. **Structure precedes style.** Compositions must function in wireframe before refinement.
3. **Hierarchy is semantic, not aesthetic.** Visual emphasis encodes meaning, not preference.
4. **Intervals are proportional and consistent.** Spacing encodes relationships structurally.
5. **Axes remain stable.** Alignment logic is predictable and necessary.

---

Grammar is not constraint for constraint's sake. It is the minimal structural language required to encode meaning spatially. A correct grammar enables infinite variation within rigorous bounds. A failed grammar produces surface-level novelty without structural coherence.

Structure is not reduction. Structure is precision.