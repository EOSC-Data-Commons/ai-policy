# EOSC-data-commons generative AI / LLM policy

EOSC Data Commons (abbr "EDC" below) supports the establishment of EOSC as a trusted European Research Commons.[1]
One of the major goals of the project is to provide an AI-based analytics metadata warehouse and discovery service. However, the AI usage in the development of the platform requires clarification to assure the quality of the project and the code base maintained in the project.

This AI / LLM policy guides the usage of AI / LLM tools and models within the project development tasks.

The goals of the policy are the following (with priorities from high to low):
- Ensure the quality of infrastractures that running the platform, include the robustness and the maintainability.
- Ensure the quality of code bases produced in the project, ensuring review efficiency and code base accuracy.
- Accelerate the development pace.

This AI policy applies to *all* the EOSC-data-commons GitHub organisation repositories unless explicitly overriden in 
ther CONTRIBUTING.md file.

## Overview 

By submitting a pull request, you certify that:

- You are the author of the contribution or have the legal right to submit it.
- You either hold the copyright to the changes or have explicit legal authorization to contribute them under this project's license.
- You understand the code.
- You accept full responsibility for AI-assisted coding.

## Dimensions 

Following the open-source-ai-contribution-policies[1] dimensions:

- AI/LLMs contributions are ALLOWED (either in code generation or code review).
- You MUST disclose if AL/LLMs were used to generate or review the code.
- Code MUST comply with the repository license (see section "Legal")
- The human in the loop MUST understand the code. You MUST be able to explain what your changes do and how they interact with the greater system without the aid of AI/LLMs. Fully unsupervised agentic tools like OpenClaw are NOT ALLOWED

All contributions are subject to code reviews. Whenever a human reviews the code, we expect you to engange with reviewers and that you don't impose unfair load on them with low-quality code or code that you don't fully understand and can't explain to a reviewer.

To avoid reviewers burden due to limited human cognitive load:
- pull requests MUST have a single, clear scope 
- pull request SHOULD NOT have more than 2,000 lines of code change
- pull request SHOULD NOT have more than 10 files of changes

Those are no hard limits but any AI/LLMs generated contribution may be rejected if not within them.

Disclosure of AI/LLMs usage for a contribution MUST be detailed in your pull request with:
- A description of the model and version used
- A description of the prompt used for code generation/review

The AI generated plans from coding agents SHOULD NOT be included in the pull request. (BUT it is allowed to be as a dedicated pull request to only include the AI design plan for iterates on design) 

## Legal

There is ongoing legal uncertainty regarding the copyright status of LLM-generated works and their provenance.
Because of this, allowing contributions by LLMs has unpredictable consequences for the copyright status of this project – even when leaving aside possible copyright violations due to plagiarism.


## References
[1] https://www.eosc-data-commons.eu/about
[2] https://github.com/melissawm/open-source-ai-contribution-policies
[3] https://forge.rust-lang.org/policies/llm-usage.html
[4] https://github.com/pypa/pip/blob/main/AI_POLICY.md
[5] https://docs.scipy.org/doc/scipy//dev/conduct/ai_policy.html
[6] https://blog.scientific-python.org/scientific-python/community-considerations-around-ai/
