# Alliance Theory and Campus Free Speech from Self-Censorship and Protest Tolerance Among College Students 

This repository contains materials for the analysis "Alliance Theory and Campus Free Speech from Self-Censorship and Protest Tolerance Among College Students" by David G. Kamper, examining evolving patterns of campus expression through the lens of alliance theory across two critical years in higher education.

## Introduction

The state of free speech on college campuses has become a defining issue in contemporary higher education, with debates centering on self-censorship, speaker disruptions, and the tolerance of diverse viewpoints. Traditional approaches to understanding campus expression conflicts have largely focused on abstract principles such as academic freedom, tolerance, and democratic values. However, these frameworks struggle to explain both the systematic patterns of selective tolerance observed across the political spectrum and the dramatic temporal shifts in which groups experience expression constraints.

This research applies alliance theory—as developed by Pinsof, Sears, and Haselton (2023)—to campus free speech dynamics, arguing that political expression patterns are fundamentally shaped by group allegiances rather than consistent principled commitments to free speech values. Alliance theory predicts that individuals will systematically favor allies and oppose rivals across different domains, leading to what appears as principled inconsistency but actually reflects strategic coalition maintenance.

Using comprehensive survey data from 342,179 college students collected by the Foundation for Individual Rights in Education (FIRE) across 2025 (58,807 students) and 2026 (284,372 students), this analysis examines several key research questions through temporal comparison to understand how campus speech climates evolve and transform.

## Research Questions

### Primary Research Questions

1. **Self-Censorship and Protest Tolerance Dynamics:** How do different contexts of self-censorship relate to tolerance for various protest tactics, and how have these relationships evolved between 2025 and 2026?

2. **Alliance-Based Preferences Over Time:** Do students demonstrate systematic biases favoring speakers and causes aligned with their political coalitions while opposing those associated with rival groups, and do these patterns remain stable across changing campus climates?

3. **Political Identity Effects and Temporal Shifts:** To what extent does political ideology predict both self-censorship behaviors and tolerance for censorious tactics by others, and how have ideological patterns shifted between the two survey years?

4. **Institutional Climate Influences:** How do administrative policies and institutional clarity regarding free speech affect student expression behaviors, and what factors predict positive versus negative campus speech climates?

### Secondary Research Questions

5. **Mental Health and Expression:** How do psychological wellbeing indicators relate to campus speech behaviors, and have these relationships evolved between 2025 and 2026?

6. **Group-Based Resource Allocation:** Do campus funding preferences reflect in-group favoritism consistent with alliance theory predictions across both survey years?

7. **Topic-Specific Conversation Patterns:** Which specific political topics create the greatest conversation difficulty on campus, and how do these patterns vary by political identity?

## Theoretical Framework

This analysis is grounded in alliance theory as articulated in Pinsof, Sears, and Haselton's (2023) "Strange Bedfellows: The Alliance Theory of Political Belief Systems." Alliance theory argues that political belief systems derive primarily from group allegiances rather than abstract moral principles, with individuals supporting policies and positions that benefit their political allies while opposing those that advantage rival coalitions. This framework predicts systematic inconsistencies in apparent principled positions, as moral principles are applied flexibly depending on whether they benefit allies or rivals.

The longitudinal design allows for testing whether alliance-based patterns represent stable features of political psychology or contextually dependent responses to changing campus environments.

## Repository Structure

```
.
├── README.md
├── Code
│   └── R
├── Data
│   ├── 2025
│   └── 2026
└── Documents
```

### Code

#### R

`FireAnalysis_Final2025.Rmd` and `FireAnalysis_Final2026.Rmd` are the primary analysis files containing comprehensive analyses and visualizations for all aspects of the study, including:

- Individual question correlations between self-censorship and protest tolerance across both years
- Political ideology analysis revealing the dramatic reversal in ideological self-censorship patterns
- Alliance theory validation through group-based preference patterns with enhanced 2026 measures
- Mental health correlate analyses showing evolving psychological relationships
- Religious, socioeconomic, and demographic factors in campus expression
- Geographic and institutional effects with expanded institutional climate measures
- Cohort and generational patterns across the two-year period
- Topic-specific conversation difficulty analysis across 29 political issues

