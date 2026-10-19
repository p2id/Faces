# Interface pattern scan

## 1) Research and selection

### 1.1 Research scan: dominant interface patterns

- Persistent top navigation with focused secondary navigation.
- Card-based content grouping with clear hierarchy and scannable metadata.
- Inline search and filtering combined with progressive disclosure.
- Primary action first, secondary actions compact and consistent.
- Bottom navigation on small screens for the most frequent destinations.
- Lightweight status indicators for unread, active, saved, or completed items.
- Side panels or drawers for details without losing context.

### 1.2 Research scan: emerging interface patterns

- Context-sensitive command surfaces shown only when useful.
- Personalization controls surfaced as part of core interaction.
- Density modes for fast scanning versus detailed review.
- Smart defaults that reduce effort without removing control.
- Modular detail panes that reduce full-page transitions.
- Micro-feedback for save, sync, and processing states.

### 1.3 Research scan: deprecated interface patterns

- Overcrowded dashboards with too many competing widgets.
- Hidden actions represented only by unlabeled icons.
- Modal-heavy flows for simple tasks that could be inline.
- Dense tabular layouts on small screens without adaptation.
- Decorative motion that does not support user understanding.
- Status communicated only by color without supporting text.

### 1.4 Research scan: outlier interface patterns

- Asymmetrical split layouts for highly expressive products.
- Strongly branded visual systems that prioritize identity over neutrality.
- Gesture-first surfaces with minimal visible controls.
- Dense operator-style interfaces for expert use cases.
- Narrative scroll experiences for onboarding or campaign-like journeys.

### 1.5 Extracted DNA

#### Visual DNA

- Clear hierarchy through typography, spacing, and contrast.
- Modular surfaces with restrained elevation.
- Controlled color use that supports meaning rather than decoration.
- Consistent shape language across containers, controls, and overlays.
- Balanced whitespace with compact but readable content density.

#### Interaction DNA

- Immediate feedback for user actions.
- Progressive disclosure for advanced or infrequent options.
- Inline validation instead of delayed failure.
- Clear transitions between browse, inspect, and edit modes.
- Predictable placement and treatment of destructive actions.

#### Accessibility DNA

- Keyboard-first usability.
- Visible focus states on all interactive controls.
- Semantic structure for headings, regions, lists, and forms.
- Sufficient color contrast for text and essential UI boundaries.
- Error states that are explicit, actionable, and perceivable.

#### Responsive DNA

- Mobile-first layout logic.
- Fluid grids that reflow cleanly.
- Components that stack, collapse, or condense without losing meaning.
- Navigation adapted per breakpoint.
- No horizontal scrolling for ordinary content.

### 1.6 Candidate product domains

1. **Professional identity network** — A profile-centered product for presentation, discovery, and trust-aware interaction.
2. **Local community exchange** — A neighborhood or interest-based product for participation, discovery, and coordination.
3. **Creative portfolio hub** — A space for showcasing work, context, and feedback in a polished, public-facing format.
4. **Wellness companion space** — A private-first product for habits, progress, and supportive interaction.
5. **Learning and mentorship platform** — A structured environment connecting learners, guides, and progress-based relationships.
6. **Event and invitation network** — A product for planning, attendance, reminders, and social coordination.

### 1.7 Weighted scoring matrix

#### Criteria and weights

| Criterion | Weight | Meaning |
|---|---:|---|
| Primary value clarity | 20 | Ease of understanding the core purpose |
| Interaction breadth | 15 | Range of UI patterns naturally required |
| Visual differentiation potential | 15 | Space for distinct but coherent design |
| Accessibility fit | 10 | Likelihood of inclusive implementation |
| Responsive adaptability | 10 | Compatibility with multiple device sizes |
| Content richness | 10 | Availability of realistic UI content and states |
| Longevity of system need | 10 | Whether the system benefits from sustained evolution |
| Specification usefulness | 10 | Ability to support tokens, contracts, and audits |

#### Scoring scale

- 1 = weak fit
- 2 = limited fit
- 3 = moderate fit
- 4 = strong fit
- 5 = excellent fit

#### Candidate scoring table

| Domain | Value | Breadth | Differentiation | Accessibility | Responsive | Content | Longevity | Spec utility | Total / 100 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Professional identity network | 5 | 5 | 4 | 4 | 5 | 5 | 5 | 5 | 96 |
| Local community exchange | 4 | 4 | 4 | 4 | 5 | 5 | 4 | 4 | 84 |
| Creative portfolio hub | 4 | 3 | 5 | 4 | 5 | 4 | 4 | 4 | 81 |
| Wellness companion space | 4 | 4 | 3 | 5 | 5 | 4 | 4 | 4 | 82 |
| Learning and mentorship platform | 5 | 4 | 4 | 4 | 4 | 5 | 5 | 5 | 90 |
| Event and invitation network | 4 | 4 | 3 | 4 | 5 | 4 | 4 | 4 | 80 |

### 1.8 Selected domain with rationale

#### Selected domain: Professional identity network

**Rationale**

- Naturally supports profile, discovery, messaging, notifications, settings, and trust controls.
- Requires a coherent and durable design system because identity, visibility, and interaction are tightly coupled.
- Produces realistic screens, edge states, and component contracts without unnecessary complexity.
- Supports strong accessibility, responsive behavior, and content structure.

### 1.9 Fallback rule

If the selected domain becomes unsuitable, choose the next highest-scoring domain that still supports the required surface coverage, component states, responsive adaptation, and token-driven specification without changing the document structure.

---