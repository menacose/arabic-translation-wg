# Acronyms Working Guide

Use [[Acronyms.base]] as the editable working table for acronyms.

## Why Acronyms Are Separate

Acronyms are not ordinary glossary terms. In this translation project, most acronyms should remain in English and be explained on first occurrence according to [[Arabic-Style-Guide-v0.1]].

## How It Works

- Each acronym is a Markdown note in `01-Glossary/Acronyms/`.
- [[Acronyms]] is the readable source list.
- [[Acronyms.base]] is the editable working table.
- Duplicate acronyms are kept in one note with multiple expansions.

## Recommended Fields

| Field | Purpose | Suggested Values |
|---|---|---|
| `acronym` | Acronym as written in source | Source text |
| `primary_expansion` | Main expansion shown in table view | Source text |
| `arabic` | Arabic handling note | `Keep English`, `Translate expansion`, `TBD` |
| `status` | Source or approval status | `Source acronym`, `Approved`, `Needs review` |
| `translation_status` | Current working state | `Needs Arabic handling`, `Approved`, `Needs WG decision` |
| `ambiguity` | Whether acronym has multiple expansions | `Single expansion`, `Multiple expansions` |

## Working Rule

Keep the acronym in English unless the Arabic style guide or a decision record says otherwise.
