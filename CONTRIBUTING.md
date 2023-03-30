# Contributing Guidelines

Thank you for your interest in contributing to this repository. We welcome and appreciate your contributions, whether it is code, documentation, data, or feedback.

Please read this document carefully before making any contributions. It contains important information about the project's goals, standards, and guidelines.

## Code of Conduct

We expect all contributors to follow our [code of conduct](CODE_OF_CONDUCT.md). Please report any unacceptable behavior to the project maintainer.

## How to Contribute

There are many ways you can contribute to this project, such as:

- Reporting issues or bugs
- Suggesting new features or enhancements
- Submitting pull requests with code changes
- Reviewing and testing existing code
- Writing or updating documentation
- Sharing data or resources
- Providing feedback or suggestions

Please follow these steps to make a contribution:

1. Check the [issues](link to issues) page to see if there is an existing issue related to your contribution. If not, create a new issue and describe your contribution clearly and concisely.
2. Fork the repository and create a new branch from the main branch. Name your branch according to the following convention: `feature/your-feature-name` or `bugfix/your-bugfix-name`.
3. Make your changes in your branch and commit them with a meaningful message. Follow the [commit message guidelines](#commit-message-guidelines).
4. Push your branch to your forked repository and create a pull request to the main branch of the original repository. Reference the issue number in your pull request description and explain what your changes do and why they are needed.
5. Wait for the project maintainer or other contributors to review your pull request and provide feedback. Address any comments or requests for changes and update your pull request accordingly.
6. Once your pull request is approved and merged, delete your branch and update your local and forked repositories.

### Project Structure

This project follows a standard data science project structure, as described below:

- `docs`: This folder contains the task and project documentation, such as the project proposal, project plan, and final report. Each document should have a clear name and purpose.
- `data`: This folder contains the raw and processed data files used for analysis and modeling. Do not upload any sensitive or confidential data to this folder.
- `notebooks`: This folder contains the Jupyter notebooks that perform data exploration, analysis, visualization, and modeling. Each notebook should have a clear title and purpose.
- `scripts`: This folder contains the Python scripts that automate data processing, model training, testing, and evaluation. Each script should have a clear name and function.
- `models`: This folder contains the trained and saved models, as well as any model artifacts such as weights, parameters, or metadata. Each model file should have a clear name and description.
- `reports`: This folder contains the reports or presentations that summarize the results and findings of the project. Each report file should have a clear name and format.
- `requirements.txt`: This file lists the Python packages and dependencies required to run the project. Use `pip install -r requirements.txt` to install them.

### Raising Issues

If there are any issues, new features, or bugs found, you may raise an issue found in the [issues](link to issues) page. However, you may have to consider the following before making an issue.

1. Make sure that your issue is unique and was not raised before. You might want to search for existing or closed issues that might solve the problem. Duplicated issues would be closed for housekeeping purposes.
2. Check if your current commit is the updated commit. There might be changes or updates that were updated in the latest commits or pull requests.
3. Be concise about your proposed feature or bugs found. Provide logs or any helpful details that might be helpful to reproduce the bug, or prospects of implementing a new feature and if such feature is feasible.
4. Keep in mind about the main objectives of the project. It is generally useful if issues provided would be crucial for achieving the necessary objectives.
5. Don't get intimidated. We're here to help you grow further by giving constructive remarks and comments about your proposed issue or bug. This would be beneficial to you in the future by raising good issues.

### Creating Pull Requests

When creating pull requests, it is generally acceptable to make pull requests that closes a particular issue. In this repository, there's a particular system of creating pull requests from a feature branch that closes a particular issue and it is as follows:

1. The feature branch is only addressing only one issue. If two similar issues are present, it may be resolved in one pull requests. You may use the [closing keywords](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) that automatically links an issue to your particular pull request.
2. There are chances that your changes would require multiple revisions before having it into a mergeable state. People assigned to review your code would verify your code to avoid further issues.
3. The topic branch should branch off from the main branch that tackles in addressing a particular issue. **Make sure that you're not pushing from the main branch** by checking your current branch from time to time.
4. Be patient when asking for review. Someone would review your pull request eventually.

### Commit Message Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification for our commit messages. This helps us to maintain a consistent and readable commit history, as well as to generate changelogs and release notes automatically.

A conventional commit message has the following structure:

```
<type>(optional scope): <description>

(optional body)

(optional footer(s))
```

- `<type>`: A word that indicates the kind of change that the commit introduces, such as `feat`, `fix`, `docs`, `test`, etc. See the [list of types](#types) below for more details.
- `(optional scope)`: An optional word or phrase that specifies the scope of the change, such as `api`, `ui`, `core`, etc. The scope should be lowercase and use hyphens to separate words.
- `<description>`: A concise summary of the change in the present tense and imperative mood, such as "add new feature", "fix bug", "update documentation", etc. The description should start with a lowercase letter and end with a period.
- `(optional body)`: An optional paragraph or paragraphs that provide more details about the change, such as the motivation, rationale, design decisions, trade-offs, etc. The body should be separated from the description by a blank line and wrap at 72 characters.
- `(optional footer(s))`: An optional section or sections that provide additional information or references related to the change, such as issue numbers, breaking changes, co-authors, acknowledgments, etc. The footer should be separated from the body by a blank line and use a keyword followed by a colon and a space, such as "Fixes: #123", "BREAKING CHANGE: new API", "Co-authored-by: John Doe <john.doe@example.com>", etc.

#### Types

The following is a list of common types that we use for our commit messages, along with their meanings and examples:

- `feat`: A new feature or functionality for the user or the system. Example: `feat(api): add new endpoint for user registration`.
- `fix`: A bug fix or a correction of an error or defect. Example: `fix(ui): fix broken layout on mobile devices`.
- `docs`: A change or addition to the documentation. Example: `docs: update README.md with installation instructions`.
- `test`: A change or addition to the tests or testing tools. Example: `test: add unit test for new feature`.
- `refactor`: A change that improves the code quality or structure without changing its behavior or functionality. Example: `refactor(core): extract common logic into a helper function`.
- `style`: A change that affects the code style or formatting without changing its meaning or functionality. Example: `style: apply black code formatter`.
- `perf`: A change that improves the performance or efficiency of the code or system. Example: `perf(core): optimize database query`.
- `build`: A change that affects the build system or external dependencies. Example: `build: upgrade to Python 3.9`.
- `ci`: A change that affects the continuous integration or delivery system or configuration. Example: `ci: add GitHub Actions workflow`.
- `chore`: A change that does not fit into any of the above types or that does not affect the code or system. Example: `chore: update .gitignore file`.

#### Examples

Here are some examples of good and bad commit messages:

Good:

```
feat(ui): add dark mode toggle

Add a button in the settings page that allows the user to switch between light and dark mode.

Closes #456
```

Bad:

```
added dark mode
```

Good:

```
fix(api): handle invalid input gracefully

Return a 400 Bad Request response instead of raising an exception when the input is invalid.

Fixes #789
```

Bad:

```
fixed bug
```
