# Contributing Guidelines

Thank you for your interest in contributing to this repository. We welcome and appreciate your contributions, whether it is code, documentation, data, or feedback.

Please read this document carefully before making any contributions. It contains important information about the project's goals, standards, and guidelines.

## Code of Conduct

We expect all contributors to follow our [code of conduct](link to code of conduct). Please report any unacceptable behavior to the project maintainer.

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
3. Make your changes in your branch and commit them with a meaningful message. Follow the [commit message guidelines](link to commit message guidelines).
4. Push your branch to your forked repository and create a pull request to the main branch of the original repository. Reference the issue number in your pull request description and explain what your changes do and why they are needed.
5. Wait for the project maintainer or other contributors to review your pull request and provide feedback. Address any comments or requests for changes and update your pull request accordingly.
6. Once your pull request is approved and merged, delete your branch and update your local and forked repositories.

<<<<<<< HEAD
### Raising Issues

If there are any issues, new features, or bugs found, you may raise an issue found in the [issues](link-here) page. However, you may have to consider the following before making an issue.

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

=======
>>>>>>> 56e846ccdbdfad128e09cd1cab9a7af8835a1853
## Project Structure

This project follows a standard data science project structure, as described below:

- `data`: This folder contains the raw and processed data files used for analysis and modeling. Do not upload any sensitive or confidential data to this folder.
- `notebooks`: This folder contains the Jupyter notebooks that perform data exploration, analysis, visualization, and modeling. Each notebook should have a clear title and purpose, and follow the [notebook style guide](link to notebook style guide).
- `scripts`: This folder contains the Python scripts that automate data processing, model training, testing, and evaluation. Each script should have a clear name and function, and follow the [script style guide](link to script style guide).
- `models`: This folder contains the trained and saved models, as well as any model artifacts such as weights, parameters, or metadata. Each model file should have a clear name and description.
- `reports`: This folder contains the reports or presentations that summarize the results and findings of the project. Each report file should have a clear name and format.
- `requirements.txt`: This file lists the Python packages and dependencies required to run the project. Use `pip install -r requirements.txt` to install them.

<<<<<<< HEAD
=======
## Coding Standards

We follow the [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide for Python code formatting and naming conventions. We also use [black](https://github.com/psf/black) as our code formatter and [flake8](https://flake8.pycqa.org/en/latest/) as our code linter.

Please make sure your code is formatted and linted before submitting a pull request. You can use the following commands to do so:

```bash
# Format code with black
black .

# Lint code with flake8
flake8 .
```

We also use [docstrings](https://www.python.org/dev/peps/pep-0257/) to document our code and functions. We follow the [Google style](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html) for docstrings.

Please make sure your code is documented before submitting a pull request. You can use the following command to check your docstrings:

```bash
# Check docstrings with pydocstyle
pydocstyle .
```

## Testing

We use [pytest](https://docs.pytest.org/en/stable/) as our testing framework for Python code. We write unit tests for our functions and classes, as well as integration tests for our scripts and notebooks.

Please make sure your code is

## Testing

We use [pytest](https://docs.pytest.org/en/stable/) as our testing framework for Python code. We write unit tests for our functions and classes, as well as integration tests for our scripts and notebooks.

Please make sure your code is tested before submitting a pull request. You can use the following command to run the tests:

```bash
# Run tests with pytest
pytest .
```
>>>>>>> 56e846ccdbdfad128e09cd1cab9a7af8835a1853

```bash
# Run tests with pytest
pytest .
```