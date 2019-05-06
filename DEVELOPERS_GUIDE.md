# Developers' Guide to Contribution

So, you've decided that you want to help beginner programmers get started with Git and Python. That's great! I'm sure that if you want to include your project in this list, you are an experienced (or at least an intermediate) Python programmer and Git user, so I won't waste your time.

## Project Rules

You should follow a few rules to make projects similar and make beginners feel confident when they try your project.

- Comment/include docstrings in your code. You don't have to comment *everything*, but please at least include a small note when dealing with external modules or complicated concepts such as threading.

- In case you decide to comment **everything**, include a version of your program with less documentation, to help fellow developers save time scrolling through 50 lines of docstring. If you want to go this way, the filename should have `_nodoc` appended. (E.g. `program.py` --> `program_nodoc.py`)

- When writing code, please follow the [PEP 8 Style Guide](https://www.python.org/dev/peps/pep-0008/). This will ensure a consistent style with other projects. The most important parts are: max. 79 characters per line, hanging idents and variable naming guides.

- Include an installation section in your README. Even if it's just a 'pip install mypackage', it will only help beginners.

- Help beginners. (Hopefully) they will ask questions, or ask for help when trying to implement a new feature.

- You should have at least two branches. `master` should be where your original project lives. Only accept pull requests that fix issues or optimize things. Your second branch should be called `community` (or another similar name.). This branch should contain the "extended" version of your program, which has been worked on by other people. It could be even be bloated with (even non working) features, you don't have to care, you have your master branch. You should note that this branch can be a mess or require more experience to fix/extend upon.

## Labels

When creating an issue, please use these labels to help people find the issues they desire.

**feature-request** - Use this when you want to add a feature request.

**bug-report** - Use this when reporting a bug.

**difficulty: [easy-medium-expert] - Please tag every issue with a difficulty to help beginners. There are no *hard-coded* levels, but make sure to only use a maximum of five.
