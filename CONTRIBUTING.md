# Contributing

Thank you for considering contributing to our packages! We appreciate your help in making our code better.

## TL;DR

- Discuss big changes first
- One feature/fix per PR to `main` branch
- Add/update tests
- Update documentation
- Run `composer test`, `composer format`, and `composer analyse`
- Be kind and respectful

## Before You Start

We love contributions, but to save everyone time and avoid disappointment:

**Please discuss first** before working on:
- Major new features
- Large refactors
- Breaking changes
- Anything you're unsure about

Every package has a specific purpose and philosophy. We carefully consider whether new features align with our vision for what this package should be and do. Even great ideas might not be the right fit if they would change the package's core purpose or make it harder to maintain.

We maintain our packages for current and recent versions of Laravel and PHP. We typically don't backport features or fixes to older versions.

Just start the conversation through GitHub describing what you have in mind. We'd hate to see you put in a lot of work only to have to decline it. When in doubt, just ask! We're happy to discuss ideas.

## How to Contribute

### Setup

See our README for installation and setup instructions.

### Making Changes

1. Fork the repository and create your branch from `main`
2. Make your changes in small, logical commits
3. Add tests for any new functionality
4. Update documentation if needed
5. Ensure all tests pass: `composer test`
6. Format your code: `composer format`
7. Run static analysis: `composer analyse`
8. Submit your pull request

When you submit your PR, GitHub Actions will automatically run tests, code style checks, and static analysis. If any of these checks fail, you'll need to fix the issues before we can review your PR.

All accepted contributions will be credited.

### Pull Request Guidelines

- **One thing at a time**: one pull request per feature or fix
- **Clear commits**: small, logical commits with descriptive messages
- **Tests required**: new features need tests, bug fixes should include a test that would have caught the bug
- **Update docs**: keep README and other documentation up to date
- **No breaking changes**: unless discussed and agreed upon first

## Code Quality

Before submitting your PR, ensure all quality checks pass:

- `composer test` - Run the test suite
- `composer format` - Format code with Laravel Pint (Laravel preset)
- `composer analyse` - Run static analysis

If you're new to testing, that's okay! Do your best, and we can help you improve the tests during the review process.

## Our Expectations

We're friendly and understanding, and we expect the same from everyone who communicates with us. Everyone wrote their first line of code at some point. We all started somewhere and we're all continuously learning.

We welcome contributors of all experience levels. Whether this is your first open source contribution or your thousandth, you're welcome here.

**Please:**
- Be respectful and considerate
- Be patient (we maintain these packages in our spare time)
- Accept feedback gracefully

**We won't tolerate:**
- Harassment or discrimination
- Aggressive or disrespectful communication
- Bad faith arguments

## Questions?

Not sure about something? Just ask! We're happy to help through GitHub.
