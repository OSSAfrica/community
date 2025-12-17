# Contributing to AI/ML - OSSAfrica

Thank you for your interest in contributing to the OSSAfrica AI/ML community! We welcome contributions from everyone, regardless of experience level.

## 🌟 Ways to Contribute

### 1. Code Contributions
- Add new AI/ML projects
- Improve existing projects
- Fix bugs and issues
- Optimize algorithms and models
- Add tests and documentation

### 2. Documentation
- Write tutorials and guides
- Improve existing documentation
- Translate content to African languages
- Create video tutorials or demos
- Document best practices

### 3. Datasets
- Share information about relevant datasets
- Create new datasets for African contexts
- Document data collection methodologies
- Ensure ethical data handling

### 4. Research
- Share research papers and findings
- Conduct experiments and share results
- Review and summarize relevant literature
- Propose new research directions

### 5. Community Support
- Answer questions in discussions
- Review pull requests
- Mentor new contributors
- Organize events and workshops

## 🚀 Getting Started

### Prerequisites

1. **GitHub Account**: Create a free account at [github.com](https://github.com)
2. **Git**: Install Git on your local machine
3. **Programming Environment**: Set up Python, R, or your preferred language
4. **AI/ML Tools**: Install necessary frameworks (TensorFlow, PyTorch, scikit-learn, etc.)

### Setting Up Your Development Environment

```bash
# Fork the repository on GitHub

# Clone your fork
git clone https://github.com/YOUR_USERNAME/community.git
cd community/ai-ml

# Add upstream remote
git remote add upstream https://github.com/OSSAfrica/community.git

# Create a virtual environment (Python example)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install common dependencies
pip install -r requirements.txt  # If available
```

## 📝 Contribution Process

### Step 1: Find or Create an Issue

- Browse existing [issues](https://github.com/OSSAfrica/community/issues)
- Comment on an issue you'd like to work on
- Or create a new issue describing your proposed contribution
- Wait for approval/feedback before starting work

### Step 2: Create a Branch

```bash
# Update your fork
git checkout main
git pull upstream main

# Create a new branch
git checkout -b feature/your-feature-name
# or
git checkout -b fix/your-bug-fix
```

### Step 3: Make Your Changes

- Write clean, readable code
- Follow existing code style and conventions
- Add comments where necessary
- Include docstrings for functions and classes
- Write tests for new functionality
- Update documentation

### Step 4: Test Your Changes

```bash
# Run tests (if available)
pytest tests/

# Run linting
flake8 your_files/
# or
pylint your_files/

# Test your changes manually
python your_script.py
```

### Step 5: Commit Your Changes

```bash
# Stage your changes
git add .

# Commit with a descriptive message
git commit -m "Add: Brief description of your changes"
```

**Commit Message Guidelines:**
- Use present tense ("Add feature" not "Added feature")
- Use imperative mood ("Move cursor to..." not "Moves cursor to...")
- First line should be 50 characters or less
- Reference issues and pull requests when relevant

Examples:
```
Add: Tutorial for training image classification model
Fix: Bug in data preprocessing pipeline
Update: Documentation for NLP project
```

### Step 6: Push and Create Pull Request

```bash
# Push to your fork
git push origin feature/your-feature-name
```

Then:
1. Go to your fork on GitHub
2. Click "New Pull Request"
3. Fill in the PR template with:
   - Description of changes
   - Related issue number
   - Testing performed
   - Screenshots (if applicable)
4. Submit the pull request

## 📋 Project Structure Guidelines

### Adding a New Project

Create a project directory under `ai-ml/projects/` with the following structure:

```
projects/
└── your-project-name/
    ├── README.md           # Project overview and documentation
    ├── requirements.txt    # Python dependencies (if applicable)
    ├── src/               # Source code
    │   ├── __init__.py
    │   └── main.py
    ├── data/              # Sample data or data documentation
    │   └── README.md
    ├── notebooks/         # Jupyter notebooks (if applicable)
    │   └── exploration.ipynb
    ├── tests/             # Unit tests
    │   └── test_main.py
    ├── models/            # Trained models or model configs
    │   └── README.md
    └── LICENSE            # Project-specific license
```

### Project README Template

Your project README should include:

```markdown
# Project Name

Brief description of what the project does.

## Problem Statement
What problem does this solve?

## Approach
How does the solution work?

## Requirements
- Python 3.8+
- TensorFlow 2.x
- etc.

## Installation
Step-by-step installation instructions

## Usage
How to use the project

## Results
Performance metrics, visualizations, etc.

## Future Work
What could be improved?

## Contributors
List of contributors

## License
License information
```

## 🎯 Code Quality Standards

### Python Code Style
- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide
- Use meaningful variable and function names
- Maximum line length: 88 characters (Black formatter default)
- Use type hints where appropriate

### Example:
```python
def train_model(
    data: pd.DataFrame,
    target_column: str,
    test_size: float = 0.2
) -> tuple:
    """
    Train a machine learning model.
    
    Args:
        data: Input dataframe
        target_column: Name of target variable
        test_size: Proportion of data for testing
        
    Returns:
        Tuple of (trained_model, test_score)
    """
    # Implementation here
    pass
```

### Documentation Standards
- Use clear, concise language
- Include code examples
- Add diagrams or visualizations where helpful
- Keep documentation up-to-date with code changes

### Testing Standards
- Write unit tests for core functionality
- Aim for >80% code coverage
- Include edge cases
- Use descriptive test names

## 🔒 Data and Model Guidelines

### Data Ethics
- Ensure data is ethically sourced
- Respect privacy and confidentiality
- Document data sources and collection methods
- Include data licenses
- Anonymize sensitive information

### Model Development
- Document model architecture and choices
- Include performance metrics
- Test for bias and fairness
- Consider computational efficiency
- Make models reproducible

### Large Files
- **DO NOT** commit large files (>10MB) directly
- Use Git LFS for large datasets or models
- Provide download links or scripts
- Document data storage locations

## 🤝 Code Review Process

All contributions go through code review:

1. **Automated Checks**: CI/CD runs tests and linting
2. **Peer Review**: Maintainers review code quality
3. **Feedback**: Reviewers may request changes
4. **Iteration**: Make requested changes
5. **Approval**: Once approved, PR will be merged

### What Reviewers Look For
- Code correctness and quality
- Test coverage
- Documentation completeness
- Adherence to guidelines
- Performance considerations
- Security issues

## 🐛 Reporting Issues

When reporting bugs or issues:

1. Check if issue already exists
2. Use issue templates if available
3. Include:
   - Clear title and description
   - Steps to reproduce
   - Expected vs actual behavior
   - Environment details (OS, Python version, etc.)
   - Screenshots or error messages
   - Relevant code snippets

## 💬 Communication

- **GitHub Discussions**: For questions and general discussion
- **Issues**: For bug reports and feature requests
- **Pull Requests**: For code contributions
- **Be respectful and constructive** in all communications

## 📜 License

By contributing, you agree that your contributions will be licensed under the same license as the project (see LICENSE file in project directory).

## 🙏 Recognition

Contributors will be:
- Listed in project README files
- Mentioned in release notes
- Recognized in community showcases

## ❓ Questions?

If you have questions:
- Check existing documentation
- Search closed issues
- Ask in GitHub Discussions
- Tag maintainers in issues

---

**Thank you for contributing to OSSAfrica AI/ML community!** Your contributions help build AI/ML capacity across Africa. 🌍✨
