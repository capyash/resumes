# Yash Capoor — Resume

LaTeX resume built on [Jake's Resume](https://github.com/sb2nov/resume) template. Maintains multiple tailored variants for different application contexts.

## Variants

| File | Target |
|------|--------|
| `default_1Pager.tex` | General-purpose one-page resume — full-stack, ML/AI, and engineering leadership |
| `applied-ai-1pager.tex` | AI/ML-focused variant — emphasizes agentic AI, RAG, NLP, and applied ML experience |

## Building

Requires a LaTeX distribution with `pdflatex` and the [Fira Sans](https://ctan.org/pkg/fira) font package.

```bash
pdflatex default_1Pager.tex
pdflatex applied-ai-1pager.tex
```

Or use [Overleaf](https://www.overleaf.com) — upload the `.tex` file and compile directly.

## Customization

To create a new variant:

1. Copy an existing `.tex` file as your starting point
2. Adjust the **Profile** section to match the target role
3. Reorder or rephrase experience bullets to emphasize relevant work
4. Update the **Skills** section to highlight the right technologies

## License

MIT