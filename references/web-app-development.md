# Web & Application Development

## Purpose and scope

Implement reliable, maintainable digital products across web, mobile, desktop, and related environments. Translate approved requirements and UI/UX specifications into working software. Do not treat a visual mockup as a functioning implementation.

## 1. Requirements and scope

Clarify users, use cases, functional and nonfunctional requirements, supported platforms, data, integrations, privacy expectations, performance needs, deployment context, and acceptance criteria. Separate essential scope from optional enhancements. Record assumptions and constraints.

## 2. Architecture and technology selection

Choose technologies based on product needs, team capability, ecosystem maturity, maintainability, security, performance, accessibility, deployment, licensing, and cost. Avoid selecting a framework merely because it is fashionable.

Define major components, responsibilities, data flow, state ownership, API boundaries, persistence, error handling, and environment configuration. Prefer the simplest architecture that safely supports the requirements and expected growth.

## 3. Frontend implementation

Build semantic, responsive interfaces that follow approved design specifications. Use reusable components where they improve consistency and maintainability. Handle loading, empty, error, success, disabled, and offline states. Ensure keyboard, pointer, and touch interaction as relevant.

Keep content, state, presentation, and business rules appropriately separated. Avoid brittle selectors, duplicated logic, hidden dependencies, and arbitrary hard-coded values when a documented configuration or design token is appropriate.

## 4. Backend, data, and APIs

Define data models, validation, authorization, error responses, pagination, rate limits, and API contracts. Validate untrusted input on the server. Handle retries and partial failures safely. Use transactions or idempotency where operations could be repeated or partially completed.

Document data ownership, retention, backup, migration, and deletion behavior. Protect secrets and credentials; never place private keys or sensitive tokens in client-side code or public repositories.

## 5. Security and privacy

Apply least privilege, secure authentication and authorization, safe session handling, input validation, output encoding, dependency updates, secure transport, and appropriate protection against common application vulnerabilities.

Collect only necessary personal data. Explain data use where required and provide appropriate consent, retention, and deletion behavior. Do not log secrets or sensitive information. Perform a risk-appropriate security review; do not claim a formal security audit without one.

## 6. Compatibility and performance

Define supported browsers, operating systems, screen sizes, and device capabilities. Optimize loading, rendering, memory, network requests, assets, and bundle size according to the product. Use progressive enhancement or graceful fallback when suitable.

Test representative environments rather than asserting universal compatibility. Consider poor network conditions, interrupted requests, small screens, zoom, and lower-powered devices.

## 7. Code quality and testing

Use clear naming, consistent formatting, modular structure, comments for non-obvious decisions, and documented setup instructions. Add automated tests where valuable:
- Unit tests for isolated logic.
- Integration tests for component boundaries and data flow.
- End-to-end tests for critical user journeys.
- Regression tests for previously fixed defects.

Run linting, type checks, builds, and tests when available. Record commands, environment, results, and failures. Do not say a build or test passed unless it was actually executed successfully.

## 8. Debugging and change management

Reproduce defects, inspect evidence, identify root causes, and make focused fixes. Avoid unrelated refactoring during a targeted correction. Preserve existing behavior unless change is intentional. Review affected dependencies and perform regression checks after modifications.

Use source control, meaningful commits, branches or tags as appropriate, and safe rollback practices. Keep secrets and generated artifacts out of version control unless explicitly required and safe.

## 9. Deployment and maintenance

Document build and deployment steps, environment variables, migrations, hosting assumptions, monitoring, backup, rollback, and recovery. Verify deployment outcomes rather than assuming that a successful local build means the product is live.

Plan maintenance for dependencies, browser changes, data lifecycle, accessibility, and evolving user needs.

## Deliverables

Provide working source code, configuration examples without secrets, setup/build/test instructions, architecture notes, API/data documentation, deployment guidance, QA evidence, and known limitations.

## Definition of done

The required functionality is implemented and integrated, critical journeys work in tested target environments, security/privacy and accessibility concerns have been addressed proportionately, build/test results are reported accurately, and another developer can run and maintain the project from the handoff.
