---
title: 'Accessibility Remediation of Mathematical Documents'
subtitle: '**Using Mathpix, Markdown and Pandoc**'
author: 'Diandra M Rivera^[With special acknowledgement to Lexi Murray for insightful discussions and revisions, and an exceptionally warm thank you to [Nikolay Yakimov](https://github.com/lierdakil) for addressing certain issues with pandoc-crossref.]'
width: '50%'
fontsize: '14pt'
linkcolor: 'blue'
---

This is a self contained learning module about how to use MathPix, Pandoc, and Markdown to remediate inaccessible mathematical documents to [WCAG AA](https://www.wcag.com/resource/what-is-wcag/#The_Three_Levels_of_WCAG_Conformance_A_AA_and_AAA) compliance. For someone completely unfamiliar with the topic, it should take 6-10 hours to complete.

1. [Main Course](https://diandramrivera.github.io/xsability/MathRemediation.html): Here, we'll not only learn how to make math accessible, but how to make *mathematical documents* accessible. No, it's not just converting file formats. (~3-4 hours)

2. [Practice File](https://diandramrivera.github.io/xsability/mFigPractice.pdf): Remediate this PDF using what you learned above. If you are new, this should take about 2 hours, and you absolutely need to reference section 5 in the main course.

3. The above has an answer key you can test with NVDA:

   a. [Remediated Practice File](https://diandramrivera.github.io/xsability/mFigPracticeRemediated.html).

   b. [Markdown Markup](https://diandramrivera.github.io/xsability/mFigPracticeMarkup.html) (copy and paste this into VS Code).

4. This workflow can also produce HTML presentations:

   a. [Accessible Presentation Slides](https://diandramrivera.github.io/xsability/htmlPresentation.html)

   b. [Markdown Markup](https://diandramrivera.github.io/xsability/htmlPresentationMarkup.html)

## Read Me

Accessible math is MathML or math that's been transcribed by MathJax presented and organized in a way that is easy for users of assistive technology to understand. It's not a file format, or a program. We use Mathpix → Markdown → Pandoc (and Pandoc-crossref) → HTML to encode TeX math markup into MathML/MathJax to maximize accessibility of what is written while minimizing the effort required of authors to present it in an understandable way (e.g. completely describing figures).

By the time you are done with this course, the above paragraph should make complete sense.
