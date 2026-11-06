# Contributing to OCSD

Thank you for contributing to the OWASP Certified Secure Developer curriculum.
These guidelines define how curriculum changes should be written and reviewed.

## Audience and scope

OCSD is a foundation-level, knowledge-based certification in web application security for developers.
It has no coding exercises or other practical tasks.
The curriculum focuses on the security knowledge expected from any web application developer.
Specialized and advanced material belongs in future certifications unless it provides context needed to explain a foundational topic.

Explain unfamiliar security concepts in language that is clear to an audience with no formal security background.

Many secure design principles also apply outside web development.
Use general wording when it remains accurate, and use web-specific terminology and examples where they clarify the certification's scope.
For example, prefer `client-side check` to `browser check` when the statement also applies to mobile and desktop clients.

## Module structure

Each module has a dedicated directory containing files with distinct purposes:

- `NN.00 - Objectives.md` defines measurable knowledge outcomes and the expected competency.
- `NN.01 - Module Name.md` defines the assessable body of knowledge.
- `NN.02 - References.md` lists official OWASP material relevant to the module.
- `NN.03 - Supplementary Reading Material.md` explains the curriculum, shows how developers apply it, and provides external learning resources.
- `NN.04 - Parking Lot.md` (optional) holds notes while a module is being drafted.
  It is not part of the finished module and is removed when the module is finished.

File names use exactly these patterns, without suffixes such as `_WIP`.
Section headings in the body of knowledge and the supplementary reading use the numbering `## N.M Title`, where `N` is the module number.
Module titles in file headings use the form `# Objectives for Module N - Module Name`, with the module name exactly as it appears in the README.
The competency section is always titled `## Expected competency`.
Supplementary reading sections use `##` headings, and lists use `-`.

### Objectives

The objectives file starts with a short description of the module's purpose.
It then lists concise learning outcomes that state the knowledge a successful candidate is expected to demonstrate.
An expected competency section summarizes that knowledge in a realistic development context.

Learning outcomes must reflect the knowledge assessed by the examination.
Suitable verbs include `identify`, `recognize`, and `distinguish`.
Verbs such as `explain` and `describe` imply a constructed response.
Verbs such as `apply`, `use`, `create`, `implement`, `configure`, and `execute` imply practical performance.
These verbs should not describe assessment outcomes.

### Body of knowledge

The file named after the module defines its assessable scope.
It expands the learning outcomes into the concepts, relationships, principles, and practices covered by the certification.

Organize related content into a small number of meaningful topic areas.
Each scope statement should tell candidates, curriculum authors, and assessment writers what a candidate must identify, recognize, or distinguish.
Include relationships and relevant context so that the expected depth is clear.

Only include the detail needed to define the scope.
Explanations, references, extended examples, or motivational prose belong elsewhere.

### References

The references file contains official OWASP material only.
Official OWASP material means projects, standards, cheat sheets, and guides published under the OWASP organization, including their official websites (for example `cheatsheetseries.owasp.org`, `asvs.owasp.org`, `wstg.owasp.org`, and `top10.owasp.org`) and OWASP-hosted videos and presentations.
Anything else, including standards bodies, vendors, and third-party videos, belongs in the supplementary reading file.
Organize references by curriculum topic, use descriptive link text, and do not list the same resource twice.
Name the version of a standard (for example ASVS 5.0.0 or Top 10:2025) and prefer the current published edition.

Include relevant OWASP projects, standards, cheat sheets, guides, examples, tools, presentations, and videos.
Provide enough relevant references for developers to explore the topics of this module.

### Supplementary reading

Supplementary reading teaches the concepts named in the body of knowledge.
Write for developers who may encounter the topic for the first time.
Define important terms, explain why they matter, and connect security decisions to development work.
Practical language is appropriate in supplementary reading because it describes development work rather than an exam activity.

Refer to non-OWASP material when OWASP material does not cover an assessable topic in enough depth or when another format helps developers learn.
All links to non-OWASP material belong in the supplementary reading file.
Commercial books are acceptable, especially when their authors are affiliated with OWASP, but freely accessible web material is generally preferred.

Use practical examples to connect curriculum concepts to development work.
Choose examples that fit the module, such as reviewing a design, implementing a control, testing behavior, or responding to a failure.
Explain the security relevance of the decisions and outcomes shown.
When useful, include a worked example near the end of the teaching content that brings together several concepts in a realistic development task.
Place the example after the concepts it applies so readers can see how they work together.

## Sources and licensing

Verify that every linked source is relevant, credible, and accessible at the stated URL.
Prefer primary sources for standards, project guidance, and technical claims.

Links in the supplementary reading may point to copyrighted or commercial works.
A link does not grant permission to copy the linked material into this repository.
Non-OWASP material reproduced or adapted in the curriculum must be under a license compatible with CC BY-SA 4.0, such as CC BY 4.0, CC BY-SA 4.0, or CC0, and must keep the attribution its license requires.
Avoid material where the license or permission is unclear.

Contributions are licensed under the repository's CC BY-SA 4.0 license.
Contributors confirm that they have the right to submit the content they contribute.

Preserve official titles, trademarks, quotations, URLs, code, and identifiers exactly as published.

## Curriculum writing style

In keeping with other OWASP projects, all content must use American English.
Examples include `authorization`, `behavior`, `modeling`, and `organization`.

Curriculum prose should be direct, neutral, and precise.
It should support learning and preparation for the assessment.

- Use familiar words and define necessary technical terms.
- Prefer concrete subjects and verbs.
- Keep sentences and paragraphs focused.
- Remove filler, repeated summaries, promotional language, and unsupported claims.
- Use consistent terminology throughout a module.
- Explain abbreviations that may be unfamiliar to the expected audience.
- Use descriptive headings that state the subject or practical purpose of the section.
- If a heading has no content of its own, remove it or simplify the hierarchy.

## Markdown

- Put each sentence on its own source line to keep Markdown easy to review in a diff.
- Use `-` for unordered lists.
- Leave blank lines around headings, lists, and code blocks.
- Use descriptive link text.
- Avoid unnecessary HTML and manual formatting.

## Use of AI tools

Contributors may use AI tools to help draft or review content.
The contributor remains responsible for the accuracy, license compliance, and style of everything they submit.

- Disclose AI assistance in the pull request description, including which files were affected and which tool was used.
- Review and verify all generated content, including technical claims, links, and quotations, before submitting it.
- Do not submit unreviewed bulk generated content.
  Keep changes small enough for a reviewer to check.
- Do not paste material from sources whose license is incompatible with CC BY-SA 4.0.

Reviewers may ask for changes to, or close, a pull request that contains undisclosed or unverified AI-generated content.

## Curriculum-wide decisions

Changes that affect the module list or the scope of several modules require a decision by the working group.
Examples are adding, splitting, merging, or renaming modules, and changing where a topic is taught.
Open a [GitHub issue](https://github.com/OWASP/OCSD/issues) to propose it, and wait for the decision before opening a pull request.

## Review checklist

Reviewers check that:

- Every link resolves and the source is credible.
- The text uses American English and one sentence per line.
- Learning outcomes use assessable verbs.
- Every outcome has a matching body-of-knowledge topic, and every topic has supplementary reading and a reference.
- Cross-references to other modules name an existing module and section.
- The pull request touches one module, or only repository-wide files.

## Pull requests

Do not combine unrelated module changes in one pull request.
Submit repository-wide policy, formatting, or tooling changes separately from module revisions.

Please [open an issue](https://github.com/OWASP/OCSD/issues) if a proposed change requires a curriculum-wide decision.
