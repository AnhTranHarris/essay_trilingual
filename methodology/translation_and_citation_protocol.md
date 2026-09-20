# Translation and Citation Protocol

## Scope

This file defines process only. It contains no essay prose.

## Canonical literary text

The 1925 Charles Scribner's Sons first edition of *The Great Gatsby* is the **sole literary source** for the analytical paper.

Use the searchable Project Gutenberg transcription to locate candidate passages. Then verify every quoted phrase against the 1925 first-edition page image before it is accepted into the evidence ledger.

Spanish and Chinese editions of the novel are not required authorities for this project.

## Essay architecture

The English essay is the canonical analytical document.

The Spanish and Mandarin/Simplified-Chinese versions are faithful translations of that same essay. They are not separate research papers and must not introduce new substantive claims, new Fitzgerald evidence, or new interpretations that are absent from the English version.

Each paragraph receives a stable identifier:

- EN-P001, EN-P002, ...
- ES-P001, ES-P002, ...
- ZH-P001, ZH-P002, ...

ES-P001 and ZH-P001 must correspond semantically to EN-P001.

## English-draft freeze

Translation begins only after the English essay passes:
- quotation verification;
- page-citation verification;
- literary-device verification;
- argument consistency review;
- MLA citation review.

The approved English version receives a frozen version identifier in GitHub. Spanish and Mandarin translations must reference that frozen English version.

If the English essay changes materially after translation begins, the affected translated paragraphs must be re-opened and re-verified.

## Fitzgerald quotations in translation

Every quoted Fitzgerald passage must have:
- evidence ID;
- chapter;
- verified 1925 page number;
- exact English transcription;
- MLA citation decision;
- Spanish project-translation status;
- Mandarin/Simplified-Chinese project-translation status.

When the project translates Fitzgerald's own words, do not imply that the wording comes from a published Spanish or Chinese translator.

Where MLA conventions require it, identify the rendering as the authors' or project translation.

## Controlled translation protocol

For every paragraph:

1. Freeze and identify the English source paragraph.
2. Record the paragraph's core proposition.
3. Record any terms that must remain consistent.
4. Record metaphorical or rhetorical features that must survive translation.
5. Produce a natural Spanish or Mandarin/Simplified-Chinese rendering.
6. Compare the translated paragraph against the English semantic invariant.
7. Check terminology consistency against the project glossary.
8. Check citations and quoted material.
9. Run an independent back-translation or semantic-review pass.
10. Revise any material drift.
11. Mark the paragraph verified in GitHub only after all required checks pass.

## Semantic invariants

Before translating a difficult paragraph, record what may not change:
- factual claim;
- literary claim;
- degree of certainty;
- causal relationship;
- metaphorical relationship;
- emotional register;
- citation relationship.

Syntax may change. Meaning may not.

## Translation-quality principle

The objective is not literal word substitution.

Spanish must read as formal, educated **Mexico City / standard Mexican Spanish with international Latin American readability**. It should avoid both Spain-specific forms and strongly regional Mexican slang. See `methodology/spanish_translation_style_guide.md`.

Mandarin must read as educated **Beijing / Mainland Standard Mandarin written Chinese in Simplified Chinese**, with national readability and no Beijing-dialect slang or heavy regional coloring. Follow the dedicated style guide in `methodology/mandarin_beijing_translation_style_guide.md`.

Target-language syntax may differ substantially from English if the analytical meaning remains stable.

## Anti-hallucination rule

A literary quotation, page number, or bibliographic claim cannot enter the final document unless its English evidence record is VERIFIED.

A translated paragraph cannot enter the final document unless it maps to an approved English paragraph and passes the translation QA protocol.

Interpretive claims must distinguish:
- direct textual evidence;
- reasonable literary inference;
- outside critical scholarship, if any is later authorized.

## GitHub quality assurance

GitHub is the project's provenance and QA environment.

Use it to maintain:
- immutable source references;
- metaphor evidence records;
- English draft version history;
- paragraph IDs;
- translation status;
- terminology/glossary decisions;
- semantic-drift findings;
- correction history;
- final verification states.

GitHub is not a literary source and is not an author. It documents how the two authors controlled quality.

## Current state

The English essay is frozen for translation. Spanish translation quality is locked to the Mexico City international standard defined in `methodology/spanish_translation_style_guide.md`.

Spanish is frozen. Mandarin/Simplified-Chinese translation may proceed only under the Beijing/Mainland native-flow standard, paragraph-level semantic QA, back-translation review, literary-device verification, and full-document vertical coherence review.
