# Installation Guide

## Package contents

This repository is an Agent Skills-style package. Keep the following structure intact:

- SKILL.md — required entry point and operating instructions.
- references/ — specialist guidance loaded when relevant.
- templates/ — reusable project documents.
- README.md, PROJECT-DECISIONS.md, and CHANGELOG.md — repository documentation and governance.

Do not copy only SKILL.md: its relative links depend on the supporting folders being present.

## 1. Obtain the package

Choose either method:

### Git

```bash
git clone https://github.com/khusnajulidar/creative-design-game-development.git
```

### ZIP archive

Download the repository ZIP from GitHub and extract it. Keep the extracted folder named:

```text
creative-design-game-development
```

The folder name must match the name value in the SKILL.md frontmatter for strict Agent Skills implementations.

## 2. Add it to an agent environment

Use the skill-discovery or custom-skills location documented by the AI agent product you use. Copy or move the entire creative-design-game-development folder into that location.

Installation directories and activation behavior differ between products and versions. Do not assume that a path used by one agent is valid for another. Consult the target product's current documentation.

If the environment supports repository-based skills, it may be possible to reference this repository directly instead of copying it. Confirm that the product supports this package structure and can resolve its relative reference files.

## 3. Refresh and confirm discovery

Follow the target product's instructions to reload, refresh, or restart its skill index. Confirm that the skill appears under the identifier:

```text
creative-design-game-development
```

If it does not appear, check the folder nesting first. The expected layout is:

```text
<skills-location>/
└── creative-design-game-development/
    ├── SKILL.md
    ├── references/
    └── templates/
```

Avoid accidental double nesting such as:

```text
<skills-location>/
└── creative-design-game-development/
    └── creative-design-game-development/
        └── SKILL.md
```

## 4. Run a practical activation check

Try a small, low-risk request such as:

> Create a clear project brief and visual direction for a simple educational mobile game. Identify the audience, core loop, deliverables, and acceptance criteria.

Then try a cross-discipline request such as:

> Review this existing interface before proposing changes. Preserve approved behavior, identify the relevant design and development references, and provide a focused implementation and QA plan.

Check whether the agent:

- Recognizes the task and applies the appropriate discipline references.
- Clarifies only consequential missing information.
- Separates assumptions from approved decisions.
- Proposes concrete deliverables and acceptance criteria.
- Preserves existing work when asked to continue a project.
- Reports tests and limitations honestly.

## 5. Product-specific notes

This repository follows the open Agent Skills package convention, but individual products may differ in discovery, loading, permissions, and supported features. The package does not grant the agent access to GitHub, local files, design software, deployment systems, or other external tools by itself. Those capabilities depend on the host environment and the user's connected tools and permissions.

## Current validation caveat

The repository structure and SKILL.md metadata have been statically reviewed. Runtime installation, automatic discovery, and real-agent workflow tests have **not** yet been completed for a specific AI product. Do not treat the package as product-tested until those checks are performed.