
# AI Contributions

AI usage is causing challenges for all open source projects, and thus also for OpenCloud.
This document defines guidelines regarding how we work with AI and how we ask contributors to work with it. 

This is done to protect OpenCloud, especially with regards to the following points: 

1. **Code Quality**: OpenCloud has a strong focus on code quality as we know that dealing with user data comes with a great responsibility for data security. All contributions have to put that first.
2. **Focus**: OpenCloud serves a specific purpose which is defined very carefully by product management. All contributions have to align with that roadmap.
3. **Maintainability**: All contributions must be as "consumable" as ever possible since all contributions will be reviewed. Also, code that is written today needs to be maintained tomorrow.   
5. **Human centric**: The most valuable resource is the time of human maintainers. That must be used carefully.

These points can be summarized in a fundamental principle for OpenCloud in relation to AI:

>*OpenCloud is a project driven by responsible individuals. Despite all concerns regarding the multifaceted impacts of AI on society and its implications for the free software movement, we are committed to taking a positive view of the use of AI as a tool to accelerate and optimize our work. However, we expect that human work habits and processes will always take precedence. A person must be held accountable for every contribution.*

Requirements are further specified below. Contributions that do not comply with these requirements will be rejected without further discussion.

## Fit to the Project

Before submitting a PR to any repository of OpenCloud, think about its size and fit to the project. That is a major factor on how careful the PR needs to be prepared and how maintainers look at it.

### Bug Fixes
Bug fixes in form of "one-liners", typo fixes, fixes to translations and such are always very appreciated. Never think "that is too trivial to submit", it is not.

### Refactorings
Bigger changes that fix misbehaviour, refactor parts of the codebase are also appreciated, but be careful. Have tests and keep changes small. Possibly ask before submitting what the maintainers think of your idea.

### Feature Additions
Yes, we love it, but we also apply the rules here, as we take the responsibility to maintain code that we include into the project. Try to structure the changes you plan into multiple steps to make it easier to understand and review. Try to consider alternatives and document your decisions (ADR).

Most important: make sure to talk before you invest work and tokens. There is a chance that we will not take your contribution even if it is formally great because it does not fit the roadmap.

### "Scratch your itch"
"Scratching your own itch" and pushing the results upstream is in general a great motivation to contribute to open source projects. OpenCloud supports that idea. 
However, we have to keep the main direction of the project in mind, so we can not accept every "special purpose" feature.

Make sure to find a balance between functions that are good for everybody and your own needs. You will have to keep private patches for some of your additions. OpenCloud comes with a [web extension system](https://docs.opencloud.eu/de/docs/dev/web/extension-system/) to make independently maintained extensions easy.

## Pull Requests

Contributions to any part of the project are highly appreciated. To submit a contribution via Github pull requests, the following points need to be considered:

1. YOU are responsible for what you submit, not your agent. Make sure you completely understand what you submit. Be able to answer questions. Be open about the way you use AI. 
2. Keep PRs short. The shorter the better, as that is easier for humans. Split code contributions to multiple PRs (e.g. separate refactors from changes introducing new features). Invest time in finding logical portions of bigger contributions and reference the PRs accordingly.
3. Authorship is for humans, not tools. Code assistants and such should not be described in commits using tags like "Co-authored-by" or similar. Nor must they be listed as primary author. 
4. Be sensitive about others time. Review AI generated texts to be **human friendly**: Keep descriptions short and concise. Separate important things from details and verify with your own understanding. Another person should understand your idea instantly. For example, consider splitting your comments to a summary on top and detailed description below.
5. Check your contribution: Review your AI generated PR carefully before submitting it. Abstain from copy & paste. It is YOU who submits it, not an AI. Maintain your contributor reputation.
6. Add useful comments, tests and documentation additions to your contribution. AI can be a great help for that.

These rules are mostly soft. But maintainership considers to put hard limits behind some of them in the CI which results in automatic decline of PRs in Github.

## Human interaction

OpenCloud is and will be a human driven project. Keep that in mind with every contribution and interaction. Besides a friendly and patient attitude, a human friendly style of communication and working is expected.

1. Ask questions early. It is easier to answer a question that clarifies things than declining a PR that does not fit.
2. Be responsive. If maintainers have questions, please be responsive.
3. Be precise. Try to stick to the topic and answer questions carefully.
4. Try to act sustainable: Bigger one-off contributions are of limited use. Taking responsibility to improve and maintain a contribution over time is very appreciated.

Please help us to refine these guidelines by submitting a PR.
