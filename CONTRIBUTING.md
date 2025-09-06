# Contributing to BitVM Bridge

Thank you for your interest in contributing! We are thrilled to have you. This guide will help you get started.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Contributor License Agreement (CLA)

Before we can accept your contribution, you will need to sign our Contributor License Agreement (CLA). This is a one-time process for all contributions to BitVM Bridge.

**Why do we need a CLA?**
The CLA is necessary to ensure that the project has the necessary rights to the code you contribute, allowing us to manage the project's intellectual property, defend it against legal challenges, and ensure its long-term sustainability. It protects you, the project, and all its users.

**How to sign?**
When you submit your first Pull Request, a bot (CLA Assistant) will automatically check if you have signed the CLA. If not, it will leave a comment with a link to sign the agreement online. The process is quick and is done via your GitHub account.

## How to Contribute

We welcome many types of contributions, including:
-   New features
-   Bug fixes
-   Documentation improvements
-   Test coverage enhancements

### Development Workflow

1.  **Set up your local environment**. Please follow our [Local Development Guide](./docs/development.md) to get your environment running.
2.  **Fork the repository** and clone it locally.
3.  **Create a new branch** from `develop`: `git checkout -b feature/your-feature-name`.
4.  **Make your changes**.
5.  **Add tests** for your changes. Our project uses Behavior-Driven Development (BDD) for high-level tests, which are described in our testing documentation.
6.  **Run all checks**: `cargo fmt -- --check`, `cargo clippy -- -D warnings`, and `cargo test`.
7.  **Commit your changes** with a descriptive message.
8.  **Push to your fork** and **submit a Pull Request** to the `develop` branch.
