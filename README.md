# Title of the Project

Description of the project, this serve as a guide for the user to understand what the project is about.

## Objective
Objective of the project, this serve as a guide for the user to understand what the project is trying to achieve.

## Tech Stack Used
![Jupyter Notebook](https://img.shields.io/badge/-Jupyter%203-%232c3e50?style=for-the-badge&logo=Jupyter)
![Python](https://img.shields.io/badge/-Python%203-%232c3e50?style=for-the-badge&logo=Python)

## Prerequisites

- [Python 3](https://www.python.org/downloads/)
- [GIT](https://git-scm.com/downloads)
- Packages in [`requirements.txt`](requirements.txt)


## Configuring your workspace
1. Open a terminal *(CMD/Bash/Powershell/ZSH/etc)*
2. Check if both python and pip is installed by typing `python --version` and `pip version`. Alternatively if this doesn't work type `python3 --version` and `pip3 --version`.
3. Go to the directory/folder where you clone the project, and open it with your favorite code editor (preferably VS Code, but Jupyter Notebook will work as well).
4. Open a terminal on the same directory of your project and create a virtual environment by typing `python -m venv <env_name>`.
   **Example:** 
   ```bash
   python -m venv venv
    ```
5. Activate your environment by using the following:
    - **Powershell/CMD:** 
    Format: `<env_name>\Scripts\activate`, 
    **Example:**
        ```powershell
        venv\Scripts\activate
        ```
    - **Bash/ZSH/Fish:**  
<<<<<<< HEAD

        ```bash
        # source ./<env_name>/bin/activate
        
=======
    Format: `source ./<env_name>/bin/activate`, 
    **Example:** 
        ```bash
>>>>>>> 56e846ccdbdfad128e09cd1cab9a7af8835a1853
        source ./venv/bin/activate
        ```
6. Install the requirements by typing 
   ```bash
   pip install -r requirements.txt
   ```
   alternatively, if this doesn't work type
    ```bash
    pip3 install -r requirements.txt
    ```
7. Run `main.ipynb` using the **venv** as ipykernel.

<<<<<<< HEAD
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

Please make sure your code is tested before submitting a pull request. You can use the following command to run the tests:

```bash
# Run tests with pytest
pytest .
```

=======
>>>>>>> 56e846ccdbdfad128e09cd1cab9a7af8835a1853
## Contributing Guidelines

To contribute to the repository through Issues or Pull Requests, see [`CONTRIBUTING.md`](CONTRIBUTING.md).


<!-- Fix this base on your contact details -->

## Contact 
<a href="https://twitter.com/intent/follow?screen_name=scaredmeow_&tw_p=followbutton">
  <img src="https://img.shields.io/twitter/follow/scaredmeow_?label=Twitter&style=social" alt="github">
</a>
<a href="https://www.linkedin.com/in/neilriego/">
  <img src="https://img.shields.io/badge/- -%232c3e50?label=LinkedIn&style=social&logo=linkedin" alt="linkedin">
</a>
<a href="mailto:neilchristianriego3@gmail.com">
  <img src="https://img.shields.io/badge/- -%232c3e50?label=Email&style=social&logo=gmail" alt="gmail">
</a>
<a href="https://calendly.com/neilriego/book-a-meeting">
  <img src="https://img.shields.io/badge/- -%232c3e50?label=Book a Meeting with Me&style=social&logo=Google Calendar" alt="Calendly">
</a>