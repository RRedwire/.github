<p align="center">
  <kbd>
    <img width="150" src="https://red-wire.org/assets/img/redwire-mark.png" alt="RedWire" />
  </kbd>
</p>

<h1 align="center">RedWire</h1>

<p align="center">
  <a href="https://discord.gg/JjdQaNJ3Rj"><img height="30" src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/RRedwire"><img height="30" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://red-wire.org"><img height="30" src="https://img.shields.io/badge/Website-E5485B?style=for-the-badge&logo=firefox&logoColor=white" alt="Website" /></a>
  <a href="https://red-wire.org/docs"><img height="30" src="https://img.shields.io/badge/Docs-E5485B?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Documentation" /></a>
</p>

**Website:** https://red-wire.org  
**Documentation:** https://red-wire.org/docs

### About

RedWire is an organization building open, self-hostable browsing infrastructure: web proxy services, the
transport stack behind them and the browser tooling around them.

Our projects focus on practical deployment. Every service ships with source, a reference deployment and a
path to run it yourself. No ads, no account system and no upstream dependency you cannot replace.

The stack builds on [Ultraviolet](https://github.com/titaniumnetwork-dev/Ultraviolet),
[BareMux](https://github.com/MercuryWorkshop/bare-mux), [Epoxy](https://github.com/MercuryWorkshop/epoxy-tls)
and [WISP](https://github.com/MercuryWorkshop/wisp-protocol); the service and deployment layer is
maintained here.

### Services

#### Browsing

- [RedProxy](https://redproxy.org) — the hosted browsing proxy. Ultraviolet rewriting, Epoxy over WISP and no account.
- [Redline](https://red-wire.org/browse/) — the reference self-hosted stack: shell, worker, BareMux, Epoxy/WISP and a Node relay.

#### UBG

- [Infrared](https://infrared.earth) — the UBG site. An experimental proxy with games, apps, tab cloaking and ad-free deployment.

#### Games

- [RedArcade](https://red-wire.org/play/) — four original browser games. No accounts, ads or installs.

#### WebOS

- [RedOS](https://github.com/Red60sapphire/redos) — a desktop in a tab, with a terminal and Linux emulation. In development.

#### Infrastructure

- [Signal](https://red-wire.org/services/signal/) — manifest-driven link hub
- [RedKit](https://red-wire.org/docs/#redkit) — client bootstrap for adding a proxy to any site
- [RedRelay](https://red-wire.org/company/#roadmap) — hardened WISP relay (planned)
- [Mirror](https://red-wire.org/company/#roadmap) — fleet manager for Redline instances (planned)
- [Beacon](https://red-wire.org/status/) — browser-side reachability checks

### Projects

<details>
<summary>Overview</summary>

#### Active

##### Proxies

- [RedProxy](https://redproxy.org) — hosted browsing proxy
- [Redline](https://github.com/RRedwire/red-wire/tree/main/services/redline) — reference Ultraviolet + BareMux + Epoxy/WISP deployment
- [Infrared](https://github.com/OGsWorkshop/Infrared) — the UBG site

##### Services

- [RedArcade](https://red-wire.org/play/) — static games portal and four original games
- [RedOS](https://github.com/Red60sapphire/redos) — browser desktop
- [Signal](https://github.com/RRedwire/red-wire/tree/main/services/signal) — manifest-driven link hub
- [Beacon](https://red-wire.org/status/) — client-side status checks

##### Tooling

- [RedKit](https://github.com/RRedwire/red-wire/tree/main/packages/redkit) — proxy client bootstrap

#### Planned

- [RedRelay](https://red-wire.org/company/#roadmap) — hardened WISP relay
- [Mirror](https://red-wire.org/company/#roadmap) — multi-instance fleet manager

#### Upstream

- [Ultraviolet](https://github.com/titaniumnetwork-dev/Ultraviolet) — service-worker proxy core
- [BareMux](https://github.com/MercuryWorkshop/bare-mux) — transport abstraction
- [Epoxy](https://github.com/MercuryWorkshop/epoxy-tls) — encrypted transport
- [WISP](https://github.com/MercuryWorkshop/wisp-protocol) — WebSocket stream protocol

</details>

### Partners

RedWire is developed in partnership with [OGsWorkshop](https://github.com/OGsWorkshop), the studio behind
Infrared and RedOS.

### License

AGPL-3.0 unless a repository says otherwise. Upstream projects retain their own licenses.
