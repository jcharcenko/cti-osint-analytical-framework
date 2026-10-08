
# CTI & OSINT Analytical Standard

**Version:** 1.0  
**Status:** Initial Standard  
**Effective Date:** October 2026  
**Maintained In:** CTI & OSINT Analytical Framework

## 1. Purpose

This standard establishes a consistent, evidence-led methodology for conducting Cyber Threat Intelligence (CTI) and Open-Source Intelligence (OSINT) investigations.

It is designed to support:

- Analytical accuracy and transparency.
- Consistent intelligence collection.
- Structured source evaluation.
- Independent corroboration.
- Technical threat analysis.
- Explicit uncertainty and confidence assessments.
- Reproducible findings.
- Quality assurance of AI-assisted research.

Individual projects must document any justified deviations from this standard.

## 2. Core Analytical Principles

### 2.1 Evidence-Led Analysis

Analytical conclusions must follow the available evidence rather than predetermined assumptions.

### 2.2 Source Traceability

Every material factual claim must be traceable to an identifiable source that has been inspected.

### 2.3 Separation of Evidence and Judgement

Distinguish between:

- Reported claims.
- Directly observable evidence.
- Analytical inference.
- Unverified or unknown information.

### 2.4 Competing Explanations

Materially different explanations must be considered and assessed according to the strength of their supporting evidence.

The assessment must not assume that opposing positions are equally credible or that the truth necessarily lies between them.

### 2.5 Explicit Uncertainty

Information gaps, contradictory evidence and analytical limitations must be documented.

Insufficient evidence is an acceptable analytical outcome.

## 3. Intelligence Requirements

Every project must establish:

1. Primary intelligence question.
2. Assessment purpose.
3. Geographic and temporal scope.
4. Relevant threat actors or activity categories.
5. Priority Intelligence Requirements (PIRs).
6. Inclusion and exclusion criteria.
7. Intended intelligence products.

These requirements must be established before systematic evidence collection begins.

## 4. Intelligence Collection

Collection must be directed by the approved intelligence requirements.

Relevant sources may include:

- Government and official institutional reporting.
- CERT/CSIRT advisories.
- Law enforcement reporting.
- Technical cybersecurity research.
- Academic research.
- Specialist and regional journalism.
- Public social-media and community OSINT.
- Official statements from parties presenting competing positions.

Primary sources should be preferred wherever possible.

Secondary reporting must be checked for dependence on the same originating evidence.

## 5. Source Reliability and Information Credibility

The framework adopts the Admiralty Code approach.

Source reliability and information credibility must be evaluated separately.

### 5.1 Source Reliability

| Grade | Classification |
|---|---|
| A | Completely reliable |
| B | Usually reliable |
| C | Fairly reliable |
| D | Not usually reliable |
| E | Unreliable |
| F | Reliability cannot be judged |

Source evaluation must consider historical accuracy, expertise, access, transparency and documented reliability concerns.

A source must not receive a grade solely because of its nationality, political alignment or institutional status.

### 5.2 Information Credibility

| Grade | Classification |
|---|---|
| 1 | Confirmed by other sources |
| 2 | Probably true |
| 3 | Possibly true |
| 4 | Doubtful |
| 5 | Improbable |
| 6 | Truth cannot be judged |

Information credibility must consider supporting evidence, independent corroboration, consistency, contradictions and uncertainty.

Every assigned rating must have a recorded justification.

Grades F and 6 indicate insufficient grounds for evaluation, not necessarily unreliability or falsehood.

## 6. Corroboration

Independent corroboration requires separate evidence streams supporting the same material claim.

Multiple articles repeating one original advisory do not constitute independent confirmation.

Where corroboration cannot be established, the limitation must be recorded.

## 7. Attribution Assessment

The assessment must distinguish:

**Reported attribution:** Attribution made by an external source.

**Supporting evidence:** Publicly available information supporting or challenging that attribution.

**Analytical judgement:** The project's own assessment of the attribution.

Official attribution and official denial are evidence of the respective stated positions, not automatic proof of the underlying facts.

## 8. Technical Threat Intelligence

