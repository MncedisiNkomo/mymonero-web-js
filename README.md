# MfyMonero Web Wallet 

<p aliwf  gn="center">
  <img alt="MyMonero" src="https://user-images.githubusercontent.com/1645428/146000939-b06f8fd3-9ed2-4a5e-bdd6-3981281dde9c.png">
</p>

<p align="center">
  MyMonero Web Wallet
</p>

<p align="center">
  <a href="https://snyk.io/test/github/mymonero/mymonero-utils"><img src="https://snyk.io/test/github/mymonero/mymonero-web-js/badge.svg"></a>
  <a href="https://opensource.org/licenses/BSD-3-Clause"><img src="https://img.shields.io/badge/License-BSD%203--Clause-blue.svg"></a>
</p>

## Installation

Before installing, [download and install Node.js](https://nodejs.org/en/download/).

Clone the repo and install the dependencies.
```bash
git clone https://github.com/mymonero/mymonero-web-js.git
cd mymonero-web-js
```
```bash
npm install
```
To start the web wallet, run the following
```bash
npm start
```

Optionally, you can override default environment variables by copying the .env.defaults file to .env

Windows:
```bash
copy .env.defaults .env
```
MacOS / Unix:
```bash
cp .env.defaults .env
```


View the web wallet at: http://localhost:9110

## Reporting Bugs & Making Feature Requests

If you would like to report an issue or share a feature request, please create a Github [Issue](https://github.com/mymonero/monero-web-js/issues) on this project.

If you're reporting a bug, be sure to include all information which we would need to reproduce the issue, such as the operating system and app version on which you saw the bug, and the steps you took, if you can tell. 

Please don't use the Issues tracker for general support or inquiries. You can also [contact us](https://mymonero.com/support) directly.

## Testing

Please submit any bugs as Issues unless they have already been reported.

Suggestions and feedback are very welcome!


## Contributing

If you have an improvement to the codebase and would like to have your code shipped in the production MyMonero app, please submit a [pull request](https://help.github.com/articles/about-pull-requests/), even if it's still a WIP. We try to credit all contributors in app release notes.

* Merging PRs which involve integrating with any third-party services will require discussion and agreement.  

* We reserve the right to refuse to merge any PRs, such as those which introduce breaking changes.

## Donating

MyMonero Donation Address (XMR): 48yi8KBxh7fdZzwnX2kFCGALRcN1sNjwBHDfd5i9WLAWKs7G9rVbXNnbJTqZhhZCiudVtaMJKrXxmBeBR9kggBXr8X7PxPT

Proceeds from donations are used to fund development on the MyMonero back-end server (a performant version of which we soon™ plan to open-source for anyone to run their own server at home). Any remaining funds will go towards product (app UI) R&D, and hosting costs.

## License and Copyrights

See `LICENSE.txt` for license.

All app source code and assets copyright © 2014-2020 by MyMonero. All rights reserved.

## Acknowledgements

Contributors to each release are credited in release notes.

### Core Contributors

* 🍕 `Tekkzbadger` ([Devin Pearson](https://github.com/devinpearson)) Lead maintainer; core developer

* 💱 `jkarlos` ([Karl Buys](https://github.com/karlbuys)) Maintainer; core developer

* 🦄 `fluffyponyza` ([Riccardo Spagni](https://github.com/fluffypony)) Advisor; MyMonero founder; Monero core team member

* 🏂 `endogenic` ([Paul Shapiro](https://github.com/paulshapiro)) Former core maintainer; MyMonero core contributor

* 😎 `vtnerd` ([Lee Clagett](https://github.com/vtnerd)) Lead back-end developer

* 🍄 `luigi` Monero tech advisor; Main MyMonero JS core crypto contributor

* 🔥 `mds` ([Matt Smith](http://mds.is)) MVP designer

* 🌠 Your name here?
