# Contributing to OSSAfrica Community

Thank you for your interest in contributing to the OSSAfrica Community! This document provides guidelines and instructions for making contributions.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Types of Contributions](#types-of-contributions)
- [Contribution Process](#contribution-process)
- [Directory Structure](#directory-structure)
- [Submission Guidelines](#submission-guidelines)

## Code of Conduct

This project adheres to a Code of Conduct that all contributors are expected to follow. Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before contributing.

## How to Contribute

There are many ways to contribute to the OSSAfrica community:

1. Share your open source projects
2. Write articles and blog posts
3. Submit conference talks and presentations
4. Create tutorials and learning materials
5. Organize or promote community events
6. Add your member profile
7. Improve documentation
8. Help review contributions from others

## Types of Contributions

### Projects

Share your open source projects that benefit the African tech community.

**Location**: `contributions/projects/`

**Required Information**:
- Project name and description
- Repository URL
- Technology stack
- License information
- Contact information

**Template**: Use `templates/project-template.md`

### Articles

Contribute blog posts, articles, or written content about your experiences.

**Location**: `contributions/articles/`

**Required Information**:
- Article title
- Publication date
- Author information
- Link to published article (if available)
- Brief summary

**Template**: Use `templates/article-template.md`

### Talks & Presentations

Submit information about talks, presentations, or speaking engagements.

**Location**: `contributions/talks/`

**Required Information**:
- Talk title
- Event name and date
- Speaker information
- Recording/slides links (if available)
- Abstract or description

**Template**: Use `templates/talk-template.md`

### Tutorials

Create step-by-step tutorials and learning materials.

**Location**: `contributions/tutorials/`

**Required Information**:
- Tutorial title
- Difficulty level
- Technologies covered
- Author information
- Tutorial content or link

**Template**: Use `templates/tutorial-template.md`

### Events

Share information about community events, meetups, or conferences.

**Location**: `events/`

**Required Information**:
- Event name
- Date and time
- Location (physical or virtual)
- Description
- Registration link (if applicable)
- Organizer information

**Template**: Use `templates/event-template.md`

### Member Profiles

Add your profile to connect with other community members.

**Location**: `members/`

**Required Information**:
- Name
- Location
- Bio
- Skills/interests
- Social media links
- GitHub profile

**Template**: Use `templates/member-template.md`

## Contribution Process

1. **Fork the Repository**
   - Go to [github.com/OSSAfrica/community](https://github.com/OSSAfrica/community)
   - Click the "Fork" button in the top right corner
   - This creates a copy of the repository in your GitHub account

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/community.git
   cd community
   ```

3. **Create a New Branch**
   ```bash
   git checkout -b add-your-contribution
   ```

4. **Add Your Contribution**
   - Navigate to the appropriate directory
   - Copy the relevant template from `templates/`
   - Fill in your information
   - Save with a descriptive filename

5. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Add [type]: [brief description]"
   ```

6. **Push to Your Fork**
   ```bash
   git push origin add-your-contribution
   ```

7. **Create a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Fill in the PR template at `.github/pull_request_template.md`
   - Submit for review

## Directory Structure

Please place your contributions in the correct directory:

```text
community/
├── contributions/
│   ├── projects/          # Open source project submissions
│   │   └── your-project.md
│   ├── articles/          # Articles and blog posts
│   │   └── your-article.md
│   ├── talks/             # Conference talks and presentations
│   │   └── your-talk.md
│   └── tutorials/         # Tutorials and guides
│       └── your-tutorial.md
├── members/               # Member profiles
│   └── your-profile.md
├── events/                # Community events
│   └── event-name.md
├── resources/             # Shared resources
└── templates/             # Templates for contributions
```

## Submission Guidelines

### File Naming Conventions

- Use lowercase letters
- Separate words with hyphens (-)
- Use descriptive names
- Include dates for time-sensitive content (YYYY-MM-DD format)

**Examples**:
- `my-awesome-project.md`
- `getting-started-with-python.md`
- `2024-01-15-community-meetup.md`

### Content Guidelines

- Write clear and concise descriptions
- Include all required information from templates
- Provide working links (verify before submitting)
- Use proper markdown formatting
- Proofread your content
- Be respectful and professional

### Quality Standards

All contributions should:
- Be relevant to the African tech community
- Follow the Code of Conduct
- Include accurate information
- Provide value to the community
- Be properly attributed

## Review Process

1. Contributions are reviewed by maintainers
2. Feedback may be provided for improvements
3. Once approved, contributions are merged
4. Contributors are acknowledged in the community

## Issues and Proposals

Use issue templates under `.github/ISSUE_TEMPLATE/` to keep reports actionable:

- Bug report: repository problems in docs/templates/automation
- Feature request: process and community improvements
- Content submission help: guidance before opening a pull request

For policy or process-level changes, open an issue first to gather feedback before submitting a pull request.

## Getting Help

If you need help or have questions:
- Open an issue in this repository
- Ask questions in discussions
- Reach out to maintainers
- Check existing documentation

## Recognition

All contributors are valued and recognized:
- Listed in community acknowledgments
- Featured in community spotlights (with permission)
- Invited to community events and initiatives

Thank you for contributing to OSSAfrica Community! 🎉
