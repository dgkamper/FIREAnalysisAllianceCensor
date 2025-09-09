# Alliance Theory and Campus Free Speech looking at Self-Censorship and Protest Tolerance Among College Students

This repository contains materials for the analysis "Alliance Theory and Campus Free Speech: An Empirical Analysis of Self-Censorship and Protest Tolerance Among College Students" by David G. Kamper, examining patterns of campus expression through the lens of alliance theory.

## Introduction

The state of free speech on college campuses has become a defining issue in contemporary higher education, with debates centering on self-censorship, speaker disruptions, and the tolerance of diverse viewpoints. Traditional approaches to understanding campus expression conflicts have largely focused on abstract principles such as academic freedom, tolerance, and democratic values. However, these frameworks struggle to explain the systematic patterns of selective tolerance observed across the political spectrum, where students consistently support expression rights for ideologically aligned speakers while opposing those from rival political coalitions.

This research applies alliance theory—as developed by Pinsof, Sears, and Haselton (2023)—to campus free speech dynamics, arguing that political expression patterns are fundamentally shaped by group allegiances rather than consistent principled commitments to free speech values. Alliance theory predicts that individuals will systematically favor allies and oppose rivals across different domains, leading to what appears as principled inconsistency but actually reflects strategic coalition maintenance.

Using comprehensive survey data from 58,807 college students collected by the Foundation for Individual Rights in Education (FIRE), this analysis examines several key research questions:

1. **Self-Censorship and Protest Tolerance:** How do different contexts of self-censorship relate to tolerance for various protest tactics?
2. **Alliance-Based Preferences:** Do students demonstrate systematic biases favoring speakers and causes aligned with their political coalitions while opposing those associated with rival groups?
3. **Political Identity Effects:** To what extent does political ideology predict both self-censorship behaviors and tolerance for censorious tactics by others?
4. **Group-Based Resource Allocation:** Do campus funding preferences reflect in-group favoritism consistent with alliance theory predictions?

Our findings provide strong empirical support for alliance theory, revealing that campus free speech conflicts are better understood as manifestations of political coalition competition rather than principled disagreements about expression values. The analysis demonstrates systematic tolerance gaps where both conservative and liberal students favor allies while opposing rivals, challenging narratives that frame campus free speech as a conflict between pro- and anti-free speech factions.

## Theoretical Framework

This analysis is grounded in alliance theory as articulated in Pinsof, Sears, and Haselton's (2023) "Strange Bedfellows: The Alliance Theory of Political Belief Systems." Alliance theory argues that political belief systems derive primarily from group allegiances rather than abstract moral principles, with individuals supporting policies and positions that benefit their political allies while opposing those that advantage rival coalitions. This framework predicts systematic inconsistencies in apparent principled positions, as moral principles are applied flexibly depending on whether they benefit allies or rivals.

## Repository Structure

```
.
├── README.md
├── Code
│   └── R
├── Data
└── Documents
```

### Code

#### R

`FireAnalysis_Final.Rmd` is the primary analysis file containing comprehensive analyses and visualizations for all aspects of the study, including:

- Individual question correlations between self-censorship and protest tolerance
- Political ideology analysis across all expression measures
- Alliance theory validation through group-based preference patterns
- Mental health and demographic correlate analyses
- Religious and socioeconomic factors in campus expression
- Geographic and institutional effects
- Cohort and generational patterns

### Data

Contains the processed FIRE campus speech survey data with 58,807 student responses across multiple years and institutions.

### Documents

Contains supplementary materials including:
- The Alliance Theory theoretical framework (Pinsof, Sears, & Haselton, 2023)
- Enhanced results and discussion sections
- Additional methodological documentation

### Paper Results

All results are analyzed and visualized in `Code/R/FireAnalysis_Final.Rmd`. All findings are included in the document. The knitted document can be viewed at [`Code/R/FireAnalysis_Final.html`](https://dgk-law-and-cognition-lab.github.io/FIREAnalysisAllianceandSelfCensor/Code/R/FireAnalysis_Final.html).

## Key Findings

### Core Relationships
- Small but significant positive correlations between general self-censorship and tolerance for protest tactics (r = 0.033 for shouting down, r = 0.028 for blocking, r = 0.009 for violence)
- Context-dependent patterns where self-censorship with professors showed negative correlations with more severe protest tactics
- Political ideology emerged as the strongest predictor of both self-censorship and protest tolerance patterns

### Alliance Theory Validation
- Systematic tolerance gaps favoring politically aligned speakers over rivals across the ideological spectrum
- Conservative students showed a tolerance gap of -0.294 between ally and rival speakers (p < 0.001)
- Liberal students demonstrated an even larger tolerance gap of -0.731 (p < 0.001)
- Strong correlations between support for different political causes (r > 0.7), indicating coherent alliance structures

### Institutional and Demographic Patterns
- No significant differences between public and private institutions in expression climates
- Cohort effects with declining self-censorship among newer students
- Counterintuitive negative correlation between stress and self-censorship
- Religious affiliation effects on both expression behaviors and group funding preferences

## Implications

These findings have significant implications for understanding and addressing campus free speech challenges:

1. **Policy Design:** Traditional approaches focusing on institutional culture or abstract free speech values may be insufficient if expression patterns are primarily driven by political coalition dynamics.

2. **Intervention Strategies:** Effective interventions may need to address underlying political polarization rather than treating campus expression conflicts as isolated disputes about specific speakers or events.

3. **Democratic Theory:** The evidence that expression tolerance is primarily driven by political allegiance rather than principled commitment challenges assumptions about democratic discourse and civic education.

## Software Versions

Analysis was performed in R version 4.2.2.

R package versions are indicated in the knitted analysis file at `Code/R/FireAnalysis_Final.html`.

## CRediT Author Statement

[What is a CRediT author statement?](https://www.elsevier.com/researcher/author/policies-and-guidelines/credit-author-statement)

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
| Funding acquisition        | X               |

## Citation

If you use this analysis or data in your research, please cite:

Kamper, D. G. (2025). Alliance Theory and Campus Free Speech: An Empirical Analysis of Self-Censorship and Protest Tolerance Among College Students. *[Journal/Conference TBD]*.

## References

Pinsof, D., Sears, D. O., & Haselton, M. G. (2023). Strange bedfellows: The alliance theory of political belief systems. *Psychological Inquiry*, 34(3), 139-160.

Foundation for Individual Rights in Education. (2024). Campus Speech Survey Data. Retrieved from [https://www.thefire.org/]

## Contact

For questions about this analysis or requests for additional information, please contact David G. Kamper at [email address].

## License

This project is licensed under the MIT License - see the LICENSE file for details.