Where applicable, investigations must examine documented technical behaviour.

This may include:

- Initial access.
- Execution and persistence.
- Credential access.
- Privilege escalation.
- Discovery and lateral movement.
- Command and control.
- Collection and exfiltration.
- Impact and disruption.

MITRE ATT&CK mappings must be based on incident-specific evidence.

Each mapping must be classified as:

- **Explicitly reported:** Supported directly by incident reporting.
- **Analyst mapped:** Derived from documented behaviour with an explained mapping.
- **Inferred:** Suspected but not demonstrated by incident-specific evidence.

Inferred techniques must not be counted as observed TTPs.

Relevant technical findings should be connected to defensive implications where possible.

## 9. Analytical Judgements and Confidence

Analytical confidence must be evaluated separately from source reliability and information credibility.

### High Confidence

Strong supporting evidence, substantial independent corroboration and limited material contradictions.

### Moderate Confidence

Credible supporting evidence, with meaningful information gaps, dependencies or plausible alternatives.

### Low Confidence

Limited, ambiguous, contested or weakly corroborated supporting evidence.

Confidence must be explained and must not be treated as a numerical probability.

## 10. AI-Assisted Research Controls

AI tools may support collection planning, research, translation, data organisation, technical analysis and drafting.

The following controls are mandatory:

1. No material factual claim may be published solely from AI model memory.
2. Original sources must be inspected before supporting significant claims.
3. Search snippets are not sufficient final evidence.
4. Quotations, dates, names, vulnerabilities and ATT&CK identifiers must be verified.
5. Unavailable or unverifiable sources must be identified.
6. Contradictory evidence must not be silently omitted.
7. AI-generated inferences must not be presented as independently observed facts.
8. Unsupported conclusions must be removed or qualified.
9. Source evaluations must not be manipulated to support preferred conclusions.
10. A final evidence and citation audit must precede publication.

## 11. Evidence Management

Projects should maintain structured records appropriate to their scope.

Recommended records include:

| Record | Purpose |
|---|---|
| Source register | Source identification, provenance and reliability |
| Claim register | Individual claims and supporting evidence |
| Incident dataset | Structured incident and campaign records |
| TTP mapping | Documented technical behaviour and ATT&CK mappings |
| Collection leads | Potential incidents requiring verification |
| Analytical notes | Judgements, competing explanations and limitations |

Records must use consistent identifiers and cross-references.

## 12. Standard Assessment Structure

A full intelligence assessment should normally contain:

1. Executive Assessment.
2. Key Judgements.
3. Intelligence Requirements and Scope.
4. Threat Landscape.
5. Incident or Campaign Analysis.
6. Competing Perspectives.
7. Technical TTP Analysis.
8. Targeting Analysis.
9. Defensive Implications.
10. Outlook and Indicators to Watch.
11. Analytical Confidence and Limitations.
12. Methodology and Sources.

Sections may be adapted to the subject and evidence available.

## 13. Publication Quality Assurance

Before publication, verify that:

- Material factual claims are traceable.
- Source evaluations are documented.
- Corroboration has been assessed.
- Attribution language is appropriately qualified.
- Technical mappings are supported by incident-specific evidence.
- Alternative explanations have been considered.
- Analytical confidence is justified.
- Figures and statistics accurately reflect the underlying data.
- Material intelligence gaps are disclosed.
- Sensitive or inappropriate information has been excluded.
- Executive assessments and key judgements pass a claim-by-claim evidence audit.

## 14. Version Control

This standard is maintained centrally within the CTI & OSINT Analytical Framework repository.

Each investigation must identify the framework version used.

Methodological changes should be documented and versioned.

Earlier assessments must not be silently represented as having followed procedures introduced in later versions.

## 15. Methodological References

The framework draws upon established intelligence evaluation practices, including:

- The Admiralty Code source reliability and information credibility grading approach.
- UK Ministry of Defence intelligence doctrine.
- MITRE ATT&CK for technical behaviour classification.

The detailed operational procedures are independently developed and are not official NATO or government requirements.

---

**CTI & OSINT Analytical Framework — Version 1.0**

*Independent research and professional development methodology.*
