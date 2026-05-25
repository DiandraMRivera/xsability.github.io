---
title: 'Accessibility Remediation of Mathematical Documents'
subtitle: '**Using Mathpix, Markdown and Pandoc**'
author: 'Diandra M Rivera^[With special acknowledgement to Lexi Murray for insightful discussions and revisions, and an exceptionally warm thank you to [Nikolay Yakimov](https://github.com/lierdakil) for addressing certain issues with pandoc-crossref.]'
width: '50%'
fontsize: '14pt'
linkcolor: 'blue'
linkReferences: true
---

This learning module will teach accessibility professionals how to use MathPix, Pandoc, and Markdown to remediate inaccessible mathematical documents to [WCAG AA](https://www.wcag.com/resource/what-is-wcag/#The_Three_Levels_of_WCAG_Conformance_A_AA_and_AAA) compliance. For someone completely unfamiliar with the topic, it should take 6-10 hours to complete. [Please  @sec:readme] before you get started.

1. [Start Here](https://diandramrivera.github.io/xsability/Beginners.html): After reading the forward below, get started here (~30-60 minutes)

   a. Download [this example](https://diandramrivera.github.io/xsability/ChavesPg28.pdf) and follow along.

   b. You will need to submit a remediated copy of the above to your superior to begin remediation tasks.

2. [Main Course](https://diandramrivera.github.io/xsability/MathRemediation.html): Here, we'll learn how to make mathematical documents *truly* accessible. No, it's not just converting file formats. (~3-4 hours)

3. [Practice File](https://diandramrivera.github.io/xsability/mFigPractice.pdf): Remediate this PDF using what you learned above. If you are new, this should take about 2 hours, and you absolutely need to reference section 5 in the main course.

4. The above has an answer key you can test with NVDA:

   a. [Remediated Practice File](https://diandramrivera.github.io/xsability/mFigPracticeRemediated.html).

   b. [Markdown Markup](https://diandramrivera.github.io/xsability/mFigPracticeMarkup.html) (copy and paste this into VS Code).

5. This workflow can also produce HTML presentations:

   a. [Accessible Presentation Slides](https://diandramrivera.github.io/xsability/htmlPresentation.html)

   b. [Markdown Markup](https://diandramrivera.github.io/xsability/htmlPresentationMarkup.html)

# Introduction {#sec:readme label="read the short introduction below"}

You show up to math class and the professor is drunk. They start rambling and scribbling at lightning speed, and most of what they are doing is complete nonsense. You raise your hand to ask a question, and in response they immediately erase everything they just wrote, and announce that they must start all over from the beginning, “to *hiccup* make you understand!!!”

You now know what it is like to read math with assistive technology when it is not made to be accessible. Math is its own language, and the rules to read it are different from almost every other form of written word. This is a problem for screen readers designed to read written language. We must insert additional “structure” into such documents so screen readers can recognize that math is not some other language, and display/announce it according to rules required to read it.

When those rules are in place, it is as if the math professor is suddenly sober. They even announce that they are going to start writing a complicated equation on the board. They pause at a term that appears terrifying, leaving their finger on it and staring at the class because they expect a question. You raise your hand, and ask, “Can you go back a few terms?” The professor points to previous terms until you say, “Yeah, that one,” and then you examine it together until you are satisfied.

Now you understand what it is like to read accessible math with assistive technology. Accessible math is called “MathML” or “MathJax”. Neither are a file format or program – they are simply a way of writing math that assistive technology can understand. The only way to remediate mathematical documents to be conformant with [WCAG AA](https://www.wcag.com/resource/what-is-wcag/#The_Three_Levels_of_WCAG_Conformance_A_AA_and_AAA) accessibility standards (e.g. to have MathML or MathJax) is to re-author inaccessible documents to include MathML or Mathjax, along with providing sufficient alt text, captions, descriptive tools like footnotes leading to tables, and the navigation features needed to maneuver around these elements so that users of assistive technology aren’t punished for needing to use it.

The easiest way to do this, to our knowledge, is to use Mathpix, Markdown, Pandoc, and VS Code to reauthor inaccessible PDF/Word formats into accessible HTML documents. We use Mathpix → Markdown → Pandoc (and Pandoc-crossref) → HTML to automatically transcribe TeX math markup into MathML/MathJax to **maximize accessibility** of what is written while **minimizing author effort** required to organize it in an understandable way (e.g. completely describing figures in a navigable manner).

## You Will Become a Better Author

This isn't just about accessibility. Completion of this course **will** make you a better author by:

1. Giving you software tools that completely separate the basic task of writing from the basic task of formatting
2. Giving you the tools needed to quickly switch journal formats so you aren't writing the same paper over and over
3. Giving you the tools to professionally typeset any document you write *in the easiest way possible*
4. Giving you tools to keep track of and insert references from an autogenerated bibliography (e.g. from Zotero or Mendeley) to make citations *as easy as possible*.
5. Giving you tools to start your own personal web page, if you're into that sort of thing.

These tools will make your authoring life *easy*. The reader has much to gain from finishing this course.
