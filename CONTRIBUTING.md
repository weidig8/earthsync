# Contribution Guidelines

Thank you for your interest in contributing to EarthSync! We welcome contributions from everyone. Please read this document to understand our guidelines before starting.

## Getting Started
1. **Fork the repository**: Click on the 'Fork' button at the top right corner of the repository page.
2. **Clone your fork**: Clone your forked repository to your local machine using Git.
   ```bash
   git clone https://github.com/<your-username>/earthsync.git
   ```
3. **Set up the upstream remote**: This helps you keep your fork up to date with the original repository.
   ```bash
   git remote add upstream https://github.com/weidig8/earthsync.git
   ```

## Development Workflow
- Create a new feature branch off of `main`:
  ```bash
  git checkout -b feature/my-feature
  ```
- Make your changes and commit them:
  ```bash
  git commit -m "Add my feature"
  ```
- Push to your fork:
  ```bash
  git push origin feature/my-feature
  ```

## Code Style
- Please adhere to the code styles present in the codebase. Use tools like Prettier or ESLint to maintain code quality.

## Commit Message Conventions
- Use the following format for commit messages:
  ```
  type(scope): subject
  
  body (optional)
  
  footer (optional)
  ```
- Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

## Pull Request Process
1. Ensure your branch is up to date with `main`.
2. Open a pull request (PR) from your feature branch to `main`.
3. Please provide a clear description of your changes and the reasoning behind them.
4. Reviewers will provide feedback, which may require further changes before merging.

## Areas to Contribute
- Bug Fixes
- Documentation
- New Features or Enhancements
- Testing and Quality Assurance

## Bug Reports
- Please use the GitHub issue tracker to report bugs. Include steps to reproduce the issue and any relevant information.

## Feature Requests
- If you have a feature idea, please open a new issue on GitHub. Provide details on the use case and why it would be beneficial.

Thank you again for considering contributing to EarthSync! We're excited to see your contributions.