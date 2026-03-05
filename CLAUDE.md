# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

LaTeX resume repository for Yash Capoor, built on Jake's Resume template. Maintains multiple tailored variants for different application contexts.

## Building

Requires a LaTeX distribution with `pdflatex` and the Fira Sans font package (`FiraSans`).

```bash
pdflatex default_1Pager.tex
pdflatex applied-ai-1pager.tex
```

Alternatively, compile on Overleaf by uploading the `.tex` file directly.

## Creating a New Variant

1. Copy an existing `.tex` file
2. Update the `Profile` section bullets to match the target role
3. Reorder/rephrase experience bullets to surface relevant work
4. Adjust the `Skills` section for the right technologies

## Custom LaTeX Commands

Defined in the preamble of each file (identical across variants):

- `\resumeItem{text}` — a single bullet point
- `\resumeSubItem{text}` — indented sub-bullet
- `\resumeSubheading{title}{date}{company}{location}` — job heading with 4 fields
- `\resumeSubSubheading{title}{date}` — secondary role under same company
- `\resumeProjectHeading{title}{date}` — for projects or non-standard entries (e.g., career break)
- `\resumeSubHeadingListStart/End` — wraps experience entries
- `\resumeItemListStart/End` — wraps bullet lists under a heading
