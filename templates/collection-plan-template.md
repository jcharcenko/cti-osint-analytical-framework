
# Intelligence Collection Plan

**Project:** [Project title]  
**Framework Version:** 1.0  
**Document Version:** 1.0  
**Status:** Draft  
**Assessment Period:** [Start date – End date]  
**Prepared By:** [Analyst]

## 1. Purpose

This collection plan defines how publicly available information will be identified, collected, evaluated and recorded to address the project's Priority Intelligence Requirements (PIRs).

**Primary Intelligence Question:**

[Insert approved intelligence question]

**Collection Objective:**

[Describe the information required and why it matters]

## 2. Collection Priorities

| Priority | PIR | Information Required | Collection Importance |
|---|---|---|---|
| 1 | PIR-01 | [Information requirement] | High |
| 2 | PIR-02 | [Information requirement] | High |
| 3 | PIR-03 | [Information requirement] | Medium |

Collection priorities must reflect the approved intelligence requirements.

## 3. Collection Streams

### Stream A — Official and Institutional Sources

Potential sources:

- National cybersecurity agencies and CERTs/CSIRTs.
- Government and intelligence-agency publications.
- Law enforcement reporting.
- International and regional institutions.
- Official statements from relevant parties.

**Collection Focus:** [Complete]

**Relevant PIRs:** [Complete]

Official reporting must be evaluated as evidence rather than automatically accepted as independently verified fact.

### Stream B — Technical Cybersecurity Research

Potential sources:

- Security vendor research.
- Incident response investigations.
- Malware and infrastructure analysis.
- Vulnerability disclosures.
- Academic technical research.
- MITRE ATT&CK documentation.

**Collection Focus:** [Complete]

**Relevant PIRs:** [Complete]

Technical observations must be distinguished from attribution claims and analyst inference.

### Stream C — Specialist and Regional Reporting

Potential sources:

- Specialist cybersecurity journalism.
- Investigative reporting.
- Regional publications.
- Independent research organisations.
- Relevant industry publications.

**Collection Focus:** [Complete]

**Relevant PIRs:** [Complete]

Trace material claims to their original evidence wherever possible.

### Stream D — Social Media and Alternative Sources

Potential sources:

- Public researcher posts.
- Public Telegram channels.
- Public technical forums.
- GitHub research repositories.
- Claims of responsibility.

**Collection Focus:** [Complete]

**Relevant PIRs:** [Complete]

Unverified claims should be retained as collection leads until sufficient evidence supports their inclusion.

## 4. Source Selection Criteria

Sources will be assessed for:

1. Relevance to the intelligence requirements.
2. Originality and proximity to the evidence.
3. Demonstrated expertise or direct access.
4. Transparency of methodology.
5. Availability of supporting documentation.
6. Potential dependence on other reporting.
7. Known limitations or conflicts of interest.

Source selection must not depend solely on whether reporting supports an anticipated conclusion.

## 5. Search Strategy

Document the planned search approach.

| Search ID | Topic / PIR | Search Terms or Method | Source Category | Status |
|---|---|---|---|---|
| SEARCH-001 | [PIR] | [Terms or method] | [Category] | Planned |
| SEARCH-002 | [PIR] | [Terms or method] | [Category] | Planned |

Consider:

- Relevant languages and alternative terminology.
- Actor aliases and campaign names.
- Geographic and sector-specific searches.
- Date restrictions.
- Historical and updated reporting.
- Source discovery through citations and references.

## 6. Incident and Claim Inclusion

An incident or claim may enter the analytical dataset when:

- It falls within the approved project scope.
- It is relevant to at least one PIR.
- At least one original supporting source has been inspected, or an exception is explicitly documented.
- Available evidence is sufficient for meaningful analysis.
- Uncertainty, disputes and attribution limitations are recorded.

The dataset must distinguish reported activity from independently corroborated activity.

## 7. Standard Collection Procedure

For each relevant finding:

1. Identify the potential incident, campaign or claim.
2. Locate the original or closest available supporting source.
3. Inspect the source and record its publication details.
4. Assign a unique source identifier.
5. Extract material claims without changing their meaning.
6. Evaluate source reliability and information credibility separately.
7. Search for independent corroboration and contradictions.
8. Record technical behaviours where supported.
9. Map relevant evidence to the approved PIRs.
10. Determine whether the finding belongs in the dataset or collection-leads register.
11. Record remaining gaps and follow-up requirements.

## 8. Evidence Management

The project should maintain the following records where relevant:

| Record | Purpose |
|---|---|
| `source-register.csv` | Source metadata, provenance and reliability |
| `claim-register.csv` | Individual claims, credibility and corroboration |
| `incident-dataset.csv` | Structured incident and campaign observations |
| `ttp-mapping.csv` | Technical behaviours and ATT&CK mappings |
| `collection-leads.csv` | Unverified or unresolved research leads |
| `analytical-notes/` | Analytical observations, alternatives and uncertainties |

Use consistent identifiers to connect records and supporting evidence.

## 9. Collection Gaps and Limitations

Potential limitations include:

- Non-public incidents.
- Incomplete technical disclosures.
- Limited access to original evidence.
- Reporting differences across countries and sectors.
- Unverifiable attribution.
- Language and translation limitations.
- Circular reporting.
- Delayed incident disclosure.

**Project-Specific Limitations:**

[Complete]

The resulting dataset represents publicly documented activity within the collection scope, not necessarily the complete population of incidents.

## 10. Collection Completion Criteria

Collection may be considered sufficient for initial analysis when:

- All PIRs have been addressed to the extent possible.
- Major relevant sources have been reviewed.
- Important incidents and campaigns have been assessed.
- Material competing perspectives have been considered.
- Significant claims have been evaluated for corroboration.
- Known intelligence gaps are documented.
- Records are sufficiently complete for quality assurance.

Completion does not imply that all relevant activity has been discovered.

## 11. Review and Change Control

| Version | Date | Change | Reason |
|---|---|---|---|
| 1.0 | [Date] | Initial collection plan | Project initiation |

Changes to collection priorities, inclusion criteria or scope must be documented.

## 12. Methodological Reference

This collection plan follows:

[CTI & OSINT Analytical Framework](https://github.com/jcharcenko/cti-osint-analytical-framework)

**Framework Version:** 1.0

Any departures from the framework must be documented and justified.

---

*Template — Adapt to the investigation before beginning systematic intelligence collection.*
