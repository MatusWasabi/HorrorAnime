# HorrorAnime

Developed with Unreal Engine 5

# Quality control Strategy (Prototyping phase)

The below documentation will be about how we will control quality of project.

**This strategy is only for prototyping phase.**

In other phase, the strategy will be more strict to smoothen development.

## Branching

For now, we will separate them with developer name.

Main branch will be used for building game only.

Things that will be inside main branch must be tested and/or documented to ensure collaborating tasks.

And it must be merged into only by approved merge request from sub-branch only.

## Convention

This will be convention that we will use early on. If you found any assets that do not match the following convention.

It is encouraged to rename them. Help the team enforce it to make clean project!!!

[Official Convention](https://dev.epicgames.com/documentation/en-us/unreal-engine/recommended-asset-naming-conventions-in-unreal-engine-projects)

If you have not found any convention, you can create one here.

## Code Review

### Focus Area

- Functionality: Ensure the feature or fix works as intended and does not introduce major bugs.
- Readability: Check for clear and understandable code. It should be easy for another developer (or yourself in the future) to read and follow. (Most important)
- Consistency: Ensure consistency in naming conventions, indentation, and overall code style. (This will be relaxed for now)

### Review Process

- Pull Requests (PRs): Always open a PR when submitting code. Even if the review is minimal, it helps track changes and gives a place for discussion.
- Self-Review: Before requesting a review, perform a quick self-review to catch obvious errors or issues.
- Review Duration: Limit review time to a maximum of 30 minutes to keep it lightweight and focused on key points.

### Feedback Guidelines

- Provide feedback on major issues first (e.g., incorrect logic, breaking functionality).
- Address minor suggestions (e.g., style tweaks or optimizations) only if they are easy to fix and don’t require much time.
- Ask for clarifications or explanations if something is unclear, especially when dealing with temporary or experimental code.
- Keep feedback constructive and focused on improving the code. Avoid micromanaging.

## Documentation

The documentations will be created in 2 main circumstances.

1. Code review and reviewer request for documentation. In this case, the owner (reviewee) must provided atleast 50 words of mark down inside that folder. The detail must include provided question by reviewer and rationale of reviewee behind the solutions.

2. Questioning code after review, when one has question about a code, the owner must answer the question regardless. And the asker will be responsible for noting down their own questions in the document. To ensure, people who reads the code later won't need to ask the same question again.