### Data

Contains the processed FIRE campus speech survey data with 58,807 student responses in 2025 and 284,372 responses in 2026, spanning multiple states and institutions.

### Documents

Contains supplementary materials including:
- The Alliance Theory theoretical framework (Pinsof, Sears, & Haselton, 2023)
- Enhanced longitudinal results and discussion sections
- Additional methodological documentation
- Comparison analysis documentation

### Paper Results

All results are analyzed and visualized in `Code/R/FireAnalysis_Final2025.Rmd` and `Code/R/FireAnalysis_Final2026.Rmd`. All findings are included in the documents. The knitted documents can be viewed at [`Code/R/FireAnalysis_Final2025.html`](https://dgkamper.github.io/FIREAnalysisAllianceCensor/Code/R/FireAnalysis_Final2025.html) and [`Code/R/FireAnalysis_Final2026.html`](https://dgkamper.github.io/FIREAnalysisAllianceCensor/Code/R/FireAnalysis_Final2026.html).

## Key Findings

### Core Relationship Evolution

The longitudinal analysis revealed both stability and dramatic transformation in campus speech dynamics between 2025 and 2026.

**Self-Censorship and Protest Tolerance Correlations:** Positive correlations between general self-censorship and tolerance for protest tactics strengthened from 2025 to 2026. General self-censorship correlations with shouting down speakers increased from r = 0.033 to r = 0.070, while blocking correlations remained stable (r = 0.028 to r = 0.030). The introduction of comfort expressing views measures in 2026 revealed systematically negative correlations with protest tolerance (r = -0.085 to -0.120), clarifying the theoretical distinction between self-censorship and expression confidence.

**The Great Ideological Reversal:** The most significant finding involves a complete reversal in which political groups report higher self-censorship. In 2025, conservative students reported lower self-censorship levels (very conservative: M = 2.97) while liberal students reported higher levels (M = 3.11). By 2026, this pattern completely reversed, with conservative students reporting substantially higher self-censorship (M = 3.08) and liberal students demonstrating the lowest levels (M = 2.34), representing a 32% difference between ideological extremes.

### Alliance Theory Validation Across Time

**Systematic Alliance-Based Preferences:** Both years demonstrated strong empirical support for alliance theory predictions, with students showing systematic tolerance gaps favoring politically aligned speakers while opposing rivals. The 2026 analysis expanded validation through examination of 21 speaker types, revealing tolerance ranging from 1.48 for racial superiority advocates to 3.03 for immigration speakers.

**Stable Group Funding Patterns:** Alliance-based group funding preferences remained consistent across both years. Liberal students demonstrated higher support for Black Lives Matter funding (31.4% in 2026) compared to conservative students (13.4%), while religious group funding showed cross-cutting patterns (liberal: 27.5%; conservative: 24.0% for Christian groups), confirming alliance theory predictions about multiple group identities.

**Issue-Specific Alliance Patterns:** The 2026 analysis revealed systematic ideological differences in conversation difficulty across 29 topics. Abortion emerged as the most difficult topic overall (45.8% reporting difficulty), with conservative students reporting greater difficulty (58.0-58.2%) than liberal students (38.3%). Israel/Palestine discussions showed inverse patterns (liberal difficulty: 50.8%; conservative: 30.8%).

### Mental Health and Expression: Evolving Relationships

The relationship between mental health and campus speech behaviors underwent fundamental transformation between survey years. The 2025 analysis found counterintuitive negative correlations between stress and self-censorship (r = -0.037 to -0.048), suggesting that psychological distress might reduce behavioral inhibition. The 2026 analysis revealed a complete reversal with strong positive correlations (stress-self-censorship: r = 0.160), aligning with theoretical expectations.

Loneliness emerged as the strongest mental health predictor of self-censorship in 2026 (r = 0.182), suggesting that social isolation drives political expression withdrawal. This relationship was negligible in 2025 (|r| < 0.02), indicating substantial evolution in psychological mechanisms underlying campus expression.

### Institutional Climate Effects

The 2026 analysis introduced systematic examination of institutional factors absent from 2025, revealing crucial insights into structural influences on campus speech. Administrative clarity regarding free speech policies demonstrated strong negative correlations with self-censorship (r = -0.254), indicating that procedural transparency significantly reduces student expression restraint. Administrative defense of speakers showed weaker but similar relationships (r = -0.168), suggesting that clarity matters more than perceived partisan support.

### Protest Tolerance Stability

Unlike self-censorship patterns, protest tolerance demonstrated remarkable consistency across both years. Liberal students consistently showed lower tolerance for disruptive tactics compared to conservatives, indicating that protest tolerance may reflect stable ideological commitments that remain constant despite changing campus climates.

## Implications

### Theoretical Implications

**Alliance Theory Validation:** The longitudinal analysis provides robust validation of alliance theory while revealing that campus expression conflicts represent standard political competition rather than principled disagreements about free speech values. The stability of alliance-based tolerance patterns across dramatically different campus climates confirms that group loyalty drives expression attitudes more than abstract principles.

**The Contextual Nature of Campus Speech:** The complete reversal in ideological self-censorship patterns demonstrates that campus speech climates are highly contextual and can undergo fundamental transformation. This finding challenges static conceptions of campus political environments and suggests that expression experiences are shaped by broader political dynamics rather than fixed institutional characteristics.

### Policy and Intervention Implications

**Administrative Response:** The strong relationship between administrative clarity and reduced self-censorship provides empirical support for practical interventions focusing on procedural transparency rather than ideological positioning. Institutions can implement clear communication policies about expression guidelines without requiring administrators to navigate complex political disputes.

**Targeted Support:** The ideological reversal in self-censorship suggests that campus climate interventions should be designed to address the differential experiences of conservative and liberal students across different time periods rather than assuming static patterns. Support programs may need periodic recalibration based on evolving campus political dynamics.

**Mental Health Integration:** The evolving relationships between psychological wellbeing and expression behaviors indicate that campus speech climate initiatives should incorporate mental health considerations, particularly addressing social isolation as a driver of expression withdrawal.

### Democratic Theory Implications

**Fragility of Democratic Norms:** The evidence that expression tolerance is primarily driven by political allegiance rather than principled commitment, combined with dramatic temporal shifts in expression patterns, suggests that democratic discourse norms may be more fragile and contextually dependent than commonly assumed.

**Coalition Competition Framework:** Understanding campus free speech through an alliance theory lens reveals that debates about expression rights, speaker policies, and campus climate represent manifestations of broader political coalition competition rather than isolated disputes about academic freedom.

## Software Versions

Analysis was performed in R version 4.2.2.

R package versions are indicated in the knitted analysis files at `Code/R/FireAnalysis_Final2025.html` and `Code/R/FireAnalysis_Final2026.html`.

## CRediT Author Statement

| Term                       | David G. Kamper |
|----------------------------|-----------------|
| Conceptualization          | X               |
| Methodology                | X               |
| Software                   | X               |
| Validation                 | X               |
| Formal analysis            | X               |
| Investigation              | X               |
| Resources                  | X               |
| Data Curation              | X               |
| Writing - Original Draft   | X               |
| Writing - Review & Editing | X               |
| Visualization              | X               |
| Supervision                | X               |
| Project administration     | X               |
| Funding acquisition        | NA              |

## Citation

If you use this analysis or data in your research, please cite:

Kamper, D. G. (2025). Alliance Theory and Campus Free Speech: A Longitudinal Analysis of Self-Censorship and Protest Tolerance Among College Students (2025-2026). *[Journal/Conference TBD]*.

## References

Pinsof, D., Sears, D. O., & Haselton, M. G. (2023). Strange bedfellows: The alliance theory of political belief systems. *Psychological Inquiry*, 34(3), 139-160.

Foundation for Individual Rights in Education. (2024). Campus Speech Survey Data. Retrieved from [https://www.thefire.org/]

## Contact

For questions about this analysis or requests for additional information, please contact David G. Kamper at [davidgkamper@ucla.edu].

## License

This project is licensed under the MIT License - see the LICENSE file for details.
