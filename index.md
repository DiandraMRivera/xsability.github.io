---
title: 'Accessibility Remediation of Mathematical Documents'
subtitle: '**Using Mathpix, Markdown and Pandoc**'
author: 'Diandra M Rivera^[With special acknowledgement to Lexi Murray for insightful discussions and revisions, and an exceptionally warm thank you to [Nikolay Yakimov](https://github.com/lierdakil) for addressing certain issues with pandoc-crossref.]'
width: '50%'
fontsize: '14pt'
linkcolor: 'blue'
---

This is a self contained learning module about how to use MathPix, Pandoc, and Markdown to remediate inaccessible mathematical documents to [WCAG AA](https://www.wcag.com/resource/what-is-wcag/#The_Three_Levels_of_WCAG_Conformance_A_AA_and_AAA) compliance. For someone completely unfamiliar with the topic, it should take 6-10 hours to complete.

1. [Main Course](https://diandramrivera.github.io/xsability/MathRemediation.html)

2. [Practice File](https://diandramrivera.github.io/xsability/mFigPractice.pdf)

3. The above has an answer key you can test with NVDA:

   a. [Remediated Practice File](https://diandramrivera.github.io/xsability/mFigPracticeRemediated.html).

   b. [Markdown Markup](https://diandramrivera.github.io/xsability/mFigPracticeMarkup.html) (copy and paste this into VS Code).

4. This workflow can also produce HTML presentations:

   a. [Accessible Presentation Slides](https://diandramrivera.github.io/xsability/htmlPresentation.html)

   b. [Markdown Markup](https://diandramrivera.github.io/xsability/htmlPresentationMarkup.html)

## Read Me

Accessible math is MathML or transcribed by MathJax. It's not a file format, or a program. We use Mathpix → Markdown → Pandoc (and Pandoc-crossref) → HTML to encode TeX math markup into MathML/MathJax to maximize accessibility while minimizing the effort required of authors to completely describe figures.

By the time you are done with this course, the above paragraph should make complete sense.
