# Changelog

All notable changes to this project will be documented here.

The project has not made an official 1.0.0 release. Repository-level static review has been performed, but the official `skills-ref validate` command has not yet been run. Runtime installation and host-agent workflow testing also remain pending.

## [Unreleased]

### Added
- Created the public GitHub repository.
- Established seven specialist disciplines, with Creative Direction as a cross-cutting capability:
  - Graphic Design & Branding
  - Illustration & 3D
  - UI/UX Design
  - Game Design & Development
  - Interactive Learning
  - Web & Application Development
  - Motion, Animation & Video
- Defined professional-proactive autonomy, T-shaped competency, and ready-to-use deliverable goals.
- Established adaptive production workflow and three-level QA approach.
- Established project continuity, decision tracking, change control, and handoff requirements.
- Added repository overview, project decision record, installation guide, and validation report.
- Added the main `SKILL.md` with operating principles, workflow, authority rules, QA, verification vocabulary, activation guidance, execution rules, edge cases, examples, and links to specialist references and templates.
- Added all ten specialist reference documents:
  - Creative Direction
  - Graphic Design & Branding
  - Illustration & 3D
  - UI/UX Design
  - Game Design & Development
  - Interactive Learning
  - Web & Application Development
  - Motion, Animation & Video
  - Quality Assurance
  - Project Continuity & Version Control
- Added all four reusable templates:
  - Project Brief
  - Design Specification
  - QA Checklist
  - Project Handoff
- Added `USER-GUIDE.md` with installation orientation, briefing patterns, production workflow, reference and asset handling, revision discipline, evidence-based QA, continuity practices, test scenarios, and a reusable starter prompt.

### Validation status
- All 15 core documents were fetched back from GitHub after creation.
- The user guide was fetched back from GitHub and checked for its validation-status note and starter prompt.
- README links to the user guide and distinguishes outstanding validation from completed static checks.
- All 14 relative links in `SKILL.md` were checked against repository paths; no broken links were found.
- `SKILL.md` frontmatter has the required `name` and `description`; the identifier is 32 characters, and the current file is 242 lines (below the 500-line recommendation).
- Main skill activation guidance and examples were expanded.
- Repository-level static review has been performed. **The official `skills-ref validate` command has not yet been run.**
- Runtime installation and real-agent workflow testing have not yet been performed; the project remains unreleased.

## [2026-11-27] — Studio standards v2.0 adoption

### Added
- Added `CORE-SKILL-v2.0.md`, `SPECIALIST-REFERENCE-GUIDE-v2.0.md`, and `WORKFLOW-QA-TEMPLATES-v2.0.md` from the user-approved source files.
- Established the three v2.0 documents as the authoritative Studio-wide standards.
- Retained the existing Agent Skills entry point, detailed specialist references, and reusable templates as supporting resources.

### Changed
- Updated `SKILL.md` to load and defer to the three governing v2.0 standards.
- Updated the README, project decisions, and validation report to document the v2.0 governance structure.

### Validation
- The three new files were created successfully on the `main` branch.
- Repository read-back, source-content comparison, relative-link checks, and final metadata checks are being performed.
- Official `skills-ref validate`, host installation, and runtime workflow tests remain outstanding. This adoption is not an official product release.

## Versioning policy

This project intends to use semantic versioning:

- **MAJOR:** incompatible changes to the skill's architecture, behavior, or document contracts.
- **MINOR:** backward-compatible capabilities, workflows, references, or templates.
- **PATCH:** corrections, clarifications, and non-breaking improvements.

A release must identify what was actually completed and verified. Planned work must remain clearly marked as planned.
