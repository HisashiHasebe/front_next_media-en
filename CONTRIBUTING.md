# Contributing to Kuroco Media Sample Site

Thank you for your interest in contributing to the Kuroco Media Sample Site! We welcome contributions from the community.

## Getting Started

1. Fork the repository
2. Clone your fork locally
3. Create a new branch for your feature or bug fix
4. Make your changes
5. Test your changes thoroughly
6. Submit a pull request

## Development Setup

```bash
# Clone the repository
git clone https://github.com/diverta/front_next_media.git

# Navigate to the project directory
cd front_next_media

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Edit .env file with your Kuroco API credentials
# NEXT_PUBLIC_BASE_URL=https://your-instance.a.kuroco.app
# NEXT_PUBLIC_FRONT_URL=http://localhost:3000

# Start development server
npm run dev
```

## Code Style

This project uses:
- **ESLint** for JavaScript/JSX linting
- **Prettier** for code formatting
- **Husky** for pre-commit hooks

Before committing, ensure your code:
- Passes ESLint checks: `npm run lint`
- Is properly formatted: `npm run format`

## Pull Request Guidelines

1. **Clear Description**: Provide a clear description of what your PR does
2. **Small PRs**: Keep pull requests focused and small when possible
3. **Tests**: Include tests if applicable
4. **Documentation**: Update documentation if you're changing functionality
5. **Commit Messages**: Use clear, descriptive commit messages

### Commit Message Format

We follow conventional commits format:

```
type(scope): brief description

- Detailed explanation if needed
- Can be multiple lines
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

Examples:
```
feat(article): add pagination to article list
fix(auth): resolve login redirect issue
docs(readme): update setup instructions
```

## Reporting Issues

When reporting issues, please include:
- A clear description of the problem
- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshots (if applicable)
- Environment details (OS, browser, Node version)

## Feature Requests

We welcome feature requests! Please:
- Check if the feature has already been requested
- Provide a clear use case
- Explain how it benefits the project

## Questions?

If you have questions:
- Check the [documentation](https://kuroco.app/docs/)
- Contact our [support](https://kuroco.app/docs/about/support/)
- Open a GitHub issue with the "question" label

## Code of Conduct

Be respectful and constructive in all interactions. We're here to build something great together!

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
