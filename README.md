
# CTI & OSINT Analytical Framework

### A Reusable Framework for Evidence-Led Intelligence Analysis

**Version:** 1.0  
**Status:** Under Development  
**Focus:** Cyber Threat Intelligence (CTI), Open-Source Intelligence (OSINT) and Structured Analytical Reporting

## Overview

This repository contains a reusable analytical framework for conducting structured, evidence-led Cyber Threat Intelligence (CTI) and Open-Source Intelligence (OSINT) investigations.

The framework is designed to support consistency, transparency, reproducibility and analytical integrity across independent intelligence research projects.

It combines established intelligence evaluation practices with project-specific procedures for source verification, technical analysis, evidence management and reporting.

The framework is intended to evolve through practical application and continuous methodological improvement.

## Objectives

The framework aims to:

- Establish consistent intelligence collection and analytical procedures.
- Apply structured source reliability and information credibility assessments.
- Reduce confirmation bias and unsupported analytical assumptions.
- Maintain traceability between evidence and analytical judgements.
- Support technical threat analysis using MITRE ATT&CK.
- Incorporate competing perspectives and alternative explanations.
- Apply explicit analytical confidence assessments.
- Reduce hallucination risks in AI-assisted intelligence research.
- Standardise the production of professional intelligence reports.

## Analytical Principles

### Evidence-Led Analysis

Conclusions must follow the available evidence rather than predetermined assumptions.

### Source Evaluation

The framework adopts the Admiralty Code approach, evaluating source reliability (A–F) and information credibility (1–6) separately.

### Analytical Transparency

Reported claims, observed evidence, analytical inference and unresolved questions must be clearly distinguished.

### Competing Perspectives

Materially different explanations and official positions must be considered fairly and assessed according to their supporting evidence.

### Technical Intelligence

Where applicable, investigations include incident-specific analysis of tactics, techniques and procedures (TTPs), tooling, infrastructure and MITRE ATT&CK mappings.

### Analytical Confidence

Major analytical judgements use High, Moderate or Low confidence, supported by an explanation of the available evidence and limitations.

### AI-Assisted Research

AI tools may support research, information organisation, translation, technical analysis and drafting.

Material factual claims must be verified against inspectable sources before publication. AI-generated content alone is not accepted as evidence.

## Framework Components

| Directory | Purpose |
|---|---|
| `standards/` | Analytical standards, source grading and confidence methodology |
| `templates/` | Reusable intelligence requirements, collection plans and evidence registers |
| `prompts/` | Instructions for initiating new AI-assisted intelligence projects |
| `quality-assurance/` | Evidence verification, bias review and publication checks |
| `examples/` | Worked examples demonstrating the framework |

## Standard Analytical Workflow

1. Define the intelligence question and assessment scope.
2. Establish Priority Intelligence Requirements (PIRs).
3. Develop an intelligence collection plan.
4. Identify and register relevant sources.
5. Evaluate source reliability and information credibility.
6. Extract and corroborate material claims.
7. Build structured incident and technical evidence datasets.
8. Examine competing explanations and intelligence gaps.
9. Develop analytical judgements with explicit confidence levels.
10. Conduct evidence verification and quality assurance.
11. Publish the assessment with methodology and limitations.
12. Record lessons learned and methodological improvements.

## Application to Intelligence Projects

Individual investigations should reference the framework version used and maintain their own project-specific research records.

The framework defines the analytical process but does not prescribe the conclusions.

### Initial Application

[Russian State-Linked Cyber Activity in Europe — Threat Assessment, 2025–2026](https://github.com/jcharcenko/russian-cyber-threat-assessment-2025-2026)

This investigation will serve as the initial practical application of the framework.

## Version Control

Changes to analytical standards and templates will be documented and versioned.

Projects should identify the framework version used during their assessment.

Future revisions may incorporate improvements identified through research, quality assurance and practical application.

## Disclaimer

This is an independent professional development and research project.

The framework is not an official NATO, government or intelligence-agency publication. References to established intelligence methodologies do not imply institutional endorsement.

The detailed operational procedures are independently developed for research and portfolio use.

---

*Independent research and professional development project.*
