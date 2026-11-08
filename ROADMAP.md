# BatteryPassCheck - development roadmap

**Status:** Planned work only. None of the boxes are marked completed. Estimates are rough.

## Product-level acceptance criterion

A reproducible synthetic dataset passes checks and broken variants yield accurate diagnostics.

## Estimated work breakdown

| Step | Milestone | Estimated hours | Observable outcome |
|---|---|---:|---|
| 1 | Research and tag normative fields for schema draft | 9 | Source-linked field catalog and applicability notes |
| 2 | Implement versioned JSON Schema | 9 | Schema validates explicit positive and negative fixtures |
| 3 | Build CSV normalization and unit checks | 9 | Structured errors for invalid conversions and mismatches |
| 4 | Implement CLI and machine reports | 8 | Users can run offline sample checks |
| 5 | Create synthetic fixture generator | 7 | At least three device classes with fake values |
| 6 | Write tests, examples, and release guidance | 10 | Documented validation coverage and limitations |
| | **Total estimated** | **52** | |

## Detailed milestones

### 1. Research and tag normative fields for schema draft (9 estimated hours)

- [ ] Deliverable: Source-linked field catalog and applicability notes.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 2. Implement versioned JSON Schema (9 estimated hours)

- [ ] Deliverable: Schema validates explicit positive and negative fixtures.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 3. Build CSV normalization and unit checks (9 estimated hours)

- [ ] Deliverable: Structured errors for invalid conversions and mismatches.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 4. Implement CLI and machine reports (8 estimated hours)

- [ ] Deliverable: Users can run offline sample checks.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 5. Create synthetic fixture generator (7 estimated hours)

- [ ] Deliverable: At least three device classes with fake values.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 6. Write tests, examples, and release guidance (10 estimated hours)

- [ ] Deliverable: Documented validation coverage and limitations.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

## QA and release gates

- [ ] A real runnable implementation exists, with verified setup commands in `README.md`.
- [ ] Automated tests pass in a clean environment and failures are actionable.
- [ ] Only fabricated, original, openly licensed, or otherwise authorized sample data is published.
- [ ] No passwords, API keys, secrets, customer records, or employer/client confidential artifacts appear in repository history.
- [ ] A source-linked change log and actual progress notes distinguish finished work from plans.
- [ ] The GitHub history preserves authentic work and authorship; do **not** manufacture or backdate commits.

## Parking lot and risks

- Technical: Do not present speculative fields as final legal requirements; label every rule set with evidence and revision.
- Commercial hypothesis (not validated): Versioned rule modules, integrations, and technical support.
- Beyond MVP: defer paid extensions and hosted features until the underlying product works.
