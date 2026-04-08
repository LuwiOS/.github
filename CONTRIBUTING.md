# CONTRIBUTING.md

## Contributing to LuwiOS

Thank you for your interest in contributing to **LuwiOS**! We welcome contributions from everyone, whether you're fixing bugs, improving documentation, or developing new features.

### Code of Conduct
By participating in this project, you agree to uphold our [Code of Conduct](CODE_OF_CONDUCT.md). We expect all contributors to be respectful, inclusive, and collaborative.

## How to Contribute

### 🐛 Reporting Bugs
Please search [existing issues](https://github.com/luwios/luwios/issues) before submitting a new one. Use the [Bug Report Template](ISSUE_TEMPLATE/bug_report.md) to provide:
- Clear description of the issue
- Steps to reproduce
- Expected vs. actual behavior
- Environment details (OS version, kernel, hardware)

### 💡 Suggesting Features
Have an idea? Use the [Feature Request Template](ISSUE_TEMPLATE/feature_request.md). Include:
- The problem you're trying to solve
- Your proposed solution
- Real-world use cases
- Whether you're willing to implement it

### 📝 Documentation Improvements
Help us improve guides, tutorials, and comments. Even small fixes like typos or broken links are appreciated.

### 💻 Code Contributions
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Push to your fork
5. Open a pull request to `main`

Ensure your code:
- Follows Rust style (`cargo fmt`)
- Includes tests when applicable
- Is well-documented

## Development Setup
```bash
# Clone your fork
git clone https://github.com/your-username/luwios.git
cd luwios

# Build the project
make build

# Run tests
make test
```

## Pull Request Guidelines
- Use descriptive commit messages
- Reference related issues (e.g., `Fixes #123`)
- Ensure CI passes
- Be responsive to review feedback

We review all PRs promptly. Thank you for helping build LuwiOS! 🚀
