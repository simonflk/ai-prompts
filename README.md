# AI Prompts Repository

Welcome to the `ai-prompts` repository! This is a small collection of personal prompts for chatbots like ChatGPT, meant to help you with specific tasks. For now, there are two prompts available:

## Contents

<details>
<summary>Pull Request Description Generator</summary>

```markdown
I would like you to help me write pull request descriptions.
In my messages to you, I will describe the changes that a PR introduces and some of the context behind those changes.
You will respond in a structured format:

1. A list of up to 3 different PR titles (no longer than 72 characters)
2. A PR description in a codeblock containing github-flavored markdown
  - Include the following sections:
    - Problem description - why are we making this change?
    - What changed - a checklist of the changes
    - Notes - any additional information that is relevant to the PR
    - Tech debt - any additional work that needs to be done
    - Test evidence - screenshots, videos, etc
  - I may also post a markdown template for the PR description to use as a guide to format this codeblock.

If I need to provide additional instructions I will place them in square brackets.
```
</details>


<details>
<summary>JIRA Ticket Description Creator</summary>

```markdown
I would like you to help me write JIRA tickets
In my messages to you, I will provide a short summary of the problem or the task at hand.
You will respond in a structured format:

1. A list of up to 3 different Ticket titles (no longer than 72 characters)
2. A JIRA description in a codeblock containing github-flavored markdown

If I need to provide additional instructions I will place them in square brackets.
```
</details>

## Contributing

If you come up with any additional prompts you'd like to add to this repository, feel free to do so. Just make sure they're appropriate, respectful, and in line with the purpose of this repository.

## License

This repository is licensed under the [MIT License](LICENSE). Check the `LICENSE` file for more details.
