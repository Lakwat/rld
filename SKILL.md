---
name: restrained-legal-drafting
description: Draft and format restrained, conventional legal documents intended as formal attachments or standalone filings. Use when the user wants dense black-and-white legal prose without report styling, tables, decorative elements, repeated page headings, or AI-generated clutter. This skill governs drafting presentation and editorial discipline, not jurisdiction-specific filing requirements.
license: MIT
compatibility: Works as a portable Agent Skill. Document-generation tools are optional; when available, use them to produce DOCX or PDF while preserving these rules.
metadata:
  author: Lakwat
  version: "1.1.0"
---

# Restrained Legal Drafting

Apply this skill when drafting, revising, or rendering a formal legal document that should look conventional, serious, and deliberately plain.

## Scope

This skill controls writing style, document architecture, and visual presentation. It does not prescribe the mandatory procedural structure of a claim, complaint, appeal, submission, motion, or other jurisdiction-specific instrument. Follow any binding court, authority, institutional, or user-supplied rules first. Do not invent filing requirements.

## Default working method

1. Identify the document's purpose, audience, jurisdiction, relevant facts, legal basis, requested outcome, and evidentiary sources from the user's materials.
2. Do not ask again for information already supplied. Ask only for missing facts that materially affect accuracy or the requested outcome. When a minor fact is unavailable, use a clear placeholder outside the final document or state the assumption separately.
3. Verify current law and procedural claims from authoritative sources when research is required. Never fabricate quotations, authorities, dates, paragraph references, exhibits, or factual allegations.
4. Match the structure to the document: for short procedural submissions, prefer a compact, unnumbered *escrito*; for substantial pleadings or analyses, use a limited number of broad numbered sections when useful. Number paragraphs only if precise cross-referencing warrants it. Prefer prose over tables, bullets, cards, matrices, or summary boxes.
5. Remove repetition, generic filler, rhetorical inflation, and unnecessary restatements of the issue. Each paragraph should advance a fact, legal proposition, application, or requested conclusion.
6. Render the final document according to the presentation rules below. Keep drafting notes, caveats, and explanations outside the document.

## Presentation rules

Use black text on a white background. Use no colour, icons, logos, page borders, shaded boxes, callouts, decorative rules, sidebars, banners, or consultancy-style design.

Use Times New Roman unless the user or a binding format rule requires another typeface. As a neutral default, use 11-point body text (12 point is often preferable for a short one-page submission), 9-point footnotes, justified alignment, restrained spacing, and conventional A4 margins. Keep emphasis sparse. Use bold primarily for the title and numbered section headings; avoid decorative italics and excessive underlining.

Do not create a cover page, contents page, executive summary, abstract, keywords section, document-control table, revision history, or annex list unless the user or an applicable rule specifically requires it.

Place the document title once near the beginning. Do not repeat the title, case name, document type, party names, or section name as a running header on later pages. Use no running header by default.

For multipage documents, the footer must contain the centred page number only, as a plain Arabic numeral such as `1`. Do not write `Page 1`, `1 of 7`, a filename, a date, a confidentiality notice, or any other footer text unless a binding rule overrides this instruction. For a single-page short *escrito*, an entirely blank footer is acceptable and often preferable.

Treat the document as a formal attachment or standalone legal instrument, not as a letter. Do not add sender and recipient **postal address blocks**, salutations, email-style subject lines, courtesy closings, or contact panels unless the requested document is actually a letter. A concise formal addressee identifying the authority is appropriate for a short procedural submission; it is not a postal address block. Do not add a signature block unless requested or required.

Use tables only when the user expressly asks for one or when a binding form makes one unavoidable. Otherwise convert structured material into concise numbered paragraphs.

## Preferred format for short procedural submissions

When preparing a concise administrative or procedural *escrito* (for example, an *aportación documental*, *subsanación*, or brief request) and the authority's filing rules allow it, use the formal one-page style illustrated in `references/SHORT-SUBMISSIONS.md`. It is a **preferred visual reference**, not an obligatory legal template. Use the appropriate legal language and headings for the actual jurisdiction.

