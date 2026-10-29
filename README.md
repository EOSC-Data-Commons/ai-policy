# EOSC-data-commons generative AI / LLM policy

EOSC-data-commons (abbr "EDC" below) is to support the establishment of EOSC as a trusted European Research Commons.[1]
Bring the AI-based analytics metadata warehousce and discovery service is one of the major goals of the project but in the development of the platform the AI usage requires clarification to assure the quality of the project and the code base maintained in the project.
It comes with this AI / LLM policy to guide the usage of AI / LLM tools and models.

The goals of the policy are the following (with priorities from high to low):
- Ensure the quality of infrastractures that running the platform, include the robustness and the maintainability.
- Ensure the quality of code bases produced in the project.
- Introduce a guideline that developers of the project can follow to minimize the confrontations between the teams.
- Accelerate the development pace.

If no repositories scope AI-policy is applied, code bases under EOSC-data-common organization inherit the (THIS) AI-policy.
The AI-policy from repositories can override items from this policy but if not mentioned, this policy has strong effect to impose the guidance.

## Dimensions

We extend the details of classifiations columns from open-source-ai-contribution-policies[1] into detail list to fit EDC.
The original dimentions are: 
- AI/LLMs allowed?
- Disclosure required?
- Policy includes copyright statement? (see section "Legal")
- Requires human in the loop?

We extend then into:
- (?) AI/LLMs NOT allowed to generate code in PR ; (AT THE SAME TIME) ; AI/LLMs allowed to review this PR
- (?) AI/LLMs allowed to generate code in PR ; (AT THE SAME TIME) ; AI/LLMs NOT allowed to review this PR
- (?) either above or "requires no human in the loop".

- (?) The AI generated plans from coding agents should not be include in the PR. (BUT it is allowed to be as a dedicated PR to only include the AI design plan for iterates on design) 
- (?) Every contribution has to be backed by a human who unequivocally owns the copyright for all changes.
    -> No LLM bots in `Co-authored-by:`s.
- (-) Absolutely no unsupervised agentic tools like OpenClaw.
- (?) If the AI is used for a PR of for part of the code, disclosure required.
    - (?) You must include a paragraph in your submission describing how you utilized them to ensure transparency about AI's role in your work. 
    - include which AI model and version are used.

By submitting a pull request, you certify that:

- You are the author of the contribution or have the legal right to submit it.
- You either hold the copyright to the changes or have explicit legal authorization to contribute them under this project's license.
- You understand the code.
- You accept full responsibility for it.


## Legal

There is ongoing legal uncertainty regarding the copyright status of LLM-generated works and their provenance.
Because of this, allowing contributions by LLMs has unpredictable consequences for the copyright status of this project – even when leaving aside possible copyright violations due to plagiarism.


## References
[1] https://www.eosc-data-commons.eu/about
[1] https://github.com/melissawm/open-source-ai-contribution-policies
[1] https://forge.rust-lang.org/policies/llm-usage.html
[1] https://github.com/pypa/pip/blob/main/AI_POLICY.md
[1] https://docs.scipy.org/doc/scipy//dev/conduct/ai_policy.html
[1] https://blog.scientific-python.org/scientific-python/community-considerations-around-ai/
