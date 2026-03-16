# Strimzi AI Usage Policy

> [!NOTE]
> **AI is welcome. Humans are responsible.**

AI tools are useful coding assistants, but contributors are fully responsible for the correctness, testing, and licensing compliance of all submissions.
Disclosure ensures accountability and helps maintain the integrity of the project's Apache 2.0 licensing as copyright law around AI-generated content evolves.

## General Guidelines

1. Contributors are fully responsible for all submissions (i.e., PRs, issues, comments) or any other engagement.
2. Contributors using AI should:
   * Thoroughly review and understand all AI-generated content before submission
   * Refine AI output to meet project quality standards and take full ownership
   * Ensure content does not violate copyright or other laws
3. PRs with AI-generated code can only target accepted issues (i.e., not labeled as `triage`).

> [!IMPORTANT]
> Contributors SHOULD disclose any substantial use of AI via a commit trailer attributing the tool used.
> Acceptable formats include:
> * `Assisted-by: Claude <noreply@anthropic.com>`
> * `Co-authored-by: Claude <noreply@anthropic.com>`
> * `Generated-by: Claude <noreply@anthropic.com>`
>
> Many AI coding tools automatically add `Co-authored-by` trailers (i.e., this is acceptable).

## Legal and Licensing Considerations

Strimzi is licensed under the Apache License 2.0.
In line with [ASF guidance on generative tooling](https://www.apache.org/legal/generative-tooling.html), contributors using AI tools must ensure that:
* The AI tools terms of use are consistent with the [Open Source Definition](https://opensource.org/osd)
* AI-generated output either is not copyrightable, contains no third-party copyrighted materials, or any included materials are licensed compatibly with Apache 2.0
* All third-party content is properly attributed
* The [Developer Certificate of Origin (DCO)](https://developercertificate.org/) can be truthfully signed

These requirements apply equally to code and documentation.

> [!WARNING]
> Contributors must also comply with their employer's policies regarding AI-assisted open source work.

## Policy Evolution

This policy will be reviewed as needed to reflect changes in AI tooling, legal developments, community feedback, and evolving CNCF best practices.

## Questions and Feedback

* Discuss on the [#strimzi channel on CNCF Slack](https://slack.cncf.io/)
* Raise topics on the [Strimzi Dev mailing list](https://lists.cncf.io/g/cncf-strimzi-dev/topics)

## References

This policy was inspired by the [CNCF AI Policy for Projects discussion](https://github.com/cncf/foundation/issues/1285).

* [ASF Generative Tooling Guidance](https://www.apache.org/legal/generative-tooling.html)
* [CNCF / Linux Foundation: Guidance on AI Tools for OSS Development](https://www.linuxfoundation.org/legal/generative-ai)
* [Kyverno AI Usage Policy](https://github.com/kyverno/community/blob/main/AI_USAGE_POLICY.md)
* [KubeVirt AI Contribution Policy](https://github.com/kubevirt/community/blob/main/ai-contribution-policy.md)
