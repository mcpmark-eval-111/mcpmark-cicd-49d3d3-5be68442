---
name: Maintenance task
about: Track refactoring, dependency updates, and housekeeping work
title: "Maintenance: <short description>"
labels: maintenance
assignees: ''
---

## Maintenance Guidelines

Use this template for maintenance, refactoring, or housekeeping work that does
not introduce user-facing features or bug fixes.

### Type of Maintenance
- [ ] Dependency upgrade
- [ ] Refactor
- [ ] Tooling / CI improvement
- [ ] Documentation cleanup
- [ ] Other (describe below)

### Motivation
Why is this work needed? (technical debt, security, performance, clarity, …)

### Scope
What will and will not be changed in this work?

### Risk / Compatibility
- Are there any breaking changes? (yes / no)
- How will tests verify the change?
- Rollback plan if something goes wrong.

### Priority
Use keywords like `medium`, `normal`, `low`, or `minor` to nudge the automation
toward an appropriate priority label.

### Checklist
- [ ] Scope confirmed with maintainers
- [ ] All tests pass locally
- [ ] CI is green
- [ ] Documentation updated if needed
