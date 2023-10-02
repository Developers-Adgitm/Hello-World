  # Hello World Program

This is a simple "Hello World" program in [any programming language]. You can use this Repo as a starting point for your "Hello World" project in any language of your choice.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

# Introduction

The "Hello World" program is a classic beginner's project that serves as a simple introduction to a programming language. It is often the first program a developer writes when learning a new language.

# Getting Started

To get started with this "Hello World" program, follow these steps:

1. Create a folder at you desired location (usually at your desktop).

2. Open Git Bash Here.

3. Create a Git Repository.
   Run the command ```git init```

4. Fork the [repository](https://github.com/Developers-Adgitm/Hello-World.git).

5. Clone your forked repository of project.
```
git clone https://github.com/<your-github-username>/Hello-World.git
```
  
6. Navigate to the project directory.
```
cd Hello-World
```

7. Add a reference(remote) to the original repository.
```
git remote add upstream https://github.com/Developers-Adgitm/Hello-World.git
```

8. Check the remotes for this repository.
```
git remote -v
```

9. Always take a pull from the upstream repository to your main branch to keep it updated as per the main repository.
```
git pull upstream main
```

8. Create a new branch.
```
git checkout -b <your_branch_name>
```

9. Perform your desired changes to the code base.

10. Check your changes
```
git status
```
```
git diff
```

11. Stage your changes
```
git add . <\files_that_you made_changes>
```

12. Commit your changes.
```
git commit -m "<your_commit_message>"
```

13. Push the committed changes in your feature branch to your remote repository.
```
git push -u origin <your_branch_name>
```

14. To create a Pull Request, click on ```compare and pull requests```.

15. Add an appropriate title and description to your PR explaining your changes.

18. Click on ```create pull request```.

Congratulations🎉, you have made a PR to Hello-World Project . Wait for your submission to be accepted and your PR to be merged by a maintainer.

# Usage

Replace `[programming language]` with the actual programming language you are using. Here's an example "Hello World" program in Python:
File name will be Hello-World.py

```python
print("Hello, World!")
```
# Contributing
If you'd like to contribute to this project, you can:

1. Fork the repository
2. Make your changes
3. Create a pull request

Please make sure to follow the Contributing Guidelines when submitting your contributions.

# License
This project is licensed under the MIT License, which means you are free to use, modify, and distribute it for personal or commercial purposes.
