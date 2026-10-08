# Restrained Legal Drafting

A portable Agent Skill for drafting formal legal documents in a conventional, deliberately plain style: black text, white background, paragraph-led structure, limited numbered headings, no tables by default, no decorative report design, no repeated running title, and a footer containing only the page number.

The skill is intended for legal documents attached to emails or used as standalone formal instruments. It is not a library of jurisdiction-specific pleading formats and does not claim to replace court rules, procedural law, or professional review.

## Contents

- `SKILL.md` — the portable Agent Skills definition.
- `PROMPT.md` — a fallback instruction block for models or clients that do not load Agent Skills.
- `references/CONFORMANCE.md` — a concise review checklist for generated DOCX and PDF files.

## Use

Give your AI agent access to this directory through its supported skills mechanism, then invoke the skill by name in the request. For example:

> Use `restrained-legal-drafting`. Draft a formal PDF submission from the attached evidence. Keep the legal research separate from the document and flag any missing material facts before finalising it.

For a client without Agent Skills support, paste the contents of `PROMPT.md` before the drafting request.

## Design principles

The repository intentionally avoids elaborate templates, graphic assets, macros, and procedural form libraries. The objective is consistency and restraint, not automation theatre.

## Priority of instructions

Binding procedural or institutional requirements come first, followed by explicit user instructions, then this skill's defaults. The skill should never invent a mandatory format for a lawsuit, complaint, appeal, or other filing.

## Licence

MIT. See the [LICENSE](./LICENSE) file.

## Verified drafting extension

This case-specific development fork builds on upstream commit `5f66ec70414e8c0fa19c815fe087f35f3c743cb7`. It adds claim-level primary-source verification, adversarial author review, independent review, explicit filing gates, restrained document generation and release hashes. No case evidence or personal data is stored here. Upstream `main` is preserved.
