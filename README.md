<h1 align="center">typescript-eslint</h1>

<p align="center">Monorepo for typescript-eslint: powerful static analysis for JavaScript and TypeScript</p>

<p align="center">
    <img src="https://github.com/typescript-eslint/typescript-eslint/workflows/CI/badge.svg" alt="CI" />
    <a href="https://opencollective.com/typescript-eslint"><img src="https://opencollective.com/typescript-eslint/all/badge.svg?label=financial+contributors&style=flat-square" alt="Financial Contributors on Open Collective" /></a>
    <a href="https://www.npmjs.com/package/@typescript-eslint/typescript-estree"><img src="https://img.shields.io/npm/dm/@typescript-eslint/typescript-estree.svg?style=flat-square" alt="NPM Downloads" /></a>
    <a href="https://codecov.io/gh/typescript-eslint/typescript-eslint"><img alt="Codecov" src="https://img.shields.io/codecov/c/github/typescript-eslint/typescript-eslint.svg?style=flat-square"></a>
</p>

<!-- markdownlint-disable MD033 -->
<p align="center">
👇
</p>

## 🧭 MAOS v1 Governance (Activ8-AI Fork)

This fork operates under MAOS v1 (Modular Automation Operating System) governance framework, which establishes:

- **Tier 3 Repository Classification**: Full governance controls with automated agent workflows
- **Charter Compliance**: All changes must align with Charter Standards for security, modularity, and provider-agnostic design
- **Fail-Closed Enforcement**: Required governance checks must pass before merge
- **Human Authority**: All merges require explicit human approval
- **Audit Trail**: Comprehensive logging and compliance tracking

### Fork-Specific Governance

This is an Activ8-AI maintained fork of [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint).

**Upstream Synchronization**:

- Regular syncs with upstream TypeScript ESLint repository
- Activ8-AI specific modifications tracked separately
- Governance requirements apply to Activ8-AI changes only

**Contribution Guidelines**:

- Upstream contributions should be made to the original TypeScript ESLint repository
- Activ8-AI specific features require governance approval
- See main repository [Activ8-AI/mcp](https://github.com/Activ8-AI/mcp) for governance details

For complete governance documentation, see:

- **Main Repository**: [Activ8-AI/mcp](https://github.com/Activ8-AI/mcp) - Primary governance standards
- **Upstream**: [typescript-eslint/typescript-eslint](https://github.com/typescript-eslint/typescript-eslint) - Original project
- **Documentation**: [typescript-eslint.io](https://typescript-eslint.io) - Official docs
- **Main Branch Docs**: [main--typescript-eslint.netlify.app](https://main--typescript-eslint.netlify.app) - Canary release docs

### High-Risk Powers

This TypeScript linting and analysis tooling has specific governance requirements:

- **Code Analysis**: Powerful static analysis of JavaScript and TypeScript codebases
- **AST Manipulation**: Direct access to Abstract Syntax Tree for code transformation
- **Custom Lint Rules**: Ability to create and enforce custom linting rules
- **TypeScript Integration**: Deep integration with TypeScript compiler and type system
- **CI/CD Integration**: Automated code quality gates in build pipelines
- **Editor Integration**: Real-time code analysis in IDEs and editors
- **Codebase Scanning**: Comprehensive scanning of entire codebases
- **Auto-fixing**: Automated code modifications and fixes
- **Configuration Management**: Control over linting rules and standards
- **Parser Extensions**: Custom parsers and language support
- **Plugin System**: Extensible plugin architecture
- **Type Checking**: Integration with TypeScript type checking
- **Build Process**: Impact on build times and developer workflow
- **Code Standards**: Enforcement of coding standards across teams

All high-risk operations are:

- Gated behind required human approval
- Logged for audit compliance
- Subject to automated security scanning
- Governed by principle of least privilege
- Require secure credential management

### Security Notes

- **Custom Rules**: Review custom lint rules for security implications
- **Auto-fixing**: Carefully test auto-fix rules to avoid unintended code changes
- **CI/CD Integration**: Ensure lint failures don't block critical deployments unnecessarily
- **Configuration Security**: Protect ESLint configuration files from unauthorized changes
- **Plugin Vetting**: Review third-party plugins for security vulnerabilities
- **Parser Safety**: Validate custom parsers don't introduce security issues
- **Build Performance**: Monitor impact on build times and developer productivity
- **Rule Disabling**: Restrict ability to disable important security rules
- **Code Scanning**: Be aware of sensitive code exposure during scanning
- **Access Control**: Limit who can modify linting configurations
- **Version Control**: Track changes to linting rules and configurations
- **Documentation**: Maintain clear documentation of custom rules and standards
- **Testing**: Thoroughly test custom rules before deployment
- **Dependency Management**: Keep dependencies updated for security patches

<p align="center">
  See <strong><a href="https://typescript-eslint.io">typescript-eslint.io</a></strong> for documentation on the latest released version.
</p>
<p align="center">
<small>
  See <strong><a href="https://main--typescript-eslint.netlify.app">main--typescript-eslint.netlify.app</a></strong> for documentation on the latest <a href="https://main--typescript-eslint.netlify.app/users/versioning">canary release</a>.
</small>
</p>
<p align="center">
👆
</p>
<!-- markdownlint-enable MD033 -->

## Code Contributors

This project exists thanks to the awesome people who contribute code and documentation:

<a href="https://github.com/typescript-eslint/typescript-eslint/graphs/contributors"><img alt="Gallery of all contributors' profile photos" src="https://opencollective.com/typescript-eslint/contributors.svg?width=890&button=false" /></a>

🙏 An extra special thanks goes out to the wonderful people listed in <https://github.com/typescript-eslint/typescript-eslint/graphs/contributors>.

## Financial Contributors

In addition to submitting code and documentation updates, you can help us sustain our community by becoming a financial contributor [[Click here to contribute - every little bit helps!](https://opencollective.com/typescript-eslint/contribute)]

<a href="https://www.netlify.com">
  <img src="https://www.netlify.com/img/global/badges/netlify-light.svg" alt="Deploys by Netlify" />
</a>

## License

typescript-eslint inherits is licensed under a permissive MIT license.
