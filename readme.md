# Waste2Earn "Waste" ICRC-1 Fungible Token

Ledger Canister ID: [zozfm-uaaaa-aaaaj-qnfkq-cai](https://dashboard.internetcomputer.org/canister/zozfm-uaaaa-aaaaj-qnfkq-cai)

Index Canister ID: [za3ie-pqaaa-aaaaj-qnflq-cai](https://dashboard.internetcomputer.org/canister/za3ie-pqaaa-aaaaj-qnflq-cai)


## Overview
This project is focused on the development and implementation of a fungible token standard, utilizing blockchain or distributed ledger technology. The core of the project is written in Motoko and is compatibility with the DFINITY Internet Computer platform.

## Contents
- `dfx.json`: Configuration file for project settings and canister definitions.
- `mops.toml`: Dependency management file listing various Motoko libraries and tools.
- `src/Token.mo`: Source code for the token system written in Motoko.

## Setup and Installation
1. **Environment Setup**: Ensure you have an environment that supports Motoko programming. This typically involves setting up the [DFINITY Internet Computer SDK](https://internetcomputer.org/docs/current/references/cli-reference/dfx-parent) and [mops tool chain](https://docs.mops.one/quick-start).
2. **Dependency Installation**: Install the dependencies listed in `mops.toml`. `mops install`.
3. **Configuration**: Adjust `dfx.json` and `mops.toml` according to your project's specific needs, such as changing canister settings or updating dependency versions.

## Usage
- **Development**: Modify and enhance `src/Token.mo` as per your requirements. This file contains the logic and structure of the fungible token system.
- **Testing and Deployment**: Use `runners/test_deploy.sh` for deploying the token system to a test or development environment. This script may need modifications to fit your deployment process.
- **Production Deployment**: Use `runners/prod_deploy.sh` for deploying the token system to a main net environment. This script will need modifications to fit your deployment process.

## Dependencies
- DFX and Mops
- Additional dependencies are listed in `mops.toml`. Ensure they are properly installed and configured.

## Contribution and Development Guidelines
- **Coding Standards**: Adhere to established Motoko coding practices. Ensure readability and maintainability of the code.
- **Testing**: Thoroughly test any new features or changes in a controlled environment before integrating them into the main project.
- **Documentation**: Update documentation and comments within the code to reflect changes or additions to the project.

## Repository
- [Project Repository](https://github.com/Wastopia/Waste_Token)


