# Vijit Singh

**Software engineering generalist — applications, infrastructure, and connected hardware.**

I build software that connects useful interfaces with the systems behind them:
web applications, developer tools, Linux infrastructure, and Raspberry Pi devices.
I care about clear design, reliable operation, and shipping projects with tests,
documentation, and repeatable installation.

[Selected work](#selected-work) · [Command-line tools](#sharp-little-tools) · [All repositories](https://github.com/VijitSingh97?tab=repositories)

## Selected work

### [Pithead](https://github.com/p2pool-starter-stack/pithead) · Infrastructure & application development

A self-hosted Monero and Tari mining stack with an operator dashboard, a CLI,
and a bootable Linux appliance. The project connects containerized services with
validated configuration, operational telemetry, authenticated browser controls,
and backup and recovery workflows.

**Stack:** Python, Bash, Docker Compose, Linux, Tor.

[Documentation](https://github.com/p2pool-starter-stack/pithead#readme) · [Releases](https://github.com/p2pool-starter-stack/pithead/releases)

### [Hidden Acres RV Park](https://github.com/VijitSingh97/HiddenAcresRV) · Web development

A Gatsby-to-Hugo rebuild of an RV park website. It uses semantic HTML, responsive
images, keyboard-accessible navigation, and structured metadata. Content is
separated from templates so routine edits do not require code changes; automated
build, link, and SEO checks support deployment to GitHub Pages.

**Stack:** Hugo, HTML, CSS, GitHub Actions.

[Architecture](https://github.com/VijitSingh97/HiddenAcresRV/blob/master/docs/ARCHITECTURE.md) · [Testing](https://github.com/VijitSingh97/HiddenAcresRV/blob/master/docs/TESTING.md)

### [LoRa Ranch Sentinel](https://github.com/VijitSingh97/gate-checker) · Embedded & distributed systems

A gate-monitoring system for properties without Wi-Fi or cellular coverage at the
edge. Raspberry Pi devices send encrypted sensor events over LoRa to a base
station, which stores events in SQLite and provides Telegram alerts and controls.
The project includes device provisioning, replay protection, watchdogs, and custom
Linux image builds.

**Stack:** Python, Raspberry Pi, LoRa, SQLite, Buildroot.

[User guide](https://github.com/VijitSingh97/gate-checker/blob/main/docs/USER_GUIDE.md) · [Build guide](https://github.com/VijitSingh97/gate-checker/blob/main/docs/BUILDING.md)

### [basis](https://github.com/VijitSingh97/quant) · Data engineering & research tooling

A Python toolkit for studying crypto funding carry and volatility strategies.
It brings together market-data collection, backtests, walk-forward checks,
monitoring, and a paper-first execution workflow with a SQLite audit trail.
The emphasis is on reproducible analysis and explicit execution boundaries.

**Stack:** Python standard library, SQLite, HTTP APIs.

[User guide](https://github.com/VijitSingh97/quant/blob/main/GUIDE.md) · [Execution design](https://github.com/VijitSingh97/quant/blob/main/README_live.md)

## Sharp little tools

Small utilities with documented interfaces, automated tests, versioned releases,
and package installation.

| Tool | Purpose | Platforms |
| --- | --- | --- |
| [cpath](https://github.com/VijitSingh97/cpath) | Copy a file or directory's absolute path to the clipboard. | macOS, Ubuntu, Debian |
| [ogr](https://github.com/VijitSingh97/ogr) | Open a Git repository or its current branch in the browser. | macOS, Ubuntu, Debian |
| [starlink](https://github.com/VijitSingh97/starlink) | List Starlink router clients as a sortable table or JSON. | macOS, Ubuntu, Debian |
| [easydd](https://github.com/VijitSingh97/easydd) | Write disk images to external drives with progress and startup/source disk checks. | macOS |

All four install through Homebrew. **cpath**, **ogr**, and **starlink** also have
signed APT repositories. Installation and shell completion details are in each
project's README.

## More engineering work

- [RigForge](https://github.com/p2pool-starter-stack/rigforge) — Linux worker provisioning, CPU tuning, service health, and recovery around XMRig.
- [Bitcoin Starter Stack](https://github.com/VijitSingh97/bitcoin-starter-stack) — A Tor-routed Bitcoin node with a dashboard, operational alerts, backups, and multi-architecture container releases.

[Explore the repositories](https://github.com/VijitSingh97?tab=repositories) for source code, design notes, tests, and release history.
