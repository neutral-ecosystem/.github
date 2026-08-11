# Neutral ecosystem roadmap

This roadmap describes direction, not release commitments. Neutral is in an
early foundation stage, priorities may change as the design is validated, and no
dates or versions are promised here.

## Current: establish the foundation

- Define the initial goals and boundaries of the Neutral programming language.
- Establish public repositories as projects are ready for collaborative work.
- Document project-specific build, test, contribution, security, and licensing
  decisions.
- Develop the language specification, parser/toolchain foundations, diagnostics,
  and an initial standard-library direction.
- Keep the ecosystem's interfaces and terminology coherent without coupling the
  projects unnecessarily.

## Next: usable development workflows

- Explore a unified Neutral CLI for creating, building, running, and testing
  projects.
- Add repeatable testing, formatting, and release processes to active
  repositories.
- Develop language tooling and editor integration as the language design becomes
  stable enough to support them.
- Prototype a provider-neutral pipeline representation, validator, and planner
  for Neutral CI/CD, initially integrating with a practical provider when useful.

## Later: broaden the ecosystem

- Expand package and toolchain support based on demonstrated needs.
- Explore additional CI/CD provider adapters while preserving a provider-neutral
  core.
- Develop Neux as independently usable Linux system tooling where its scope is
  clear and maintainable.
- Evaluate graphical or higher-level tooling only after the underlying models
  and command-line workflows are established.

## Project boundaries

- **Neutral** is the programming language and its toolchain.
- **Neutral CLI** is the unified command-line interface for ecosystem workflows.
- **Neutral Flow** is a pipelining tool.
- **Neux** is standalone Linux system tooling; it is not the Neutral language or
  a Linux distribution.

Progress should be tracked in each public project's issues and milestones once
those repositories exist. Proposals are welcome through the relevant repository;
see [`CONTRIBUTING.md`](CONTRIBUTING.md).
