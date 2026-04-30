# AGENTS.md

## Purpose
This repository is a curated list (`README.md`) of deception-related resources. Future Codex runs should prioritize **accuracy over volume** and avoid speculative edits.

## Rules for updating `README.md`
1. **Never fabricate details**
   - Do not invent titles, dates, summaries, authors, venues, or claims.
   - If a source page/PDF cannot be accessed well enough to verify facts, do **not** add or modify that entry.

2. **Year must be verified, not inferred loosely**
   - Confirm the year from the source itself (publication date, paper metadata, DOI page, arXiv record, conference page, etc.).
   - Do not rely only on surrounding list context or assumptions.

3. **Default placement rule: append to the end of the relevant subsection**
   - Unless the user explicitly asks for reordering/sorting, add new bullets to the **end** of that subsection.
   - Do not insert a new entry between existing items that share the same year unless explicitly asked to reorder.

4. **Keep existing style consistent**
   - Format: `- [Title](URL) (YEAR) - short description.` for paper-like entries.
   - Use concise, factual descriptions based on verifiable source content.

5. **Avoid silent quality regressions**
   - Do not duplicate an existing link/resource.
   - Ensure the resource goes in the correct section (`Articles`, `Research`, `Talks`, etc.).
   - Preserve markdown structure and headings.

## PR and commit title conventions
- For paper additions, keep titles simple and consistent: `Add Paper - <short details on paper>`.
- Avoid overly long or quirky PR/commit titles; prefer concise, descriptive wording.

## Pre-commit checklist (required)
- Verify each changed/added URL and title are real.
- Verify each changed/added year is correct.
- Confirm new bullets were appended (unless user requested different ordering).
- Check for accidental duplicates.
- Run: `git diff -- README.md` and sanity-check every changed line.
