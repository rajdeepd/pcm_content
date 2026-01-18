# Proposed Structure for Cengage Carbon and its Compounds

## Directory Structure

Following the pattern established in the "Metals and Non-metals" chapter, the proposed structure for `/Users/rdua/work/github/rajdeepd/pcm_content/class10/chem_cengage/4-carbon-and-its-compounds` is as follows:

```
4-carbon-and-its-compounds/
├── concepts/                  # Main theory sections
│   ├── 01-bonding-in-carbon.md
│   ├── 02-versatile-nature.md
│   ├── 03-allotropes.md
│   ├── 04-organic-compounds.md
│   ├── 05-homologous-series.md
│   ├── 06-nomenclature.md
│   ├── 07-chemical-properties.md
│   ├── 08-ethanol-ethanoic-acid.md
│   ├── 09-soaps-detergents.md
│   └── index.md
├── exercises/                 # Practice questions
│   ├── 01-veryshort-answers.md (Moved from root)
│   ├── 02-short-answers.md      (Moved from root)
│   ├── 03-long-answers.md       (Moved from root)
│   ├── 04-concept-application.md
│   ├── 05-hots-questions.md
│   └── index.md
├── previous-years/            # Board and Competition questions
│   ├── 01-board-pyqs.md
│   └── index.md
├── images/                    # Chapter specific images
└── index.md                   # Main entry point
```

## Key Delta to Fix

1.  **Missing Theory (concepts/):** The working directory currently lacks all theoretical content from the 62 pages of the source.
2.  **Incomplete Exercises:** While some answer files exist, the actual questions and additional exercises (Concept Application, HOTS) are missing.
3.  **Visuals:** Most diagrams from the source need to be extracted and linked.

## Implementation Plan

1.  **Setup Structure:** Create the `concepts/`, `exercises/`, and `previous-years/` subdirectories.
2.  **Reorganize Existing Files:** Move the current answer files into the `exercises/` directory.
3.  **Map Source Content:** Use the `PAGE_CONTENT_MAPPING.md` to guide the extraction of theory and exercises from the 62 source images.
4.  **Extract Section-by-Section:** Start with theory (bonding, allotropes) and move towards chemical properties and functional groups.
5.  **Update Navigation:** Ensure the main `index.md` and sub-index files correctly link to all new content.
