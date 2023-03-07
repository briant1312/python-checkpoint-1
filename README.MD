[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/software-engineering-immersive/boston)

# Python Checkpoint 1

## Preparation

- Accept the Github classroom invitation.
- **Clone** this repo.
- Run `pip3 install pipenv` (If that doesn't work try `python3 -m install pipenv` or `sudo -H pip3 install -U pipenv`)
- Run `pipenv install` to install the dependencies for this checkpoint and setup
    the virtual environment 
- Run `pipenv shell` to activate your virtual environment
- Run `pytest` from your activated terminal to check that the tests are working (`pytest`)

> `pytest` command not found?

<details>
<summary>Try</summary>

**While in the virtual environment:**
```
pip3 install --user pipenv
```

</details>

> `pytest` command is running but not showing the tests?

<details>
<summary>Try</summary>

**While in the virtual environment:**
```
pip3 install pip-review
```
**Then**
```
pip-review --local --interactive
```
    
If it asks you to update your dependencies, respond with yes!
    
</details>

## Running Tests

To execute all the tests in the terminal, run `pytest`. Every time you make a change and
save your files, you will need to manually re-run the tests.

Each test file corresponds to one of the code files.

| test file | code file | 
| ----------| ----------|
| tests/data_types_test.py | data_types.py |
| tests/methods_test.py | methods.py |
| tests/oop_test.py | oop.py |

To run a single test file: `pytest ./tests/path-to-test-file.py`

When you start, all of the tests will be failing; your goal is to make as many
pass as you can in the hour provided.

> HINT: read the output of the failing tests.

## Instructions

This checkpoint is divided into three sections:

- Data Types in `data_types.py`
- Methods in `methods.py`
- Object Oriented Programming in `oop.py`

Each section has a series of prompts written in inline comments. Write the
Python necessary to complete each prompt in each of the three files.

**Make a commit after you complete each section.**

**DO NOT** Modify the files in the `tests/` folder.

## Submission

Commit as you go. When you arefinished, push your commits to GitHub.

Pull request when finished!
