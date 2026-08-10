
# AI Assisted Contributions

AI usage is causing challenges for all open source projects, and thus also for OpenCloud.
This document defines guidelines regarding how we work with AI and how we ask contributors to work with it. 

This is done to protect OpenCloud, especially with regards to the following points: 

1. **Code Quality**: OpenCloud has a strong focus on code quality as we know that dealing with user data comes with a great responsibility for data security. All contributions have to put that first.
2. **Focus**: OpenCloud serves a specific purpose which is defined very carefully by product management. All contributions have to align with that roadmap.
3. **Maintainability**: All contributions must be as "consumable" as ever possible since all contributions will be reviewed. Also, code that is written today needs to be maintained tomorrow.   
5. **Human centric**: The most valuable resource is the time of human maintainers. That must be used carefully.

These points can be summarized in a fundamental principle for OpenCloud in relation to AI:

>*OpenCloud is a project driven by responsible individuals. Despite all concerns regarding the multifaceted impacts of AI on society and its implications for the free software movement, we are committed to taking a positive view of the use of AI as a tool to accelerate and optimize our work. However, we expect that human work habits and processes will always take precedence. A person must be held accountable for every contribution.*

Requirements are further specified below. Contributions to any part of the project are highly appreciated, but those that do not comply with these requirements can be rejected without further discussion.

## Issues

If you use AI to create issue reports, it is important to keep in mind that there is a human supposed to read it. People are easily overloaded by details, which quickly renders the generated issue completely useless.

To avoid that, make sure to remember the following AI specific rules:

* Keep issue reports short. Avoid details that are not important to fix the specific problem.
* Separate details from the the issue overview.
* Be exact and avoid unspecific information.

Always work through a generated text before using it as issue report.

## Pull Requests

To submit a contribution via Github pull requests, the following points need to be considered:

1. YOU are responsible for what you submit, not your agent. Make sure you completely understand what you submit. Be able to answer questions. Declare which AI you used to assist you, and how you used it. Be aware of potential licensing- and copyright issues AI generated code can inject.
2. Keep PRs short. The shorter the better, as that is easier for humans. Split code contributions to multiple PRs (e.g. separate refactors from changes introducing new features). Invest time in finding logical portions of bigger contributions and reference the PRs accordingly.
3. Authorship is for humans, not tools. Code assistants should not be described in commits using tags like "Co-authored-by" or similar. Nor must they be listed as primary author.
4. Be sensitive about others time. Review AI generated texts to be **human friendly**: Keep descriptions short and concise. Separate important things from details and verify with your own understanding. Another person should understand your idea instantly. For example, consider splitting your comments to a summary on top and detailed description below. Beware that generated text are often long and unspecific.
5. Check your contribution: Review your AI generated PR carefully before submitting it. Abstain from copy & paste. It is YOU who submits it. Maintain your contributor reputation. Never submit generated code that you do not understand or you disagree with.

### Attribution

When AI tools contribute, proper attribution helps track the evolving role of AI in the development process. Inspired by the guidelines [described in the Linux kernel docs](https://docs.kernel.org/process/coding-assistants.html), contributions should include an `Assisted-by` tag in the following format:

`Assisted-by: AGENT_NAME:MODEL_VERSION [TOOL1] [TOOL2]`

- `AGENT_NAME` is the name of the AI tool or framework
- `MODEL_VERSION` is the specific model version used
- `[TOOL1] [TOOL2]` are optional specialized analysis tools used

### Enforcement

These rules are mostly soft, and the whole topic is still floating. But maintainership considers to put hard limits behind some of them in the CI which results in automatic decline of PRs in Github.

## Human interaction

OpenCloud is and will be a human driven project. Keep that in mind with every contribution and interaction. Besides a friendly and patient attitude, a human friendly style of communication and working is expected.

1. Ask questions early. It is easier to answer a question that clarifies things than declining a PR that does not fit.
2. Be responsive. If maintainers have questions, please be responsive.
3. Be precise. Try to stick to the topic and answer questions carefully.
4. Try to act sustainable: Bigger one-off contributions are of limited use. Taking responsibility to improve and maintain a contribution over time is very appreciated.

Please help us to refine these guidelines by submitting a PR.
