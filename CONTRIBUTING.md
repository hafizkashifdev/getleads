# Contributing to Get Leads

Thank you for your interest in contributing to Get Leads! This document provides guidelines and information for contributors.

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- Git
- A GitHub account

### Development Setup

1. **Fork the repository**
   - Click the "Fork" button on the GitHub repository page

2. **Clone your fork**
   ```bash
   git clone https://github.com/yourusername/get-leads.git
   cd get-leads
   ```

3. **Add upstream remote**
   ```bash
   git remote add upstream https://github.com/originalowner/get-leads.git
   ```

4. **Install dependencies**
   ```bash
   npm install
   ```

5. **Start development server**
   ```bash
   npm run dev
   ```

## 📝 Development Workflow

### Branch Naming Convention
- `feature/description` - New features
- `bugfix/description` - Bug fixes
- `hotfix/description` - Critical fixes
- `docs/description` - Documentation updates
- `refactor/description` - Code refactoring

### Commit Message Format
```
type(scope): description

[optional body]

[optional footer]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

**Examples:**
```
feat(ui): add user role management interface
fix(api): resolve lead import timeout issue
docs(readme): update installation instructions
```

## 🧪 Testing

### Running Tests
```bash
npm test
```

### Test Coverage
- Aim for at least 80% test coverage
- Write unit tests for new features
- Include integration tests for API endpoints

## 📋 Pull Request Process

### Before Submitting
1. **Update your fork**
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Write clean, readable code
   - Add tests for new functionality
   - Update documentation as needed

4. **Test your changes**
   ```bash
   npm test
   npm run lint
   ```

5. **Commit your changes**
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

### Pull Request Guidelines
- Use the provided PR template
- Provide a clear description of changes
- Include screenshots for UI changes
- Reference related issues
- Ensure all checks pass

## 🐛 Bug Reports

### Before Reporting
1. Check existing issues
2. Try the latest version
3. Reproduce the issue

### Bug Report Template
Use the GitHub issue template and include:
- Clear description
- Steps to reproduce
- Expected vs actual behavior
- Environment details
- Screenshots (if applicable)

## ✨ Feature Requests

### Before Requesting
1. Check existing feature requests
2. Consider the project's scope
3. Provide detailed use cases

### Feature Request Template
Use the GitHub issue template and include:
- Problem description
- Proposed solution
- Alternative solutions
- Additional context
- Priority level

## 📚 Code Style Guidelines

### HTML/CSS
- Use semantic HTML
- Follow BEM methodology for CSS
- Use consistent indentation (2 spaces)
- Comment complex sections

### JavaScript
- Use ES6+ features
- Follow consistent naming conventions
- Add JSDoc comments for functions
- Use meaningful variable names

### General
- Keep functions small and focused
- Write self-documenting code
- Use consistent formatting
- Remove unused code

## 🔒 Security

### Reporting Security Issues
- **DO NOT** create public issues for security vulnerabilities
- Email security issues to: hafizkashifdev@gmail.com
- Include detailed reproduction steps
- Allow time for response before disclosure

### Security Guidelines
- Never commit secrets or API keys
- Use environment variables for sensitive data
- Validate all user inputs
- Follow OWASP guidelines

## 📖 Documentation

### Documentation Standards
- Keep documentation up-to-date
- Use clear, concise language
- Include code examples
- Add screenshots for UI changes

### Types of Documentation
- README updates
- API documentation
- User guides
- Developer guides
- Changelog entries

## 🏷️ Release Process

### Version Numbering
We follow [Semantic Versioning](https://semver.org/):
- `MAJOR`: Breaking changes
- `MINOR`: New features (backward compatible)
- `PATCH`: Bug fixes (backward compatible)

### Release Checklist
- [ ] Update version numbers
- [ ] Update CHANGELOG.md
- [ ] Run full test suite
- [ ] Update documentation
- [ ] Create release notes
- [ ] Tag the release

## 🤝 Community Guidelines

### Code of Conduct
- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Follow the golden rule

### Communication
- Use clear, professional language
- Be patient with newcomers
- Ask questions when unsure
- Share knowledge generously

## 📞 Getting Help

### Resources
- GitHub Issues for bug reports and feature requests
- GitHub Discussions for questions and ideas
- Email: hafizkashifdev@gmail.com for direct contact

### Response Times
- Bug reports: 2-3 business days
- Feature requests: 1-2 weeks
- Security issues: 24-48 hours
- General questions: 3-5 business days

## 🎉 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation
- Annual contributor highlights

Thank you for contributing to Get Leads! 🚀
