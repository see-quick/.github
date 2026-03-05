# Strimzi AI Usage Policy

> [!NOTE]
> **AI is welcome. Humans are responsible.**

Current AI tools are useful as coding assistants, but not as autonomous contributors.
Anyone submitting content to Strimzi is fully responsible for the correctness, intent, testing, and licensing compliance of the contribution.

## Motivation

This policy encourages the use of AI tools within the Strimzi project to boost productivity and innovation while ensuring transparency and quality.
Disclosure creates accountability and helps ensure contributors take ownership of AI-assisted work, rather than placing a disproportionate review burden on maintainers.
It also serves legal purposes, as copyright law around AI-generated content continues to evolve and proper attribution helps maintain the integrity of the project's licensing under Apache 2.0.

## Acceptable Uses of AI Tools

AI tools are accepted as development assistants for:

* **Code scaffolding**: Generating boilerplate code and initial implementations
* **Refactoring**: Suggesting code improvements and modernization
* **Testing**: Creating test cases and test data
* **Documentation**: Drafting technical documentation and code comments
* **Debugging**: Identifying potential issues and suggesting fixes
* **Research**: Exploring architectural approaches and best practices

## General Guidelines

1. Contributors are fully responsible and accountable for all their submissions.
This includes Pull Requests (PRs), issues, comments, or any other form of engagement with the project and its maintainers.
2. Contributors using AI to generate content should:
   * Thoroughly review all AI-generated content before submission
   * Understand the reason and impacts of the changes
   * Refine AI output to meet project quality standards
   * Take full ownership of all submitted content regardless of origin
   * Ensure content does not violate legal copyright or other laws
3. Pull Requests that include AI-generated code can only be for issues that are accepted (i.e., not labeled as `triage`).

> [!IMPORTANT]
> Contributors SHOULD disclose any substantial use of AI.
> Disclosure SHOULD take the form of a trailer line within the commit attributing the AI tool used.
> Acceptable formats include:
> * `Assisted-by: Claude <noreply@anthropic.com>`
> * `Co-authored-by: Claude <noreply@anthropic.com>`
> * `Generated-by: Claude <noreply@anthropic.com>`

> [!TIP]
> Many AI coding tools automatically add `Co-authored-by` trailers, this is acceptable and need not be changed to `Assisted-by`.

### Scope of Disclosure

Disclosure is expected when AI tools have materially contributed to the submitted content.

**Requires disclosure:**

* AI wrote a function, class, or significant code block that you included
* AI suggested an algorithm, architecture, or approach you adopted
* AI generated tests, documentation, or commit messages you used
* AI-suggested solutions, refactoring, or significant debugging help that shaped the final implementation

**Does not require disclosure:**

* General Q&A or learning (even if it informed your approach)
* IDE autocomplete (e.g., Copilot line completions, IntelliSense)
* Using AI to explain existing code
* Asking AI to review your human-written code
* Spell checking or minor syntax corrections
* Content that has been substantially rewritten such that the original AI output is no longer recognizable

When in doubt, err on the side of disclosure — transparency benefits the community.

[Strimzi Maintainers](https://github.com/strimzi/governance/blob/main/MAINTAINERS) are exempt from these rules and may use AI tools at their discretion (i.e., they have proven themselves trustworthy to apply good judgment).

## Documentation

The same legal and licensing considerations that apply to code also apply to documentation contributions.
Contributors must ensure AI-generated documentation does not include copyrighted material and that tool licensing terms are compatible with Apache 2.0.

## Website & Blog Guidelines

Strimzi accepts blog post contributions from maintainers and external contributors.
For blog posts:

1. AI-generated images **are permitted** if disclosed correctly at the time of contribution.
2. Contributors must ensure they have the right to use and publish any AI-generated media and cite AI usage.
3. Media must not infringe on third-party copyrights or trademarks.
4. AI-generated images should support the content and should never be used to replace thoughtful writing.

**Blog Content Expectations**

Blog posts are considered project contributions and must reflect original human authorship.
Contributors are expected to:
* Share original ideas, experiences, or informed perspectives
* Own the narrative, structure, and technical accuracy
* Use AI as a drafting or editing aid (i.e., not as the sole author)

> [!CAUTION]
> Blog posts that are primarily or entirely AI-generated, with minimal human insight, will be rejected.

Disclosure of AI assistance for blogs is encouraged for transparency but not mandatory unless requested.

## Legal and Licensing Considerations

Strimzi is licensed under the Apache License 2.0.
In line with [ASF guidance on generative tooling](https://www.apache.org/legal/generative-tooling.html), contributors using AI tools must ensure that:
* The AI tools terms of use do not place any restrictions on its output that are inconsistent with the [Open Source Definition](https://opensource.org/osd)
* At least one of the following conditions is met for any AI-generated output:
   - The output is not copyrightable subject matter
   - No third-party copyrighted materials are included in the output
   - Any third-party materials included have been licensed under terms compatible with Apache 2.0
* Contributors should use available tool features or code scanning to obtain reasonable certainty about the above conditions
* All third-party content is properly attributed
* The [Developer Certificate of Origin (DCO)](https://developercertificate.org/) can be truthfully signed

> [!WARNING]
> Contributors must also comply with their employers policies regarding AI-assisted open source work.

Strimzi follows both [ASF guidance on generative tooling](https://www.apache.org/legal/generative-tooling.html) and [CNCF / Linux Foundation guidance on AI-assisted development](https://www.linuxfoundation.org/legal/generative-ai).

## Review Process

Reviewers should apply the same standards to all contributions regardless of origin.
When reviewing contributions that disclose AI assistance, reviewers should pay particular attention to:

* Code quality and adherence to project coding standards
* Appropriate test coverage
* Security implications (AI tools may introduce subtle vulnerabilities)
* Long-term maintainability and avoiding over-engineering
* That the contribution is not verbose or superficially correct without real substance

Low-effort submissions that appear to be unreviewed AI output may be rejected without detailed feedback until properly refined.

## Policy Evolution

This policy will be reviewed and updated as needed to reflect:
* Changes in AI tooling and use of this tooling across open source projects
* Legal or regulatory developments
* Maintainer and reviewer experience in conjunction with community feedback
* Evolution of CNCF and industry best practices

## Questions and Feedback

Please share feedback and any questions or concerns about this policy, including areas that feel too strict or too permissive, enforcement concerns, or gaps in the policy:

* Discuss on the [#strimzi channel on CNCF Slack](https://slack.cncf.io/)
* Raise topics on the [Strimzi Dev mailing list](https://lists.cncf.io/g/cncf-strimzi-dev/topics)

## References

This policy was inspired by the [CNCF AI Policy for Projects discussion](https://github.com/cncf/foundation/issues/1285).

* [ASF Generative Tooling Guidance](https://www.apache.org/legal/generative-tooling.html)
* [CNCF / Linux Foundation: Guidance Regarding Use of Generative AI Tools for Open Source Software Development](https://www.linuxfoundation.org/legal/generative-ai)
* [Kyverno AI Usage Policy](https://github.com/kyverno/community/blob/main/AI_USAGE_POLICY.md)
* [KubeVirt AI Contribution Policy](https://github.com/kubevirt/community/blob/main/ai-contribution-policy.md)
