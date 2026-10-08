
# Source Evaluation and Intelligence Confidence

**Framework:** CTI & OSINT Analytical Framework  
**Version:** 1.0  
**Status:** Initial Standard

## 1. Purpose

This document provides practical procedures for evaluating source reliability, information credibility, corroboration, attribution and analytical confidence.

It supplements `analytical-standard.md` and applies to investigations conducted under the framework.

## 2. Source Reliability

Source reliability concerns the source's demonstrated trustworthiness, reporting history, expertise and access to relevant information.

| Grade | Classification |
|---|---|
| A | Completely reliable |
| B | Usually reliable |
| C | Fairly reliable |
| D | Not usually reliable |
| E | Unreliable |
| F | Reliability cannot be judged |

### Assessment Procedure

For each source, examine:

1. Identity and provenance.
2. Relevant expertise and access.
3. Historical accuracy, where assessable.
4. Transparency of evidence and methods.
5. Corrections, retractions and documented inaccuracies.
6. Possible incentives, conflicts or reporting limitations.

Record the grade and its justification.

Do not automatically assign high reliability to government sources, established media or cybersecurity vendors.

Use F where there is insufficient evidence to judge reliability.

## 3. Information Credibility

Information credibility concerns the strength of an individual claim, rather than the reputation of the source making it.

| Grade | Classification |
|---|---|
| 1 | Confirmed by other sources |
| 2 | Probably true |
| 3 | Possibly true |
| 4 | Doubtful |
| 5 | Improbable |
| 6 | Truth cannot be judged |

### Assessment Procedure

For each material claim:

1. Identify the exact assertion.
2. Locate the original supporting evidence.
3. Examine whether the evidence directly supports the assertion.
4. Seek independent corroboration.
5. Identify contradictions or alternative explanations.
6. Assign a credibility grade with justification.

A reliable source may make an incorrect claim. A source with unknown reliability may publish independently confirmed information.

## 4. Corroboration Assessment

Corroboration requires supporting evidence that is genuinely independent.

### Independent Corroboration

Examples include:

- Separate technical investigations using distinct evidence.
- An official report supported by independently obtained victim evidence.
- Independent forensic findings that support the same material claim.

### Dependent Reporting

Examples include:

- Multiple articles repeating one government advisory.
- Several publications citing the same vendor report.
- Social-media posts reproducing a single unverified claim.

Dependent reporting must not be counted as multiple independent confirmations.

Where independence cannot be determined, record that limitation.

## 5. Attribution Assessment

Record attribution at three levels:

**Reported Attribution:** Who made the attribution and precisely what they claimed.

**Supporting Evidence:** The evidence publicly available to support or challenge that attribution.

**Analytical Judgement:** The conclusion justified by the available evidence.

Distinguish between:

- Confirmed observations.
- External attribution assessments.
- Claims of responsibility.
- Analyst inference.
- Unresolved attribution.

Official attribution and denial statements establish the respective stated positions but do not independently prove the underlying events.

## 6. Competing Perspectives

Identify material claims and counterclaims from relevant parties.

Assess them against the same evidentiary criteria.

Where perspectives conflict:

1. Record each substantive claim accurately.
2. Identify the evidence presented by each party.
3. Seek independent technical or documentary corroboration.
4. Identify unsupported assertions.
5. Explain which interpretation is best supported, if any.

Do not assume that conflicting accounts deserve equal evidentiary weight.

## 7. Analytical Confidence

Confidence describes the strength of the evidence and reasoning supporting an analytical judgement.

| Level | Guidance |
|---|---|
| High | Strong evidence, substantial independent corroboration and limited material contradictions |
| Moderate | Credible evidence with meaningful gaps, dependencies or plausible alternatives |
| Low | Limited, ambiguous, disputed or weakly corroborated evidence |

Confidence is separate from source reliability and information credibility.

Confidence is not a numerical probability or a statement of likelihood.

Every major judgement should include a short rationale explaining the confidence assessment.

## 8. Practical Evaluation Example

The following example is fictional and demonstrates the evaluation procedure only.

**Claim:** A government agency reports that a state-linked actor compromised a European energy organisation.

**Evidence available:**

- One official attribution statement.
- A technical advisory describing malicious activity.
- Three news articles repeating the official statement.
- No publicly available independent forensic confirmation of the named actor.

**Source reliability:** Evaluate the government agency and technical advisory publisher based on their respective reporting records and evidence. Do not automatically assign A.

**Information credibility:** Evaluate the compromise claim separately from the actor-attribution claim.

**Corroboration:** The three derivative news articles do not constitute independent confirmation.

**Attribution:** Record the official attribution, but distinguish it from independently verified technical evidence.

**Confidence:** A conclusion that malicious activity occurred may have a different confidence level from a conclusion identifying the responsible actor.

No definitive grade can be assigned from this simplified example without examining the actual sources and evidence.

## 9. Recording Requirements

Each source evaluation should include:

- Source ID.
- Source title and publisher.
- Original URL or document reference.
- Publication and access dates.
- Source reliability grade.
- Reliability justification.

Each material claim evaluation should include:

- Claim ID.
- Exact claim or faithful paraphrase.
- Supporting source IDs.
- Information credibility grade.
- Credibility justification.
- Corroboration status.
- Contradictory evidence, if applicable.
- Attribution status, where relevant.

## 10. Quality Assurance

Before an assessment is published:

- Recheck high-impact claims against original sources.
- Verify that source and claim ratings have recorded justifications.
- Review apparent corroboration for circular reporting.
- Check that competing evidence has not been omitted.
- Confirm that attribution language matches the supporting evidence.
- Review analytical confidence separately from source grades.
- Correct or qualify unsupported conclusions.

## 11. Methodological Note

The Admiralty Code provides a structured approach to grading sources and information.

The practical procedures, examples and confidence criteria in this document are framework-specific implementations, not official NATO or government assessment instructions.

---

**CTI & OSINT Analytical Framework — Source Evaluation v1.0**
