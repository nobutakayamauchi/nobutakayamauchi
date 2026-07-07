# GitHub Profile Next Actions

The next goal is profile alignment, not product expansion.

## Next Tasks

1. Confirm that the README points to the canonical RTS repository.
2. Confirm that the public description is concise and stable.
3. Confirm that experimental work is not presented as finished production infrastructure.
4. Confirm that no private context, operations logs, customer information, or secrets are present.
5. Add or update public-safe links only when they are stable.
6. Keep the profile readable for collaborators, reviewers, and future AI assistants.
7. Maintain `docs/profile/ECOSYSTEM_STATUS.md` as a public-safe ecosystem index, not a raw update log.

## Suggested Follow-up Files

```text
docs/profile/public_positioning_checklist.md
docs/profile/link_inventory.md
```

## Public Profile Checklist

Use this checklist before changing the public README:

- Does this improve clarity for a first-time visitor?
- Is the claim stable enough to keep public?
- Is the link canonical and maintained?
- Does this avoid private or operational material?
- Does this avoid overclaiming product readiness?
- Does this keep the profile concise?

## Ecosystem Status Checklist

Use this checklist before changing `docs/profile/ECOSYSTEM_STATUS.md`:

- Is this a public-safe summary rather than an internal operating note?
- Does it describe a repository class or ecosystem-level change?
- Does it avoid raw incident logs, customer data, secrets, and private context?
- Does it avoid treating every repository as active work?
- Does it point detailed protocol material back to the canonical RTS repository?

## Do Not Do Yet

Do not:

- add private personal context
- add operations logs
- add customer information
- add secrets, tokens, or credentials
- add unstable project links without review
- add long internal explanations
- turn the profile into a product landing page
- present experimental repositories as finished infrastructure
- use the ecosystem status file as a raw commit log

## Next Recommended Task

Create `docs/profile/link_inventory.md` if the number of public links grows.

That file should list each public link with:

1. label
2. URL
3. purpose
4. canonical or experimental status
5. maintenance owner
6. next review date or review trigger
