# cookiecutter-terraform-terratest

Cookiecutter template to start terraform module with basic boilerplate tests with terratest.

## Preparing your environment
You will need to install Cookiecutter and Precommit to be able to use this repo.
Consult the documentation for full instructions, but briefly:

### MacOS (using Homebrew)

- Ensure you have Python3 installed: ```brew install python3```
- Install cookiecutter: ```pip install --user cookiecutter```
- Install precommit: ```brew install pre-commit```

### Linux
- Ensure you have Python3 installed: ```apt install python3```
- Install cookiecutter: ```pip install --user cookiecutter```
- Install precommit: ```pip install pre-commit```

## Usage
```
cookiecutter https://github.com/robc-io/cookiecutter-terraform-terratest
```

- Answer the prompts given by cookiecutter
- Navigate to your newly created directory
- Initialize the git repo: ```git init```
- Install the pre-commit hooks ```pre-commit install```
- Make your first commit: ```git add -A && git commit```
- Profit!

See [cookiecutter docs](https://cookiecutter.readthedocs.io/en/1.7.0/) for more details.
