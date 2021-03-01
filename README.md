<!-- FIXME: YOUR COPYRIGHT / SPDX LICENSE HEADER -->

# Baseline Protocol DApp [@trufflesuite]

> create-react for etherjs & baseline protocol

[![Build Status](https://travis-ci.com/sambacha/create-eth-enterprise.svg?branch=trufflesuite)](https://travis-ci.com/ilyakmet/solidity-typescript-template)
[![codecov](https://codecov.io/gh/sambacha/create-eth-enterprise/branch/template/graph/badge.svg)](https://codecov.io/gh/ilyakmet/solidity-typescript-template)

## 💼 Baseline Protocol

<!-- FIXME: INTRODUCTION -->

The Baseline Protocol is an open source initiative that combines advances in cryptography, messaging, and blockchain to execute secure and private businessprocesses
at low cost via the public Ethereum Mainnet.

[ethereum-oasis/baseline](https://github.com/ethereum-oasis/baseline)

## 🏢 Overview

<!-- FIXME: OVERVIEW -->

The protocol will enable confidential and complex collaboration between enterprises without leaving any sensitive data on-chain.

## Developer Tools 🛠️

- [Truffle](https://trufflesuite.com/)
- [TypeChain](https://github.com/ethereum-ts/TypeChain)
- [Openzeppelin Contracts](https://openzeppelin.com/contracts/)

## Tested Against

<!-- You can find specific versioning information used here at https://gist.github.com/sambacha/116b0dfc5c99cc8905545d63002b8f94 -->

|    Version    |          Build           | Date <br>(yyyy-mm-dd) |
| :-----------: | :----------------------: | :-------------------: |
| Version 0.6.4 | MDc6UmVsZWFzZTI0MzgwNTQ3 | 2020-03-10T15:26:16Z  |

### Proposal Responsibility:

| Person          | Contact Info             | Responsibility     |
| --------------- | ------------------------ | ------------------ |
| @github_usrname | usr@github_email.com     | Proposal Submitter |
| @github_dev1    | posixmeharder@tycoon.com | Developer          |

## Files

_Explain what is the purpose of each process and process related file in the project._

Click to see file details:

<details>
  <summary>IYIPX.sol</summary>
  <br>

This file does something and its purpose is to do abc.

  <hr>
</details>

<details>
  <summary>deploy-mainnet.sh</summary>
  <br>

This file deploys the contracts on `mainnet`

  <hr>
</details>

<details>
  <summary>myEmailTemplate.ftl</summary>
  <br>

This file does something and its purpose is to do abc.

Image example of the **Rendered** FreeMarker file (if applicable)

  <hr>
</details>

## Usage

Create `.infura` and `.secret` files. Install the dependencies:

```bash
$ yarn
```

### Tests

```bash
$ yarn test
```

### Coverage

```bash
$ yarn coverage
```

### Deploying

Deploy to Rinkeby:

```bash
$ NETWORK=rinkeby yarn deploy
```

### Verifying Contract Code

```bash
$ NETWORK=rinkeby yarn run verify YourContractName
```

_For further deployment templates and options see:_ [Deployment Documentation](docs/deployment.md)

| Method        | Trigger                                                                                    |
| ------------- | :----------------------------------------------------------------------------------------- |
| Truffle       | On creation of a Production Release. <br> Deployed to mainnet `chainid: 1`                 |
| Web3 Provider | On commit to branch with pattern `build/development`. <br> Deployed to `testnet` `ropsten` |

## Changelog

_Store details about the releases of your improvement in the Change Log_

[Improvement Change Log](CHANGELOG.md)

## Informative / Additional Information

<!-- INFORMATION THAT WOULD BE HELPFUL, ETC) -->

_Explanation of other details about the project that may not have been included in the Overview._

Examples:

1. Use cases.
1. Error handling.
1. If there is re-usable code that could be used for other purposes.
1. Explanation of any specific configurations, in-line code or expressions in any of the process files.
1. Explanation of designs and specific configurations.
1. Related documentation that may be contained in another system or the `/docs` folder.

## Additional Support documentation

_See the following for additional support documentation related to building and managing process projects:_

1. [Best Practices and Documentation Patterns](docs/patterns.md)
1. [Helper Scripts and Snippets](docs/helpers.md)

## Terminology / Libraries

A list of terms and libraries used by this project.

| Term        | Acronym | Definition                       |
| ----------- | ------- | -------------------------------- |
| Requestor   |         |                                  |
| Initiator   |         | Another term used for requestor. |
| SafeMath    | Lib     | OpenZeppelin                     |
| Proxy       |         |                                  |
| Margin Rate |         |                                  |
| Stablecoin  |         |                                  |
| Tether      | USDT    | USDT Stablecoin                  |

## Security

| Point of contact | Method             |
| ---------------- | ------------------ |
| persons name     | contact@method.com |

## License

<!-- FIXME: LICENSE -->

This Boilerplte is CC-0 - Public Domain

<!-- Additional information for licenses should be in the SPDX- format -->
