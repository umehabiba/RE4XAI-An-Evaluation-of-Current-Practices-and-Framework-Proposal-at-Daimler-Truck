# RE4XAI-An-Evaluation-of-Current-Practices-and-Framework-Proposal-at-Daimler-Truck
[README.md](https://github.com/user-attachments/files/29202902/README.md)
# Supplementary Materials: Design for Explainable AI-Based Systems

> **A Case Study on Requirements Engineering Practices at Daimler Truck**  
> Umm-e-Habiba, Jonas Fritzsch, Lucas Mauser, Justus Bogner, and Stefan Wagner

---

## About This Repository

This repository contains the **supplementary materials** for our empirical study on Requirements Engineering (RE) practices for Explainable AI (XAI) systems, conducted in collaboration with **Daimler Truck AG**.

The study investigates how well existing RE practices handle explainability requirements in AI-based systems, identifies the resulting gaps and challenges, and proposes a holistic three-phase framework to support practitioners throughout the elicitation, specification, and validation of explainability requirements.

---

## Research Questions

| RQ | Question |
|----|----------|
| **RQ1** | How well do existing RE practices support the handling of explainability requirements in AI-based systems? |
| **RQ1.1** | How do current elicitation practices perform in capturing explainability requirements? |
| **RQ1.2** | How do existing specification practices influence the precision and ambiguity of explainability requirements? |
| **RQ1.3** | To what extent do existing validation practices ensure alignment with stakeholder expectations and regulatory obligations? |
| **RQ2** | How can the key challenges identified in RQ1 be addressed by a comprehensive framework? |
| **RQ3** | How effective is the proposed framework in supporting practitioners in industrial settings? |

---

## Study Design

The study follows a **three-phase mixed-methods design**:

```
Phase 1: Think-Aloud Protocol       Phase 2: Data Analysis &        Phase 3: Framework Evaluation
(Existing RE Practices)             Framework Design                (Focus Group + Questionnaire)
        │                                    │                                  │
 ┌──────┴──────┐               Qualitative coding (κ = 0.80)       ┌───────────┴───────────┐
 │ Elicitation │               Constant comparison method          │ Focus Group  (N = 8)  │
 │Specification│                                                   │ Questionnaire (N = 7) │
 │ Validation  │                                                   │ TAM: PU + PEOU        │
 └─────────────┘                                                   └───────────────────────┘
 Scenario: ASGA                                                    Scenario: ADDW
```

**Participants:** 8 practitioners from Daimler Truck — development engineers, product engineers, safety engineers, and researchers — with diverse RE and AI experience levels.

### RE Practices Assessed

| RE Step | Techniques |
|---------|-----------|
| **Elicitation** | Semi-Structured Interviews · Brainstorming · Task Analysis |
| **Specification** | Structured Natural Language (SNL) · Use-Case Diagrams · Softgoal Interdependency Graphs (SIG) |
| **Validation** | Structured User Feedback · Walkthroughs · Compliance Checking |

---

## Repository Contents

```
.
└── User Evaluation Study/
    │
    ├── Study Guide (2).docx                          # Session schedule and think-aloud protocol
    ├── 250401_Use-Case-Description-1.docx            # Phase 1 scenario — Active Sideguard Assist (ASGA)
    ├── Participant Demographics Sheet (1).docx       # Demographics collection template
    ├── Comprehensive Practice Guide for RE.docx      # Instructions and examples for all 9 RE practices
    ├── Presentation_final_02_04.pptx                 # Study introduction slides
    │
    ├── Session 2 Material and survey/
    │   ├── 250714_Use-Case-Description_Session-2.docx    # Phase 3 scenario — ADDW / Driver Monitoring System
    │   ├── Focus Group Session Guide.docx                # Focus group procedure and session plan
    │   ├── A framework for Managing Explainability        # Framework evaluation document (PDF)
    │   │   Requirements in AI-Based System_Evaluation.pdf
    │   ├── ERF_evaluation_summary.xlsx                   # TAM questionnaire results summary
    │   └── User Evaluation study Documents_clean.xlsx    # Full anonymized survey data
    │
    └── Think-aloud transcribe/
        │
        │  ── Phase 1: Elicitation ──
        ├── Interview (Phase 1).docx
        ├── Brain stroming RE4XAI-Study Phase-1 Lucas.docx
        ├── Task Analysis.txt
        │
        │  ── Phase 2: Specification ──
        ├── SNL RE4XAI-Study Phase-2 Lucas.docx
        ├── Use Case Modelling (Phase 2).docx
        ├── SIG.docx
        │
        │  ── Phase 3: Validation ──
        ├── Structured User Feedback (Phase 3).docx
        ├── 250402 RE4XAI-Study Phase-3 Lucas.docx   # Walkthroughs transcript
        └── compliance checking.docx
```

---

## Proposed Framework

The framework supports the full RE lifecycle for explainability requirements across three stages:

1. **Elicitation Stage** — Establishes a shared explainability vocabulary, maps stakeholders to explanation needs, and structures planning around *who*, *what*, and *why* explanations are required.
2. **Specification Stage** — Characterizes explanation format, timing, intended audience, and measurability; produces testable acceptance criteria aligned with regulatory obligations.
3. **Validation Stage** — Verifies completeness, stakeholder alignment, traceability, and regulatory compliance (EU AI Act, GDPR).

A **spreadsheet-based application template** (three tabs, one per stage) was used by participants during the focus group and is included in this repository as `ERF_evaluation_summary.xlsx` / `User Evaluation study Documents_clean.xlsx`.

---

## Framework Evaluation Results

Survey conducted with N = 7 practitioners using the Technology Acceptance Model (TAM), 7-point Likert scale:

| Construct | Mean | Median | SD | Cronbach's α |
|-----------|------|--------|----|-------------|
| Perceived Usefulness (PU) | 6.43 | 6.40 | 0.41 | 0.603 |
| Perceived Ease of Use (PEOU) | 5.69 | 5.80 | 0.91 | 0.751 |

PU–PEOU correlation: r = 0.714 (p = 0.047), consistent with TAM theory.

---

## Scenarios Used in the Study

| Study Phase | Scenario | Regulatory Mandate |
|-------------|----------|--------------------|
| Phase 1 (think-aloud) | Active Sideguard Assist (ASGA) | UN Regulation No. 151 / GSR 2019/2144 |
| Phase 3 (focus group) | Advanced Driver Distraction Warning (ADDW) | GSR 2019/2144 / GSR 2023/2590 |

---

## Ethical and Privacy Notes

- All participant data is anonymized (Participant IDs P1–P8 only).
- Complete transcripts are not published; only relevant excerpts are quoted in the paper with explicit participant approval.
- Study data was collected and stored in compliance with institutional research ethics guidelines.

---

## Authors

| Name | Affiliation |
|------|-------------|
| **Umm-e-Habiba** | Technical University Munich |
| **Jonas Fritzsch** | University of Stuttgart |
| **Lucas Mauser** | Daimler Truck AG / TU Munich |
| **Justus Bogner** | Vrije Universiteit Amsterdam |
| **Stefan Wagner** | University of Stuttgart |

---

## How to Cite

A BibTeX entry will be added upon publication. In the meantime, please refer to the paper title and authors listed above.
