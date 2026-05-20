
# Accessibility Remediation of Mathematical Content with Markdown, Pandoc, and MathPix
### Diandra Rivera

## Accessibile Math

The goal of these documents is to teach how to remediate inaccessible mathematics-rich content (pdf's, word, etc.) to [WCAG AA](https://www.wcag.com/resource/what-is-wcag/#The_Three_Levels_of_WCAG_Conformance_A_AA_and_AAA) (or above) standards. The [American Mathematical Society](https://www.ams.org/accessibility/accessibility-guidance) advocates for any tool that can accomplish this task. However, little information is available to digital accessibility professionals who need to re-author mathematics to satisfy the [following accessibility principles](https://www.w3.org/TR/WCAG21/#background-on-wcag-2)

- Math that is **distinguishable** from other elements in the document
- Math that is **navigable** at multiple scales *via keyboard input alone*
- Math that is **understandable**, either via assistive technology or by sight.
- Math for which the above features are **compatible** with *any browser and computer*

Additional document structure - usually markup - is required to enable the above features. We will introduce Markdown, VSCode, TeXMath, Pandoc Markdown and MathPix as authoring tools that will allow the readers of this document to re-author inaccessible pdf's into HTML documents (with encoded MathML and MathJax support) that conform to the above principles, and then [verify this conformance](https://websiteaccessibilitychecker.com/checker/index.php).

