# resume_template

A clean, minimal LaTeX resume template for tech/cybersecurity roles. Single-page, ATS-friendly, and easy to customize — no build tools or dependencies beyond a standard LaTeX install.

---

## Files

| File | Description |
|---|---|
| `template.tex` | Main resume source — edit this |
| [`2_30_6.pdf`](https://github.com/mrxehmad/resume-template/blob/main/2_30_6.pdf) | Compiled PDF preview |
| `README.md` | This file |

---

## Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/resume_template.git
   cd resume_template
   ```

2. **Edit your details** in `template.tex` — replace the placeholder name, contact info, experience, and skills sections with your own.

3. **Compile to PDF**
   ```bash
   pdflatex template.tex
   ```
   Output: `template.pdf`

---




---

## Customization

All layout parameters are set at the top of `template.tex`:

```latex
% Page margins
\usepackage[top=0.35in, bottom=0.25in, left=0.55in, right=0.55in]{geometry}

% Font size
\changefontsizes{11pt}
```

### Sections

Each section follows the same pattern — easy to add, remove, or reorder:

```latex
\noindent\textbf{\large SECTION TITLE}\\[-6pt]
\noindent\rule{\textwidth}{0.5pt}

\vspace{5pt}
% your content here
```



```


**Via browser** (if using an HTML version): `Ctrl+P` → Save as PDF, set margins to None.

**Online:** Upload `template.tex` to [Overleaf](https://www.overleaf.com) and compile there — no local install needed.

---

## License

MIT — use freely, modify as needed, no attribution required.
