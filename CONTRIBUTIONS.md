## Contributing to Vibekit

Thanks for your interest in contributing to Vibetkit! This guide explains how to make valuable contributions to the project.

## Getting Started

Before you start your work, checkout [open issues](https://github.com/EmberAGI/arbitrum-vibekit/issues) to see if someone is already working on the same topic. For big changes or new features, create an issue first to avoid duplicate work, though it's not required for smaller updates.

## Expanding Protocol Support (Integrating New Plugins)

Vibekit supports DeFi protocol integrations through the Ember plugin system. This standardized architecture enables adding support for protocols with swap, lending, and liquidity capabilities.

### Quick Overview

The plugin system supports:

- **Swap Operations**: Token swapping across DEXs
- **Lending Operations**: Borrow, repay, supply, and withdraw on lending protocols
- **Liquidity Operations**: Provide and withdraw liquidity from pools

### Getting Started

1. **Create an Issue**: Navigate to the [Vibekit issues board](https://github.com/EmberAGI/arbitrum-vibekit/issues) to create a new issue detailing the protocol you intend to integrate.

2. **Review Plugin Documentation**: Check the comprehensive [Ember Plugin README](https://github.com/EmberAGI/arbitrum-vibekit/tree/main/typescript/lib/ember-plugin) for detailed implementation guidelines, architecture overview, and code examples.

3. **Study Existing Implementations**: Examine existing plugins and action implementations in the `typescript/lib/ember-plugin/` directory for reference patterns.

## Development Steps

**1. Fork & Clone the Repository:**

- **Fork the Repository:** Start by creating your own copy of the [Vibekit repository](https://github.com/EmberAGI/arbitrum-vibekit) on GitHub.

- **Clone Your Fork:** After forking, clone your forked repository to your local machine to begin development. You can do this by running `git clone https://github.com/YOUR_USERNAME/arbitrum-vibekit.git` (replace `YOUR_USERNAME` with your GitHub username).

**2. Review MCP Tools Guidelines:** Checkout the [README.md](https://github.com/EmberAGI/arbitrum-vibekit/tree/main/typescript/lib/mcp-tools) file in the `mcp-tools` directory for guidance on developing MCP tools.

**3. Implement Changes:** Add new tools or improve existing ones.

**4. Create Documentation:** Create a `README` file for your new MCP tool that clearly explains its functionality and setup process.

**5. Create Example Agents:** Consider adding a demo agent to the [templates directory](https://github.com/EmberAGI/arbitrum-vibekit/tree/main/typescript/templates) to showcase your new features.

**6. Provide Comprehensive Testing:** Ensure your implementation includes thorough testing coverage, which is a key quality metric we evaluate.

**7. Update CHANGELOG:** Document your modifications in [CHANGELOG.md](https://github.com/EmberAGI/arbitrum-vibekit/blob/main/CHANGELOG.md) to keep the project's history clear.

## Submitting Your Work

When preparing your pull request (PR), be sure to link any relevant issues to provide context. Make sure your code passes all testing and linting requirements as well.

## Review Process

After you submit your PR, we'll acknowledge it within 2–3 days to let you know it's being reviewed. You can expect initial feedback or requested changes from us within 5 days. Once all feedback is addressed and your PR is approved, your contribution will be merged.

## Getting Support

If you need assistance at any step of the contribution process:

- Search [existing issues](https://github.com/EmberAGI/arbitrum-vibekit/issues) for similar questions or problems.
- If your concern isn't already covered, create a new issue with detailed information.
- Reach out to our team for guidance.
- Join our [support Discord](https://discord.com/invite/bgxWQ2fSBR) and connect with other builders.
