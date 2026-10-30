# Automatic Speech Recognition: Introduction, Current Trends and Open Problems (2026)

Course slides by Laurent Besacier (NAVER LABS Europe), MOSIG, October 2026.

**Slides (PDF):** [ASRcourseMOSIG2026.pdf](ASRcourseMOSIG2026.pdf)

## Outline

1. From waves to words
2. Going end-to-end
3. Listening without labels (SSL)
4. Speech as tokens
5. When LLMs learn to listen
6. Talking while listening (full duplex)
7. Is ASR solved?

## Compiling

The slides are written in LaTeX (Beamer) and compile with a standard TeX Live distribution:

```sh
pdflatex ASRcourseMOSIG2026.tex
bibtex ASRcourseMOSIG2026
pdflatex ASRcourseMOSIG2026.tex
pdflatex ASRcourseMOSIG2026.tex
```

or simply `latexmk -pdf ASRcourseMOSIG2026.tex`.

## Repository content

- `ASRcourseMOSIG2026.tex`: slide source
- `*.bib`, `bibs/`: bibliography (new 2026 references are in `bibs/refs2026.bib`)
- figures at the root, in `images/` and in `images2026/`
- `wooclap_questions.txt`: optional quiz questions (quiz slides are hidden by default; set `\quiztrue` in the preamble to show them)

## Figures

Figures taken from papers or other sources are credited on the slides where they appear ("Figure from ..."). They remain the property of their authors.
