# PR Guidelines

Making your PR stand-out.

This guide supports the [PR Template](./.github/pull_request_template.md) used for all DeepX repositories.

Having a readable PR is critical to speed-up reviewing and support future readers.

As a reviewer, please ask for the template to be filled.

## PR Metadata

Setting PR metadata:

- Title:
    - Provide a short summary of the PR changes.
    - Do not include the clickup ID in the title.
- Assignees:
    - Assign yourself and other direct collaborators.
- Type:
    - Create the PR as a draft.
    - Only set it to non-draft when it is ready to be reviewed. Avoid spam.
- Reviewers:
    - Only assign reviewers when the PR is ready to be reviewed. Avoid spam.
- Labels:
    - Make wise use of the labels.
    - In particular, remember to tag `breaking` changes or PRs to `do not merge`.

## PR Description

### Description

Describe your changes in detail.

If the description gets too big, you can use H4 subsections `####`.

Remember to mention other relevant PRs.
- For example, PRs that this one depends on.
- When mentioning PRs, we recommend using the following format: `- #123` in a new line. This will expand the PR to show its title and status. For example:
- #3

### Motivation and Context

Explain why this change is required and what problem it solves.

### How Has This Been Tested?

Describe in detail how you tested your changes.

Reviewers can use this to try the changes locally.

#### Pro-Tip: Create a checklist of validations

This will help you keep track of pending validations, and will reassure the reviewer that you actually performed those.

For example:
- [x] Verify that all markdown links work. 
- [x] Verify that the system builds.
- [ ] Verify with Acceptance Test suite locally.

#### Pro-Tip: Use code-snippets to show how you tested it

I verified that the system works by running this test:
```bash
cd /root/code/tests/
pytest-3 test_my_library.py
```

Use [syntax highlighting](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks#syntax-highlighting) for the [available languages](https://github.com/github-linguist/linguist/blob/master/lib/linguist/languages.yml).
