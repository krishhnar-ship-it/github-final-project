# Contributing Guidelines

All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.

Thank you for your interest in contributing to this project! These guidelines explain how to contribute changes clearly and effectively.

## 1. Getting Started

Before contributing, make sure you have:

- A GitHub account.
- Git installed on your computer.
- Access to the project repository.
- Basic knowledge of Git and GitHub commands.

## 2. Fork the Repository

1. Open the original repository on GitHub.
2. Click the **Fork** button.
3. Select your GitHub account as the owner.
4. Keep the repository name exactly as `mcino-Introduction-to-Git-and-GitHub`.
5. Ensure that the fork is public.

## 3. Clone Your Fork

Clone your fork to your local computer:

```bash
git clone https://github.com/YOUR_USERNAME/mcino-Introduction-to-Git-and-GitHub.git
```

Navigate to the project directory:

```bash
cd mcino-Introduction-to-Git-and-GitHub
```

Replace `YOUR_USERNAME` with your GitHub username.

## 4. Create a New Branch

Create a separate branch for your contribution instead of working directly on the main branch.

```bash
git checkout main
git pull origin main
git checkout -b your-branch-name
```

Use a descriptive branch name, such as:

- `bug-fix-typo`
- `bug-fix-revert`
- `add-code-of-conduct`
- `update-documentation`

## 5. Make Your Changes

Make your changes to the appropriate files in the project.

For example, contributions may include:

- Fixing spelling mistakes and typos.
- Improving README documentation.
- Adding a `CODE_OF_CONDUCT.md` file using the Contributor Covenant.
- Updating the `CONTRIBUTING.md` guidelines.
- Fixing bugs and improving existing functionality.

Keep changes focused and ensure that the modified files are saved.

## 6. Review and Stage Your Changes

Check which files have been modified:

```bash
git status
```

Review your changes:

```bash
git diff
```

Stage the files you want to include in your contribution:

```bash
git add .
```

If you want to stage only one file, use:

```bash
git add CONTRIBUTING.md
```

## 7. Commit Your Changes

Commit your staged changes with a meaningful message:

```bash
git commit -m "Add contribution guidelines"
```

Other examples of meaningful commit messages include:

```bash
git commit -m "Fix copyright year typo in README"
```

```bash
git commit -m "Add Contributor Covenant code of conduct"
```

Write commit messages that briefly explain what you changed.

## 8. Push Your Branch

Push your branch to your GitHub fork:

```bash
git push -u origin your-branch-name
```

When using HTTPS authentication, enter your GitHub username and use an appropriate Personal Access Token when Git requests a password.

Never share your access token or commit it to the repository.

## 9. Submit a Pull Request

1. Open your fork on GitHub.
2. Select the branch containing your changes.
3. Click **Compare & pull request** or open the **Pull requests** tab and click **New pull request**.
4. Select the appropriate base repository and branch.
5. Provide a clear title and description.
6. Explain what you changed and why.
7. Submit the pull request for review.

For contributions intended for the original project, ensure that the base repository is `ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub` and the base branch is `main`.

## 10. Code of Conduct

All contributors are expected to follow the project's `CODE_OF_CONDUCT.md` file.

Be respectful, considerate, and constructive when communicating with other contributors. Help maintain an inclusive and welcoming environment for everyone.

## 11. Reporting Bugs

When reporting a bug, provide:

- A clear and descriptive title.
- Steps to reproduce the problem.
- Expected behavior.
- Actual behavior.
- Relevant error messages or screenshots, if available.

Include enough information to help others understand and reproduce the issue.

## 12. Documentation Improvements

Documentation improvements are welcome. Ensure that instructions are clear, accurate, easy to follow, and consistent with the project's existing documentation.

Check spelling, formatting, Markdown headings, and code examples before submitting documentation changes.

## 13. Review and Feedback

Contributors may be asked to update their changes based on feedback. Please review comments carefully, make any necessary corrections, and push additional commits to the same branch.

Thank you for helping improve this project and for contributing to the open-source community!
