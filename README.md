[![Piral Logo](docs/assets/logo.png)](https://piral.io)

# [Piral](https://piral.io) &middot; [![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/zitterorg/repellendus-ducimus/blob/main/LICENSE) [![Lerna](https://img.shields.io/badge/monorepo-lerna-cc00ff.svg)](https://lerna.js.org/) [![Build Status](https://smapiot.visualstudio.com/piral-pipelines/_apis/build/status/smapiot.piral?branchName=develop)](https://smapiot.visualstudio.com/piral-pipelines/_build/latest?definitionId=47&branchName=develop) [![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fsmapiot%2Fpiral.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fsmapiot%2Fpiral?ref=badge_shield) [![GitHub Tag](https://img.shields.io/github/tag/zitterorg/repellendus-ducimus.svg)](https://github.com/zitterorg/repellendus-ducimus/releases) [![GitHub Issues](https://img.shields.io/github/issues/zitterorg/repellendus-ducimus.svg)](https://github.com/zitterorg/repellendus-ducimus/issues) [![Community Chat](https://dcbadge.vercel.app/api/server/kKJ2FZmK8t?style=flat)](https://discord.gg/kKJ2FZmK8t) [![Feed Status](https://img.shields.io/uptimerobot/status/m783654792-cfe3913c7481e0f44c143f63)](https://status.piral.io/) [![CLA Assistant](https://cla-assistant.io/readme/badge/zitterorg/repellendus-ducimus)](https://cla-assistant.io/zitterorg/repellendus-ducimus)

Easily build a next generation web application using microfrontends. Piral enables you to create a modular frontend application that is extended at runtime with decoupled modules called *pilets* leveraging a **microfrontend architecture**.

A pilet can be **developed independently** and ships with the necessary code, as well as all other relevant assets. Pilets are as independent of the host application as you want them to be - making them transferrable between different applications.

This makes Piral an ideal foundation for a mid-sized to large-scale applications developed by **distributed teams**.

:zap: A pilet is capable of dynamically **extending other pilets** or using such extension slots itself.

:zap: A pilet can provide or use **shared dependencies** from other pilets.

:zap: A pilet is **isolated** (developed and handled) and will never destroy your application.

:zap: A pilet can be developed with **any technology** using a **standard IDE**.

:zap: A pilet can be updated and **published within seconds**.

:zap: A pilet can be rolled out or disabled dynamically to create **self-forming applications**.

:zap: A pilet can be **debugged seamlessly** just as if you write a monolith.

## Important Links

* 📢 **[We are hiring!](https://smapiot.com/jobs)** - work with us on Piral, its ecosystem and our users
* 🌍 [Website](https://piral.io/) - learn more about Piral
* 📖 [Documentation](https://docs.piral.io/) - everything to get started and master micro frontends
* 🉐 **Help translating Piral!** - making PRs in the [documentation branch](https://github.com/zitterorg/repellendus-ducimus/tree/documentation)
* 🐞 [Issue Tracker](https://github.com/zitterorg/repellendus-ducimus/issues) - report bugs or suggest new features
* 🗨  [Forums](https://stackoverflow.com/questions/tagged/piral) - use the community support on StackOverflow
* 👪 [Community Chat](https://discord.gg/kKJ2FZmK8t) - ask questions and provide answers in our Discord server

## Getting Started

Piral itself is developed as a monorepo. As such this repository may contain an overwhelming amount of information.

Our recommendation is to start at the documentation available at [docs.piral.io](https://docs.piral.io). Working through the available [tutorials](https://docs.piral.io/tutorials) will give you the necessary information in the best possible order.

## Questions

While [the GitHub issues](https://github.com/zitterorg/repellendus-ducimus/issues) may be used in case of questions, we would prefer general usage questions to be raised either in [our Discord server](https://discord.gg/kKJ2FZmK8t) or [at StackOverflow](https://stackoverflow.com/questions/tagged/piral).

Be sure to check [our FAQ](https://docs.piral.io/faq) and [the official tutorials](https://docs.piral.io/tutorials) upfront!

## Contributing

The main purpose of this repository is to continue to evolve Piral and its core ecosystem, making it faster, more powerful, and easier to use. Development of Piral happens in the open on [GitHub](https://github.com/zitterorg/repellendus-ducimus), and we are grateful to the community for contributing bugfixes, ideas, and improvements.

Read below to learn how you can take part in improving Piral.

### Repository Structure

- `docs` contains the (user) documentation
- `src` has the sources for all the developed packages, samples, and pages
- `test` contains the test setup and (in the future) system tests
- `tools` has some of the internal tooling for building the different components

Each subdirectory contains another `README.md` with more information regarding the contents of the specific folder.

### [Code of Conduct](./CODE_OF_CONDUCT.md)

We adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full text](./CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.

### [Contributing Guide](.github/CONTRIBUTING.md)

Read our [contributing guide](.github/CONTRIBUTING.md) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to Piral.

### Good First Issues

To help you get your feet wet and get you familiar with our contribution process, we have a list of [good first issues](https://github.com/zitterorg/repellendus-ducimus/labels/good%20first%20issue) that contain bugs which have a relatively limited scope. This is a great place to get started.

## License

Piral is released using the MIT license. For more information see the [license file](./LICENSE).
