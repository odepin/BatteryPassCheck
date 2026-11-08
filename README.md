# BatteryPassCheck

> Preflight checks for structured battery-passport datasets.

**Current state:** Documentation starter / proposed product. The presence of this README does **not** mean the software has been implemented, deployed, used. Update this status to reflect real work.

## What it is

BatteryPassCheck is a proposed specialist software tool for Smaller battery assemblers, e-mobility engineering teams, and their software integrators. Battery-passport data fields, applicability, and versioning are complex for small producers starting data-readiness work. The intended differentiation is: Offline, schema-first checks using synthetic datasets, without operating a commercial passport service.

## Intended users and use cases

- Check a synthetic e-bike battery record and locate missing values
- Switch schema versions and inspect changed requirements
- Feed conflicting units and produce a useful correction hint

## Planned features

- Define a battery data model with explicit mandatory/optional field applicability
- Validate CSV and JSON submissions against a declared schema version
- Surface missing values, inconsistent units, and invalid enumerations
- Create fake sample battery datasets for automated testing
- Export a JSON validation log and an evidence-gap summary

## Proposed technology

Python 3.12+, Pydantic, JSON Schema, Typer, pytest

These technologies are *planned*, not a claim that dependencies have already been installed or code has been written. Revise this section when actual implementation decisions are made.

## Proposed architecture

- Versioned JSON Schema and applicability matrix
- Cross-field consistency checks
- CSV/JSON import and normalization
- CLI output adapters and fixture tests

See [TECHNICAL_PLAN.md](TECHNICAL_PLAN.md) for technical boundaries and acceptance tests.

## Running locally

**Not yet runnable.** This package contains documentation templates, not software. When a functioning implementation is available, replace this paragraph with tested prerequisites, install instructions, a verified executable command, and a reproducible example using `Synthetic battery records using invented identifiers and clearly labeled mock materials.`

## Data boundaries and exclusions

Certification, issuance of official digital passports, production battery identity tracking, or storing confidential supplier records. All public examples should use Synthetic battery records using invented identifiers and clearly labeled mock materials.

## Known limitations / validation risks

Do not present speculative fields as final legal requirements; label every rule set with evidence and revision.

## Development roadmap

Work is broken into estimated, not-yet-completed milestones in [ROADMAP.md](ROADMAP.md). They are *planning estimates*, not an assertion that development has begun or that work will definitely be performed.

## Business direction

Potential commercial extensions: Versioned rule modules, integrations, and technical support. 

## Contributing and licensing

License: [Mozilla Public License 2.0](LICENSE) (`MPL-2.0`). The distribution contains the complete license text. Any future source files can include the SPDX identifier `MPL-2.0` and the Exhibit A notice where appropriate. Rights in contributions and project ownership must be verified before licensing.

