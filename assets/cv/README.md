[`Ziyu_Peng_Research_CV.pdf`](Ziyu_Peng_Research_CV.pdf) is the current downloadable CV, linked from both the homepage and the [web CV](../../cv.html).

The editable English LaTeX source is `Ziyu_Peng_Research_CV.tex`. The matched Chinese translation is [`Ziyu_Peng_Research_CV_ZH.tex`](Ziyu_Peng_Research_CV_ZH.tex), which builds [`Ziyu_Peng_Research_CV_ZH.pdf`](Ziyu_Peng_Research_CV_ZH.pdf). Keep names, dates, claims, figures, links, and section order aligned. Chinese compilation requires XeLaTeX and Noto Sans CJK SC; `.github/workflows/build-zh-cv.yml` builds and commits the Chinese PDF on TeX updates. Rebuild it from this directory with:

```bash
latexmk -pdf Ziyu_Peng_Research_CV.tex
latexmk -c Ziyu_Peng_Research_CV.tex
```

Keep the PDF filename unchanged so the download links remain valid. Update the TeX source and `cv.html` together, rebuild the PDF, and check its text and page layout before committing all three files. Honors should also agree with `index.html` and the repository README files.
