# A Mathematical Model to quantify  interpersonal relationships between humans.

### **Abstract:**

Human relationships, though inherently emotional and subjective, follow patterns that can be conceptually modeled using a quantitative approach. This paper introduces a novel mathematical framework for representing the strength of interpersonal bonds across a spectrum of relationship types. By combining emotional, behavioral, temporal, and subjective components into a unified equation, the model aims to provide a lens for evaluating and predicting the evolution of human connections over time. Applications range from psychological analysis to AI-human interaction systems.

### 1. Introduction

Human relationships are complex, multifaceted constructs governed by a combination of emotional depth, time investment, shared history, and countless intangible experiences. While traditionally studied qualitatively through psychology and sociology, the advent of AI and computational psychology opens the door for quantitative modeling.

This paper proposes a formal model for measuring "Bond Strength" as a function of various emotional, behavioral, and contextual parameters. The model is relationship-agnostic, meaning it applies to friendships, romantic relationships, family ties, and professional associations.

---

### 2. Model Overview

We define the bond strength between two individuals over time, denoted as B(t) , as follows:

$$
B(t) = (\alpha \cdot E(t)) + (\beta \cdot Ef(t)) + (\gamma \cdot R(t)) + (\delta \cdot S(t)) + (\epsilon \cdot A(t)) + M(t)
$$

Where:

- $E(t)$  = Emotional Investment
- $Ef(t)$ = Effort
- $R(t)$  = Reciprocity
- $S(t)$  = Shared Experiences
- $A(t)$ = Age of Relationship (Time known)
- $\alpha \;to\; \epsilon \;$ = weights of coefficients.
- $M$ = Subjective Modifier, a cumulative score of qualitative factors

---

Human behavior cannot be fully captured by quantifiable actions alone. The modifier  $M(t)$ includes positive and negative subjective experiences:

$$
M = \sum_{i=1}^{n} s_i -\sum_{i=1}^{n} d_i
$$

Where:

- $s_i$ : Positive subjective events (e.g., trust, mutual growth, vulnerability)
- $d_i$ : Negative subjective events (e.g., jealousy, disrespect, conflict)

Each event can be weighted (e.g., +3 for deep trust, -2 for minor fights), allowing the modifier to reflect the qualitative texture of the relationship.

### 4. Relationship Archetypes

Different types of relationships emphasize different components. For instance:

| Relationship Type | E | Ef | R | S | A | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Romantic | High | High | High | High | Medium | Intensity & effort focused |
| Friendship | Medium | Medium | High | High | Medium | Mutuality key |
| Family | Medium | Low | Low | High | High | Inertia and history weighted |
| Mentorship | Low | High | Medium | Medium | Low | Growth-focused |
| Acquaintance | Low | Low | Low | Low | Low | Minimal interaction |

### 5. Rate of Change and Dynamics

Relationships are not static. To capture their dynamic nature:

$$

\frac{dB}{dt} = \alpha \cdot \frac{dE}{dt} + \beta \cdot \frac{dEf}{dt} + \gamma \cdot \frac{dR}{dt} + \delta \cdot \frac{dS}{dt} + \epsilon \cdot  \frac{dM}{dt}
$$

This differential form reflects whether a relationship is strengthening or deteriorating, helping identify turning points or intervention needs (e.g., therapy, communication, reconnection).

---

### 6. Applications

**1. AI and Social Robotics:** Inform machine understanding of human emotions and social contexts.

**2. Relationship Counseling:** Quantify and visualize relationship health.

**3. Mental Health:** Detect isolation or emotional imbalance via low bond scores.

**4. Social Media:** Enhance friend/recommendation algorithms using deeper metrics.

**5. Simulation Models:** Model societies, teams, or networks in agent-based systems.

---

### 7. Limitations and Ethical Considerations

- Human relationships are partially irrational and nonlinear.
- Quantifying emotions may oversimplify individual experiences.
- Ethical use of this model in AI systems requires informed consent, privacy preservation, and transparency.

---

### 8. Future Work

- Extend the model using neural-symbolic AI systems.
- Build a dynamic graph visualization for real-time bond mapping.
- Validate the model through surveys and psychological studies.
- Adapt to cultural contexts.

---

### 9. Conclusion

This model provides a flexible, extensible structure for understanding the anatomy of human connection. Though inherently imperfect, it serves as a bridge between the emotional complexity of human experience and the logical structure of computational systems. As AI continues to mediate our social lives, tools that preserve emotional nuance will become increasingly vital.