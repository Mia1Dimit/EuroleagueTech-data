# Data Dictionary

## Purpose

This document defines the data domains, folder-level schemas, and quality expectations for Euroleague-Tech-data.

## Dataset Scope

The repository captures structured basketball technology research across teams, vendors, staff, and technology domains.

## Data Domains

| Domain | Folder | Unit of Record | Format |
|---|---|---|---|
| Team Profiles | euroleague-teams/ | One file per team | Markdown |
| Vendor Profiles | vendor-profiles/ | One file per vendor | Markdown |
| Team Staff Profiles | euroleague-teams-staff/ | One file per team staff map | Markdown |
| Technology Analyses | technology-analysis/ | One file per technology domain | Markdown |
| Research Reports | research-reports/ | One file per cited study/report summary | Markdown |
| Reference Policies | root-level files | One file per policy/guide | Markdown |

## Canonical Identifiers

### Team ID (recommended)
- Lowercase slug aligned to filename.
- Example: real-madrid, fenerbahce-beko-istanbul.

### Vendor ID (recommended)
- Lowercase slug aligned to filename.
- Example: catapult-sports, kinexon, wsc-sports.

### Category ID (recommended)
- Lowercase slug by capability domain.
- Example: performance-tracking, video-analysis, fan-engagement.

## Folder-Level Schema Guidance

### Team Profiles: euroleague-teams/
Recommended sections:
1. Team Overview
2. Confirmed Technology Stack
3. Likely/Unconfirmed Technology Signals
4. Vendor Relationships
5. Evidence Notes
6. Last Verified Date

Suggested core fields inside each file:
- team_name
- country
- competition
- technologies_confirmed
- technologies_likely
- sources
- confidence_level
- last_verified

### Vendor Profiles: vendor-profiles/
Recommended sections:
1. Vendor Overview
2. Products and Capabilities
3. Euroleague Adoption Signals
4. Strategic Positioning
5. Evidence Notes
6. Last Verified Date

Suggested core fields:
- vendor_name
- vendor_category
- products
- known_clients_euroleague
- differentiators
- sources
- confidence_level
- last_verified

### Team Staff Profiles: euroleague-teams-staff/
Recommended sections:
1. Performance and Medical Staff Roles
2. Analytics and Video Roles
3. Publicly Visible Responsibilities
4. Evidence Notes
5. Last Verified Date

Suggested core fields:
- team_name
- role
- person_name
- area
- source
- confidence_level
- last_verified

### Technology Analyses: technology-analysis/
Recommended sections:
1. Domain Definition
2. Key Vendors
3. Team Adoption Patterns
4. Market Trends
5. Risks and Constraints
6. Evidence Notes
7. Last Verified Date

Suggested core fields:
- domain_name
- summary
- key_vendors
- adoption_examples
- evidence
- confidence_level
- last_verified

### Research Reports: research-reports/
Recommended sections:
1. Citation Metadata
2. Method Summary
3. Key Findings
4. Relevance to Euroleague Context
5. Limitations

Suggested core fields:
- title
- authors
- year
- publication
- doi_or_url
- findings_summary
- practical_implications
- limitations

## Confidence Model

Use one explicit confidence label per claim cluster:
- High: directly supported by primary source or official publication.
- Medium: supported by multiple secondary sources with consistent evidence.
- Low: single-source signal or inference requiring validation.

## Freshness and Verification

- Every profile should include a Last Verified date.
- Revalidation cadence recommendation:
  - High-priority entities: every 30-60 days
  - Medium-priority entities: every 90 days
  - Long-tail entities: every 180 days

## Data Quality Rules

1. Separate fact from assumption in each file.
2. Include traceable sources for new claims.
3. Prefer primary sources over derivative commentary.
4. Avoid non-attributed numerical claims.
5. Keep naming conventions consistent with filenames.

## Known Constraints

- Public information may be incomplete or delayed.
- Some vendor/team relationships are commercially undisclosed.
- Official document redistribution rights may be restricted.

## Change Management

- Significant structure updates should be logged in CHANGELOG.md.
- New fields should be added consistently across comparable folders.
- Deprecated fields should be documented before removal.
