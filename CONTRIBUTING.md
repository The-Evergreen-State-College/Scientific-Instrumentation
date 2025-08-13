# Contributing to Scientific-Instrumentation

Welcome to the **Scientific-Instrumentation** repository! This project is a collaborative effort to develop open-source tools, documentation, and code for scientific instrumentation projects at The Evergreen State College. We encourage contributions from students at all skill levels, whether you’re new to coding or an experienced developer.

This document outlines how to contribute, with five progressive levels of responsibility. Each level builds on the previous one, helping you develop skills in scientific programming, version control, collaboration, and project management. If you have questions, contact the maintainer at [geeraerd@evergreen.edu].

## Technologies Used
- [**Notepad++**](https://notepad-plus-plus.org/): Text editor for writing and editing code files.
- [**VS Code**](https://code.visualstudio.com/): Primary code editor for writing and managing project files.
- [**Quarto**](https://quarto.org/): For creating reproducible scientific documents and reports.
- **Markdown (.md)**: For documentation, including READMEs and Quarto files.
- [**Git**](https://git-scm.com/): Version control system for tracking changes and collaborating.
- [**GitHub**](https://github.com/): Platform for hosting the repository and managing contributions.

## Getting Started
1. Read this `CONTRIBUTING.md` file to understand the contribution process.
2. Familiarize yourself with the repository structure (e.g., `/assets`, `/Instrumentation`).
3. Ensure you have the necessary tools installed (see [Setup](#setup) below).
4. Start at the appropriate contribution level based on your skills and experience.

## Contribution Levels

### Level 1: Basic File Contribution
**Description**: Share project files without directly interacting with GitHub. Ideal for beginners new to version control or GitHub.

**Tasks**:
- Send files (e.g., `.png`, `.qmd`, `.md`, or data files) via email to [geeraerd@evergreen.edu] or upload to the designated network file share on Google Drive.
  - Ask for the credentials to access the Google Drive folder if you don’t have them.
- Follow the naming convention for files based on what you see in file names for the file types.
- Include a brief description of the file’s purpose in the email or a text file.

**Expectations**:
- Submit files by agreed deadlines.
- Files should follow project standards (e.g., Quarto documents, or Markdown files).
- Descriptions are clear and concise (e.g., “This Quarto file documents the sensor calibration process”).

**Skills Developed**:
- File organization and naming conventions.
- Professional communication.
- Familiarity with project file types (e.g., `.qmd`, `.md`).

### Level 2: GitHub Pull Requests
**Description**: Contribute directly to the repository using GitHub’s web interface. Suitable for those ready to learn basic version control.

**Tasks**:
- Create a GitHub account and fork the repository or request collaborator access.
- Upload files or edit existing ones via the GitHub web interface (e.g., drag-and-drop or edit directly).
- Submit changes as a pull request (PR) with a descriptive title and message (e.g., “Add sensor data processing script”).
- Open issues to report bugs, suggest improvements, or ask questions.

**Expectations**:
- Place files in the correct directory. Do not put anything in `/docs` that is reserved for Quarto compiled files, a.k.a. the website.
- PR descriptions explain the purpose and reference related issues (e.g., “Fixes #10”).
- Issues are detailed, including steps to reproduce bugs or clear suggestions.

**Skills Developed**:
- Navigating GitHub’s web interface.
- Writing clear PRs and issue reports.
- Basic version control concepts (e.g., commits, PRs).

### Level 3: Local Development with VS Code
**Description**: Work with the repository locally using Git and submit PRs via VS Code’s GitHub extension. For those comfortable with GitHub and ready for a local workflow.

**Tasks**:
- Clone the repository to your local machine (`git clone https://github.com/The-Evergreen-State-College/Scientific-Instrumentation.git`).
- Create a new branch for your changes (e.g., `git branch feature-sensor-script`).
- Edit files in VS Code (e.g., Quarto documents, or Markdown).
- Commit changes with descriptive messages and push to GitHub using VS Code’s GitHub extension.
- Create a PR to propose your changes for review.

**Expectations**:
- Follow a Git workflow: clone, branch, commit, push, PR.
- PRs include clear descriptions and adhere to project standards (e.g., consistent Quarto formatting).
- Test changes locally (e.g., run preview and render Quarto documents).

**Skills Developed**:
- Proficiency with Git and VS Code’s GitHub extension.
- Local development and testing workflows.
- Writing clean, documented code and documentation.

### Level 4: Direct Push Access
**Description**: Take on significant responsibility with direct push access to the main branch. Reserved for contributors with a proven track record of high-quality PRs.

**Tasks**:
- Push changes directly to the `main` branch or other designated branches.
- Review PRs from other contributors, providing constructive feedback.
- Update documentation (e.g., README, Quarto guides) to reflect project changes.
- Propose and lead new features or modules (e.g., a new instrumentation script or report).

**Expectations**:
- Changes are tested and maintain project integrity (e.g., no breaking changes).
- PR reviews are thorough, respectful, and align with project standards.
- Documentation is clear, up-to-date, and follows Markdown/Quarto conventions.
- Communicate actively via GitHub issues or email to coordinate with the team.

**Skills Developed**:
- Leadership in collaborative projects.
- Code and documentation review skills.
- Project planning and execution.

### Level 5: Maintainer
**Description**: Oversee the repository as a maintainer, managing contributions, mentoring contributors, and ensuring project quality. For students with extensive experience and a strong track record at Level 4.

**Tasks**:
- Manage the repository’s structure, branches, and settings on GitHub.
- Merge PRs after thorough review, ensuring alignment with project goals.
- Mentor new contributors by providing feedback, answering questions, and guiding them through contribution levels.
- Define and prioritize project tasks by creating issues and milestones.
- Maintain and update documentation, including `README.md` and `CONTRIBUTING.md`.
- Coordinate with other maintainers or faculty to align the project with academic goals.

**Expectations**:
- Ensure the repository remains organized, accessible, and welcoming to contributors.
- Provide timely, constructive feedback on PRs and issues (within 1–2 days).
- Proactively identify and address technical or organizational issues (e.g., outdated dependencies, unclear documentation).
- Uphold project standards (e.g., code quality, Quarto formatting) and enforce contribution guidelines.
- Communicate regularly with contributors and faculty via GitHub, email, or other channels.

**Skills Developed**:
- Project management and leadership in open-source development.
- Mentorship and communication in a collaborative setting.
- Strategic planning for project growth and sustainability.
- Advanced GitHub administration (e.g., branch protection, milestones).

## Setup
To contribute effectively, set up the following tools:
1. **VS Code**: Install from [code.visualstudio.com](https://code.visualstudio.com/). Add extensions:
   - GitHub Pull Requests and Issues
   - Quarto (for `.qmd` files)
   - Markdown All in One (for `.md` files)
2. **Git**: Install from [git-scm.com](https://git-scm.com/) and configure with your GitHub account.
3. **Quarto**: Install from [quarto.org](https://quarto.org/) for rendering `.qmd` files.
4. **GitHub Account**: Sign up at [github.com](https://github.com/) and share your username with the maintainer for access.

## Project Standards
- **File Naming**: Use the template layout.
- **Code Style**: Follow project template. Comment code clearly.
- **Quarto/Markdown**: Use consistent headings and formatting. Test Quarto files locally before submitting.
- **Commit Messages**: Be descriptive (e.g., “Add data visualization for temperature sensor”).
- **Directory Structure**:
  - `/docs`: RESERVED! Quarto files.
  - `/assets`: Images, figures, or other assets used in documentation.

## How to Progress
- Start at **Level 1** and submit 2–3 successful contributions to move to **Level 2**.
- After mastering GitHub PRs at **Level 2**, transition to **Level 3** with local development.
- With a consistent record of high-quality PRs at **Level 3**, you may be granted **Level 4** push access.
- After demonstrating leadership and reliability at **Level 4**, you may be invited to become a **Level 5** maintainer.
- Discuss your progress with the current maintainer to ensure you’re ready for the next level.

## Getting Help
- **Issues**: Open a GitHub issue for bugs, questions, or suggestions.
- **Email**: Contact [geeraerd@evergreen.edu] for direct support.
- **Resources**:
  - [VS Code Documentation](https://code.visualstudio.com/docs)
  - [Quarto Getting Started](https://quarto.org/docs/get-started/)
  - [GitHub Guides](https://guides.github.com/)
  - [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

Thank you for contributing to **Scientific-Instrumentation**! Your work helps advance creative commons & open-source scientific tools at Evergreen.