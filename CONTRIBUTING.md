# Contributing to apps-frontend

Thank you for contributing to apps-frontend! This document provides guidelines and instructions for contributing.

## Code of Conduct

Be respectful and professional in all interactions with other contributors.

## Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally
3. **Create a feature branch**: `git checkout -b feature/your-feature-name`
4. **Install dependencies**: `npm install`
5. **Make your changes** following the code style
6. **Test your changes**: `npm run test`
7. **Commit your changes** with clear messages
8. **Push to your fork** and create a Pull Request

## Development Workflow

### Branch Naming
- Feature branches: `feature/feature-name`
- Bug fixes: `fix/bug-name`
- Documentation: `docs/documentation-name`
- Refactoring: `refactor/component-name`

### Commit Messages
Use clear, descriptive commit messages:
```
feat: add user authentication component
fix: resolve styling issue on mobile
docs: update installation instructions
```

### Code Style
- Use TypeScript for type safety
- Follow ESLint and Prettier configurations
- Write meaningful comments for complex logic
- Keep components small and focused

### Testing
- Write unit tests for new features
- Ensure integration tests pass
- Test your changes across different browsers/devices
- Maintain or improve code coverage

```bash
npm run test              # Run tests
npm run test:coverage     # Check coverage
npm run lint              # Run linter
npm run format            # Format code with Prettier
```

## Pull Request Process

1. **Update documentation** if needed
2. **Add tests** for new functionality
3. **Ensure all tests pass**: `npm run test`
4. **Run linter**: `npm run lint`
5. **Provide a clear description** of your changes
6. **Reference related issues** using `#issue-number`
7. **Wait for review** and address feedback

## Reporting Issues

When reporting bugs, please include:
- Clear description of the issue
- Steps to reproduce
- Expected behavior
- Actual behavior
- Browser/environment information
- Screenshots if applicable

## Questions?

Feel free to open an issue or contact the maintainers.

Thank you for contributing!