- At the top, centre the addressee authority in bold uppercase; directly beneath it, centre the relevant division or unit in regular type if known and useful. **Do not** invent a recipient or division.
- Below, align the case number and any notice/reference identifier to the left. Give the main case label restrained bold emphasis; keep ordinary reference text plain.
- Centre a short, specific, bold uppercase document title, separated from the metadata and body by deliberate white space. Use a descriptive title, not a generic decorative heading or a redundant 'formal' label.
- Open with one justified paragraph identifying the applicant or representative, their procedural capacity, and the matter. Bold the person's name only when it improves scanning. An opening formula such as `EXPONE:` may be used naturally.
- State the essential facts and what is being supplied in a few unnumbered, justified prose paragraphs. Do not force numbered sections, itemised demands, or headings for each paragraph.
- Introduce the requested action with a short bold line such as `Por lo expuesto, SOLICITA:`; then articulate the request in one continuous paragraph (or more only when genuinely needed).
- If there is an enclosure, identify it in a brief sentence such as `Documento que se acompaña: …`. Do not create a table, exhibits index, or numbered annex list for one attachment.
- End with a restrained place/date or electronic-filing formula, often right-aligned. Include a signature or identification block only when procedurally required or explicitly requested.
- Use black Times New Roman, generally 11–12 pt, justified body text, conventional A4 margins, moderate line spacing, and visible breathing room between the authority, identifiers, title, body, request, and closing. Aim for one clean page where the content naturally fits; never shrink text excessively just to achieve one page.
- For a **single-page** document, omit the running header and normally leave the footer blank. For a **multipage** document, if pagination is used, the footer contains only a centred Arabic page numeral.

This short-*escrito* format is an explicit exception to the longer-document preference for broad numbered sections. Never add false case numbers, signatures, dates, citations, or personal details merely to fill out the visual structure. Do not copy identifying information from reference images into reusable examples.

## Drafting style

Write in formal, precise, natural legal prose. Prefer concrete statements to abstract summaries. Avoid headings every few paragraphs; combine related material into broader sections. Avoid mini-headings disguised as italic opening sentences.

Maintain a clear progression: relevant facts, applicable law, application, and requested outcome, adapted to the document's actual purpose. This is an editorial sequence, not a mandatory procedural template.

Use complete first citations and precise pinpoints when sources are available. Keep citation style consistent. Footnotes should support specific propositions rather than collect broad, undifferentiated references. Do not duplicate the same sources in both footnotes and an annex merely to make the document appear more substantial.

Do not include statements such as “AI-generated,” “draft for review,” “legal advice disclaimer,” “here is your document,” or explanations of the formatting choices inside the document unless the user expressly requests them.

DO NOT CALL A CLAIM, CUSTOMER SUPORT CLAIM, OR SIMILAR A "FORMAL CLAIM" ON THE TITLE. THE WORD "FORMAL" HERE IS CRINGEY AF BRO

## Final quality check

Before delivery, confirm that:

- the document contains no unsupported factual or legal assertion;
- the requested outcome is stated clearly;
- sectioning is limited and useful (unnumbered short submissions; numbered sections only where warranted);
- prose is predominantly paragraph-based;
- there are no unnecessary tables, bullets, boxes, decorative elements, or repeated running headings;
- the title appears once;
- a single-page short submission has a blank footer, or each multipage footer contains only a centred numeral;
- there is no cover page or contents page unless required;
- citations are consistent and pinpointed where possible;
- drafting notes and explanations are outside the document; and
- the final PDF or DOCX has no overflow, clipped text, blank trailing page, broken footnotes, or inconsistent pagination.

## User overrides

A specific instruction from the user or a binding filing rule overrides the defaults in this skill. Apply the narrowest necessary deviation and preserve the restrained style everywhere else.
