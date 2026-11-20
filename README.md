<h1 align="center">
  <a href="https://linuxfabrik.ch" target="_blank">Linuxfabrik</a> Standards
</h1>
<p align="center">
  The rules and files that all Linuxfabrik repositories share.
  <span>&#8226;</span>
  <b>made by <a href="https://linuxfabrik.ch/">Linuxfabrik</a></b>
</p>
<div align="center">

![License](https://img.shields.io/github/license/linuxfabrik/standards)
![GitHub Issues](https://img.shields.io/github/issues/linuxfabrik/standards)
[![GitHubSponsors](https://img.shields.io/github/sponsors/Linuxfabrik?label=GitHub%20Sponsors)](https://github.com/sponsors/Linuxfabrik)
[![PayPal](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7AW3VVX62TR4A&source=url)

</div>

<br />

# Linuxfabrik Standards

This repository holds no code. It is the single source of what the Linuxfabrik repositories have in common: how to write commit messages and changelog entries, what a pull request covers, how tests are treated, how the CI supply chain is pinned, and the rules for contributions made with AI assistance.

Each Linuxfabrik repository carries a copy of these rules at the top of its `CONTRIBUTING.md`, so they can be read where the work happens. The copies are not edited by hand: a change is made here and reaches every repository as a pull request.


## Contents

| File | What it is |
|---|---|
| [CONTRIBUTING.md](CONTRIBUTING.md) | The shared rules (the "Linuxfabrik Standards" block), followed by the rules for changing them. |
| [AGENTS.md](AGENTS.md), [CLAUDE.md](CLAUDE.md), [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md), [LICENSE](LICENSE), [.github/FUNDING.yml](.github/FUNDING.yml), [.github/pre-commit/](.github/pre-commit/) | Files that are byte-identical in every Linuxfabrik repository. |


## Repositories

The standards apply to these repositories:

- [checklistfabrik](https://github.com/Linuxfabrik/checklistfabrik)
- [firewallfabrik](https://github.com/Linuxfabrik/firewallfabrik)
- [icingaweb2-module-generictts](https://github.com/Linuxfabrik/icingaweb2-module-generictts)
- [icingaweb2-theme-linuxfabrik](https://github.com/Linuxfabrik/icingaweb2-theme-linuxfabrik)
- [kickstart](https://github.com/Linuxfabrik/kickstart)
- [lfops](https://github.com/Linuxfabrik/lfops)
- [lib](https://github.com/Linuxfabrik/lib)
- [mcp-server-icinga](https://github.com/Linuxfabrik/mcp-server-icinga)
- [monitoring-plugins](https://github.com/Linuxfabrik/monitoring-plugins)
- [packaging](https://github.com/Linuxfabrik/packaging)
- [standards](https://github.com/Linuxfabrik/standards)

Forks of other projects (`ansible-freeipa`, `fwbuilder`, `icingaweb2-module-director`) keep their upstream files, so patches can go back upstream.


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). A proposal for a new or changed rule is welcome as an issue or a pull request.
