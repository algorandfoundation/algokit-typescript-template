<div align="center">
<a href="https://github.com/algorandfoundation/algokit-typescript-template"><img src="https://bafybeid5333wj4vvxc3yyif3dzrewowos46sq2vj55r7u3vyhazhoyffo4.ipfs.nftstorage.link/" width=60%></a>
</div>

<p align="center">
    <a target="_blank" href="https://github.com/algorandfoundation/algokit-cli"><img src="https://img.shields.io/badge/docs-repository-00dc94?logo=github&style=flat.svg" /></a>
    <a target="_blank" href="https://developer.algorand.org/algokit/"><img src="https://img.shields.io/badge/learn-AlgoKit-00dc94?logo=algorand&mac=flat.svg" /></a>
    <a target="_blank" href="https://github.com/algorandfoundation/algokit-typescript-template"><img src="https://img.shields.io/github/stars/algorandfoundation/algokit-typescript-template?color=00dc94&logo=star&style=flat" /></a>
    <a target="_blank" href="https://developer.algorand.org/algokit/"><img  src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Falgorandfoundation%2Falgokit-typescript-template&countColor=%2300dc94&style=flat" /></a>
</p>

---

This template provides a beta template for developing and deploying [Algorand TypeScript](https://github.com/algorandfoundation/puya-ts) smart contracts.

~~To use it [install AlgoKit](https://github.com/algorandfoundation/algokit-cli#readme) and then either pass in `-t typescript` to `algokit init` or select the `typescript` template.~~

To use it run:
```
algokit init --template-url https://github.com/algorandfoundation/algokit-typescript-template --UNSAFE-SECURITY-accept-template-url
```

This is one of the official templates used by AlgoKit to initialize an Algorand smart contract project. It's a [Copier template](https://copier.readthedocs.io/en/stable/).

## Features

This template supports the following features:

- Compilation of multiple [Algorand TypeScript](https://github.com/algorandfoundation/puya-ts/) contracts to a [predictable folder location and file layout](template_content/smart_contracts) where they can be deployed; [docs](https://github.com/algorandfoundation/puya-ts/), [examples](https://github.com/algorandfoundation/puya-ts/tree/main/examples)
- Deploy-time immutability and permanence control
- [NPM](https://www.npmjs.com/) for TypeScript packaging and dependency management
- [TypeScript](https://www.typescriptlang.org/) for strongly typed programming language that builds on JavaScript
- [ts-node-dev](https://github.com/wclr/ts-node-dev) for TypeScript deployment script execution
- [Prettier](https://prettier.io/) for code formatting
- [ESLint](https://eslint.org/) for linting
- [vitest](https://vitest.dev/) for automated testing (unit test and end-to-end)
- [better-npm-audit](https://github.com/jeemok/better-npm-audit#readme) for dependency vulnerability scanning
- [pre-commit](https://pre-commit.com/) for managing and maintaining multi-language pre-commit hooks
- VS Code configuration (linting, formatting, breakpoint debugging)
- dotenv (.env) files for configuration
- [Output stability](https://github.com/algorandfoundation/algokit-cli/blob/main/docs/articles/output_stability.md) tests of the TEAL output
- CI/CD pipeline using GitHub Actions

## Getting started

Once the template is instantiated you can follow the [README.md](template_content/README.md.jinja) file to see instructions for how to use the template.

### Interactive Wizard

**To initialize using the `algokit` CLI**:

- Execute the command `algokit init`. This initiates an interactive wizard that assists in selecting the most appropriate template for your project requirements.

**To initialize within GitHub Codespaces**:

- Follow these steps to leverage GitHub Codespaces for template selection:

  1. Go to the [algokit-base-template](https://github.com/algorandfoundation/algokit-base-template) repository.
  2. Initiate a new codespace by selecting the `Create codespace on main` option. This can be found by clicking the `Code` button, then navigating to the `Codespaces` tab.
  3. Upon codespace preparation, `algokit` will automatically start `LocalNet` and present a prompt with the next steps. Executing `algokit init` will initiate the interactive wizard.
