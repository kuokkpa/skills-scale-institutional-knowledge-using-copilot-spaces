# OctoAcme Role RACI Matrix

This template provides a standalone, reusable RACI matrix mapping common OctoAcme artifacts and activities to project roles.

For full role definitions and context, see [docs/octoacme-roles-and-personas.md](../octoacme-roles-and-personas.md).

---

## RACI Key

| Code | Meaning |
|---|---|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; single point of accountability |
| **C** | Consulted — provides input before or during |
| **I** | Informed — notified of progress or completion |

---

## RACI Matrix

| Artifact / Activity | Developers | Product Manager | Project Manager | UX Designer | DevOps Engineer | Data Analyst | Support Lead |
|---|---|---|---|---|---|---|---|
| Project One-pager | C | A/R | C | C | C | C | C |
| Backlog & Acceptance Criteria | C | A/R | I | C | C | C | C |
| Definition of Done (DoD) | A/R | C | C | C | C | — | — |
| Risk Register | C | C | A/R | I | C | I | I |
| Sprint / Iteration Planning | R | A | R | C | C | I | I |
| CI/CD Pipeline & Deployments | C | I | I | I | A/R | I | I |
| Release Notes | C | A | R | C | C | I | R |
| Incident Communications | C | I | I | I | R | I | A/R |
| Retro Action Items | C | C | A/R | C | C | C | C |
| Success Metrics & Dashboards | C | A | I | C | C | R | C |
| User Research & Prototypes | C | C | I | A/R | — | C | C |

---

## Usage Notes

- **A/R** indicates a role that is both accountable and the primary contributor for that activity.
- A dash (**—**) indicates the role is not typically involved in that activity.
- Adapt ownership assignments to match your team's actual structure and size.
- Keep this matrix updated as new roles are added or responsibilities shift.
