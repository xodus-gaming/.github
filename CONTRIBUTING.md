## Xodus Contributing Guidelines

We're really happy you are reading this, we always need new contributions in the Xodus project.

Below you'll find a list of topics to consider before you submit your first contribution to any of `xodus-gaming` projects.

#### Found a bug? Have a feature idea?

- Make sure similar topic was not already reported by searching on GitHub under `Issues` [(more about issues)](https://docs.github.com/en/issues)
- If you're unable to find an open issue referring to the problem/feature idea, **open a new one**. Make sure to include a title and a clear description, with as much information as possible. e.g steps to reproduce, crash log, expected behavior.
- Try to use an issue template form that best fits the problem category - if you were given a choice during issue submission.


#### Intending to write a code patch?

- Let us know what do you intend to work on via [Discord](https://discord.gg/ZG774FK4tq) or discussion in a GitHub issue. We want to avoid duplicated efforts, as well as ensure progress and assignee is properly reflected in the issue state.
- Follow our [LLM use guidelines](#llm-use-guidelines)
- Ensure all tests still succeed after your changes, add new if applicable
- Submit a patch by creating a [Pull Request](https://docs.github.com/en/pull-requests/how-tos/create-pull-requests/creating-a-pull-request)
- Write/update documentation if applicable
- Ensure the PR description clearly describes the problem and the solution. Include the relevant GitHub issue number
- Iterate on the PR together with reviewers. Resolve all change requests and discussions before we proceed


### LLM use guidelines

We recognize LLMs (commonly called "AI" as speech mannerism) becoming part of the modern developer experience. However, given the sensitiveness of the project, and the main axis being directed on reverse engineering, we are forced to impose certain rules and limits as to where LLMs are acceptable, especially repositories that have a chance of bringing the code upstream, where similar rules are already in place.

- Reverse engineering efforts driven by LLM are not allowed
- LLM assisted code will be rejected from most repositories - see [Wine Clean Room Guidelines](https://gitlab.winehq.org/wine/wine/-/wikis/Clean-Room-Guidelines/)
  - With the exception of parts of `xodus-gaming/xodus` that don't interact with Microsoft or XBOX services. Code quality and performance improvements not impacting api layer logic are welcome.
- Ensure any comments in code are where actually needed, e.g counter intuitive approach to a problem. Avoid X not Y patterns
- Please do not write tests to a point that it becomes irrelevant. Stay minimalistic, and only cover what's needed
- Use of LLMs is welcome for documentation related tasks
  - Proofreading new documentation additions for grammar mistakes, inconsistencies and other issues. Especially if English is not your native language.
  - Browsing documentation, ask your LLM to read docs and help you navigate given concept
