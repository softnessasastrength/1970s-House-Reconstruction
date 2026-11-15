# 1970s-House-Reconstruction

Architectural reconstruction of a 1970s home, featuring Revit BIM models, floor plans, historical design references, material schedules, and documentation.

## Status

Repository scaffolding, initialized 2026-11-07. The folder structure and
working conventions are in place; the reconstruction content itself is at an
early stage. In the words of the Revit workspace README: "No completed BIM
model is claimed by this repository scaffolding."

## Repository layout

| Folder | Contents |
| --- | --- |
| `docs/` | Project documentation: the architectural brief (`architectural-brief.md`), existing conditions (`existing-conditions.md`), and the design-decision log (`design-decisions.md`). |
| `materials/` | Materials and bill of materials. Tracks material, specification, unit, quantity, source, price date, and confidence. Quantities remain provisional until reconciled to verified geometry. |
| `plans/` | Plans and drawings, organized into `existing/`, `demolition/`, and `proposed/` as applicable, with revision, scale, date, and status on each issued sheet. Conceptual drawings are not marked permit-ready. |
| `references/` | Historical and design references: original 1970s imagery, drawings, product literature, and later alterations, catalogued with provenance, copyright/usage status, and whether each reference depicts the actual house or an analogous example. |
| `revit/` | Revit BIM workspace for approved Revit project deliverables, with Revit version, units, linked models, families, and source drawings recorded in the model manifest before committing. Currently contains only its README — no model yet. |
| `systems/` | Building systems: structural, electrical, plumbing, HVAC, and life-safety assumptions, documented separately. Final system designs require applicable code review and qualified professional verification. |

Each folder's own README carries its full working conventions.
