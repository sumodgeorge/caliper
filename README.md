# ![Hyperledger Caliper](https://wiki.hyperledger.org/download/attachments/2392434/Hyperledger_Caliper_Logo_Color.svg?version=1&modificationDate=1548883186000&api=v2)

[![CI](https://github.com/hyperledger-caliper/caliper/actions/workflows/main.yml/badge.svg)](https://github.com/hyperledger-caliper/caliper/actions/workflows/main.yml)
[![codecov](https://codecov.io/gh/hyperledger/caliper/branch/main/graph/badge.svg?token=rVFhTNrZBJ)](https://codecov.io/gh/hyperledger/caliper)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/2381/badge)](https://bestpractices.coreinfrastructure.org/projects/2381)
[![license](https://img.shields.io/badge/license-Apache%202.0-blue)](https://github.com/hyperledger-caliper/caliper/blob/main/LICENSE)
[![node (scoped)](https://img.shields.io/node/v/@hyperledger/caliper-cli)](https://www.npmjs.com/package/@hyperledger/caliper-cli)
[![npm (scoped)](https://img.shields.io/npm/v/@hyperledger/caliper-cli?label=version)](https://www.npmjs.com/package/@hyperledger/caliper-cli)
[![npm](https://img.shields.io/npm/dt/@hyperledger/caliper-cli?label=npm%20downloads)](https://www.npmjs.com/package/@hyperledger/caliper-cli)
[![Docker Pulls](https://img.shields.io/docker/pulls/hyperledger/caliper)](https://hub.docker.com/r/hyperledger/caliper)
[![Discord.Chat](https://img.shields.io/badge/discord-caliper-red)](https://discord.com/channels/905194001349627914/941417677778473031)
[![Mailing list](https://img.shields.io/badge/mailing%20list-caliper-blue)](https://lists.hyperledger.org/g/caliper/topics)

Welcome to the Hyperledger Caliper project. Caliper is a blockchain performance benchmark framework, which allows users to test different blockchain solutions with predefined use cases, and get a set of performance test results.

Currently supported blockchain solutions:

* [Hyperledger Fabric v1.X, v2.X](https://github.com/hyperledger/fabric)

Currently supported performance indicators:
* Success rate
* Transaction/Read throughput
* Transaction/Read latency (minimum, maximum, average)
* Resource consumption (CPU, Memory, Network IO, ...)

See the [PSWG white paper](https://www.hyperledger.org/learn/publications/blockchain-performance-metrics) to find out the definitions and corresponding measurement methods.

For more information on using Caliper, please consult the [documentation site](https://hyperledger-caliper.github.io/caliper/)

## Configuration and usage
See the [related documentation page](https://hyperledger-caliper.github.io/caliper/).

## How to contact us

If you have any issues using Caliper that the documentation does not help you solve, please reach out to us through the following methods:
* [Discord](https://discord.com/channels/905194001349627914/941417677778473031) Please feel free to contact us on Discord (instant messaging). We monitor the Caliper channels as closely as possible, but even if you don't have a problem that needs resolving, why not jump on and say hi ... we'd love to hear from you about your experiences and any new features you think we should work on.
* [Issues](https://github.com/hyperledger-caliper/caliper/issues) Feel free to raise an issue if you are facing a Caliper related problem

Caliper interacts with multiple blockchain technologies and consequently it *might* be an issue with the underlying blockchain technology being interacted with. You can seek specific help on these technologies on the same Discord server such as the Fabric or Besu channels.

## How to contribute

We welcome contributions to the Caliper code base. Please see [Contributing](/CONTRIBUTING.md) for more information.

## License
Hyperledger Project source code files are made available under the Apache License, Version 2.0 (Apache-2.0), located in the [LICENSE](LICENSE) file. Hyperledger Project documentation files are made available under the Creative Commons Attribution 4.0 International License (CC-BY-4.0), available at http://creativecommons.org/licenses/by/4.0/.
