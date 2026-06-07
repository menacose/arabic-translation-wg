# Glossary Working Table Guide

Use [[Glossary.base]] as the editable working table for all glossary terms.

## How It Works

- Each glossary term is a Markdown note in `01-Glossary/Terms/`.
- Source definitions from Appendix C are stored inside the same term notes.
- Each term note has Obsidian properties such as `english`, `arabic`, `status`, `review_state`, and candidate options.
- [[Glossary.base]] displays those properties as a table.
- Editing a cell in the Base updates the property in the term note.

## Recommended Fields

| Field | Purpose | Suggested Values |
|---|---|---|
| `status` | Formal approval status | `Proposed`, `Approved`, `Rejected`, `Deprecated` |
| `review_state` | Current working state | `Needs WG vote`, `Needs SE review`, `Needs language review`, `Approved` |
| `option_a` | First Arabic candidate | Free text |
| `option_b` | Second Arabic candidate | Free text |
| `option_c` | Third Arabic candidate | Free text |
| `decision` | Linked decision record | `DEC-XXX` or `TBD` |
| `term_type` | Term category | Free text |
| `matrix` | Link to scoring matrix | Obsidian link |

## Dropdown Note

Native Obsidian properties do not provide strict dropdown fields inside Markdown tables. Bases and Properties make editing easier and usually autocomplete existing property values. If the WG needs enforced dropdown values, use a community plugin such as Metadata Menu later.

## Working Rule

Use [[INCOSE-MENA-Arabic-Glossary]] for presentation and publication. Use [[Glossary.base]] and the term notes for working edits. Use [[Source-Terms-and-Definitions]] when you need to review source definitions.
