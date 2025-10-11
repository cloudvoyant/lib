# Claude Code Instructions

## Plan Maintenance

**IMPORTANT**: Please update `.claude/plan.md` whenever:

- A major task or phase is completed
- Significant architectural changes are made
- New features or scripts are added
- The implementation approach changes

**How to update**: Read the current plan, review the todo list status, and rewrite the relevant sections to reflect actual progress and any new insights.

**Reminder frequency**: Suggest updating the plan after completing 2-3 related tasks or at the end of a work session.

## Project Context

The following files MUST be respected:

**User-facing documentation** (in `docs/`):
- `docs/design.md` captures the project's design principles and philosophy - this is effectively the prime directive that must be respected at all times
- `docs/architecture.md` captures architecture and important implementation details. The architecture outlined in this doc must be respected, and implementation details must be kept up to date as development proceeds.
- `docs/user-guide.md` is a user guide for the project, and must similarly be kept up to date.
- `docs/decisions/` contains Architectural Decision Records (ADRs) documenting important design choices. When making significant architectural changes:
  - Create a new ADR file: `docs/decisions/NNN-short-title.md`
  - Follow the ADR template in `.claude/style.md`
  - Update the index in `docs/decisions/README.md`
  - Update relevant documentation (design.md, architecture.md)
  - Reference ADRs when explaining architectural choices

## Development Workflow

When working on this project:

1. Always source the plan before starting work
2. Update todo list as tasks progress
3. Test scripts work from different directories
4. Ensure all scripts use logging shortcut functions
5. Update plan.md when completing milestones
6. When plan.md is completed, review project docs and ensure they are up-to-date
7. Delete plan.md
