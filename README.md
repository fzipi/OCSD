# OWASP Certified Secure Developer (OCSD)

Welcome to the OCSD curriculum repository.
OWASP Certified Secure Developer (OCSD) is a proposed foundation-level certification focused on web application security for developers.
This repository contains the curriculum being developed by the OWASP OCSD working group, supporting references, and sample assessment questions.
This is the official OWASP project link: <https://owasp.org/www-project-certified-secure-developer/>

## Project Status
This repository is a curriculum-development resource, not an exam registration service or a finalized certification handbook.

## Charter

**Purpose.** Define the web application security knowledge that a foundation-level developer certification validates.

**Goals.**

- Publish a vendor-neutral curriculum built on established OWASP resources.
- Define measurable learning outcomes and an assessable body of knowledge for each module.
- Provide supplementary reading so developers can prepare without a formal security background.
- Provide sample questions that trace back to the learning outcomes.

**Non-goals.**

- Practical exercises, coding tasks, or tool operation. The assessment is knowledge-based.
- Specialized or advanced material, which belongs in future certifications.
- Exam registration, proctoring, or delivery.

**Governance.** The OWASP OCSD working group maintains the curriculum.
Module changes are reviewed through pull requests.
Changes that affect several modules or the module list need a working group decision, opened as a [GitHub issue](https://github.com/OWASP/OCSD/issues) first.

**Joining.** Open an issue or a pull request, and read [CONTRIBUTING](./CONTRIBUTING.md) first.

**Assessment format.** Knowledge-based questions only, with learning outcomes written using the verbs `identify`, `recognize`, and `distinguish`.
Sample questions are public in [Sample Question Bank](./Sample%20Question%20Bank.md) so candidates and authors can see the expected style and depth.

## Repository Layout

- [Curriculum](./Curriculum) contains one directory per module with objectives, body of knowledge, references, and supplementary reading.
- [Sample Question Bank](./Sample%20Question%20Bank.md) contains sample assessment questions.
- [To be decided](./To%20be%20decided) contains material the working group has not yet adopted. It is not part of the curriculum.
- [CONTRIBUTING](./CONTRIBUTING.md) defines structure, style, and review rules.
- [LICENSE](./LICENSE) applies to everything in this repository.

## Audience and Scope
OCSD is intended for web application developers who want to demonstrate foundational security knowledge and for hiring managers who need to assess that knowledge.

This certification program is an answer to the questions a hiring manager for a developer might ask, to validate security knowledge of the candidate.
It is also for the developers who want to showcase their skills in developing secure code.

Remember:

* ***Writing secure code != testing the security of code with tools***
* ***If developers do not put security in the code, no one else will***

The questions we may want to ask are:

* If I am hiring a web application developer, what are the security-related skills I would look for?
* If I were a web application developer, what security skills would I like to be validated for?

[CONTRIBUTING](./CONTRIBUTING.md) explains the structure of this repository.

## Curriculum Modules

Here are the [curriculum modules](/Curriculum) that the working group for OCSD has arrived at:

1. Secure Design, Architecture and Threat Modeling
2. Authentication and Credential Management
3. Authorization
4. Input Validation and Output Encoding
5. Cryptography and Key Management
6. Error Handling
7. Secure Logging
8. Data Protection and Privacy
9. Secure Communications
10. Software Supply Chain Security
11. Business Logic Security
12. Secure File and Resource Handling
13. API and Web Service Security
14. Secure Configuration and Deployment
15. Security of and for AI
16. Secure Developer Environment and Security Awareness

## Body of Knowledge

The curriculum prioritizes established OWASP resources and projects, but the working group is open to include other open-source materials too, if the license is compatible with CC BY-SA 4.0.

Here is an excerpt of OWASP projects that we are referencing:

- [Application Security Verification Standard (ASVS) 5.0.0](https://asvs.owasp.org/)
- [Cheat Sheet Series](https://cheatsheetseries.owasp.org/index.html)
- [Developer Guide](https://devguide.owasp.org/)
- [Software Assurance Maturity Model (SAMM)](https://owaspsamm.org/)
- [Mobile Application Security](https://mas.owasp.org/)
- [Top 10:2025](https://owasp.org/Top10/2025/)
- [API Security Top 10:2023](https://owasp.org/API-Security/editions/2023/en/0x00-header/)
- [Web Security Testing Guide (WSTG) v4.2](https://owasp.org/www-project-web-security-testing-guide/v42/)
- [Code Review Guide](https://owasp.org/www-project-code-review-guide/)

Modules cite the editions listed above unless a module states otherwise.


## Contributing

Contributions can improve the certification objectives, clarify the body of knowledge, add relevant references and teaching examples, or review sample questions.
Please read the [contributing guidelines](./CONTRIBUTING.md) before submitting any changes (PRs), and keep module revisions separate from repository-wide changes.
For proposals that affect the whole curriculum, please open a [GitHub issue](https://github.com/OWASP/OCSD/issues) first.

## Frequently Asked Questions

**Does holding another certification, such as CSSLP or CREST OVS, give credit toward OCSD?**
No. OCSD is a knowledge-based foundation certification, and the working group has not defined equivalence or grandfathering rules for other certifications.
To propose one, open a [GitHub issue](https://github.com/OWASP/OCSD/issues) that explains how the other certification's scope maps to the OCSD modules.

**Are the sample questions the real exam?**
No. The questions are samples that show the expected style and depth.

## License

This repository is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](./LICENSE).
