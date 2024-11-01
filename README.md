# Set up instructions

Please complete the steps in this README before your interview. This will give you as much time as possible in the interview 
to demonstrate your technical skills.

## Pre-requisites

#### Something to edit and run code

You may want to use an IDE such as VSCode or Pycharm. However, any text editor and terminal you are comfortable using will work.

#### Python (3.11.* or later)

To check which version of Python you have installed, run:

```commandline
python --version
```

#### Poetry

Poetry is a tool for dependency management and packaging in Python. Follow the [installation instructions](https://python-poetry.org/docs/#installing-with-pipx) if you need to 
install it.

To confirm Poetry is installed, run:

```commandline
poetry --version
```

## Running the code

Clone a copy of the repository to your machine:

```commandline
git clone https://github.com/peter-woodcock/junior-tech-test.git
```

To activate the virtual environment and install the required packages, run the following commands in the root folder of 
this project:

```commandline
poetry shell
poetry install
```

There's one unit test that should pass when you run:
```commandline
pytest
```
You can test that the module loads the test data as expected by running:
```commandline
python3 derec test
```

Once you reach this point, the project is set up and ready to go.

## Exploring the code

You are welcome to explore the code base as much as you'd like. We will provide you with the tasks 
to complete at the start of the interview.
