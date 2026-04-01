# Sources and Evidence Policy

## Purpose

This file defines how sources are selected, cited, and maintained in Euroleague-Tech-data.

## Source Hierarchy

Use this priority order when building or updating claims:

1. Primary sources
- Official league publications
- Official team announcements
- Official vendor documentation
- Peer-reviewed publications

2. Secondary sources
- Reputable industry analysis
- Major media reporting with named evidence

3. Tertiary sources
- Aggregators and commentary
- Informal analysis threads

## Citation Requirements

For each material claim, provide:
- source title
- publisher/organization
- publication date (if available)
- URL or document identifier
- access date

## Confidence Mapping

- High confidence: primary source directly supports claim.
- Medium confidence: multiple secondary sources converge.
- Low confidence: single source or partial evidence.

## Recommended Citation Block (Template)

Use this template inside markdown profiles:

Source:
- Title:
- Publisher:
- Date:
- URL:
- Accessed:
- Supports:
- Confidence:

## Inclusion and Exclusion Rules

### Include
- Publicly available sources with traceable origin.
- Research papers with stable references.
- Official statements and product documentation.

### Exclude
- Unverifiable rumors.
- Anonymous social posts without corroboration.
- Copyrighted documents that cannot be legally redistributed.

## Legal and IP Notes

- Team names and trademarks belong to their respective owners.
- Official league documents may be referenced but not necessarily redistributed.
- When in doubt, store metadata and links, not document binaries.

## Source Maintenance Workflow

1. Add source metadata when creating/updating a claim.
2. Assign confidence label.
3. Add Last Verified date in the target file.
4. Re-check stale sources during periodic review.

## Minimum Quality Bar per File

A profile is considered publishable when:
- at least one traceable source is present
- confidence is declared
- fact vs assumption is clearly separated
- last verification date is included

## Initial Repository Source Inventory (Current)

Current source-bearing areas in this repository include:
- research-reports/
- technology-analysis/
- vendor-profiles/
- euroleague-teams/
- euroleague-teams-staff/
- CONFIRMED-FACTS-ONLY.md

## Future Expansion (Optional)

You can later add a machine-readable source register, for example:
- sources/index.csv
- sources/index.json

with columns such as:
- source_id
- entity_type
- entity_id
- source_type
- citation_title
- publisher
- date
- url
- confidence
- last_verified
