# AGENTS.md

This file is for agents editing or reading the list in `README.md`.

## How to read the list

The list follows a memory lifecycle: **representation → evolution → retrieval → evaluation**, plus applications and adjacent work.

- Short headings are category names. The sentence under each heading is the bucket definition.
- A paper may appear in more than one subsection. That is intended: browse by what you are looking for, not by unique paper.
- **Adjacent / Out of Scope** is contrast (GraphRAG, non-graph memory, generic agent memory), not the core personalized graph-memory set.

## Adding or moving a paper

1. Use this row shape:

   `**Official Title** (Venue'YY) [[paper]](url) [[code]](url)`

2. Put the paper under **every** heading it actually illustrates (structure, evolution operation, retrieval mechanism, evaluation family, or application). Copy the same row; do not write a one-line “see also”.
3. Keep rows alphabetical by title inside each table.
4. Placement must come from the paper text, or from where the companion survey cites that paper. Do not classify from the title, abstract, or memory alone.
5. Do not drop a paper from a heading just because it already appears elsewhere.

Companion survey (same taxonomy): keep a local clone or the ICKG draft nearby when reorganizing. If a claim is only in the survey, place the paper only in the survey section that cites it.

## Metadata

For paper rows, verify title, venue stamp, paper URL, and optional code URL.

Short version:

- Title: official arXiv Atom or proceedings title. Expand stubs (`Mem0`, `GraphGen`, `TemporalKGMemory`). Do not rewrite official wording for style.
- Venue: published track when known. Keep Findings, Industry, and workshops distinct (`ACL Findings'26`, `Lifelong Agent@ICLR'26`). Preprint only → `arXiv'YY`.
- Paper URL: unversioned `https://arxiv.org/abs/<id>` when an arXiv version exists.
- Code URL: only if the paper, arXiv comment, or official project page states it, and the link resolves.

Do not commit unless the maintainer asked for a commit.
