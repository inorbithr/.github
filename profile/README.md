<p align="center"><a href="https://inorbit.hr">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/inorbithr/.github/main/.github/assets/hero-dark.png">
    <img alt="InOrbit: understand your system, detect what breaks, prove what fixes it" src="https://raw.githubusercontent.com/inorbithr/.github/main/.github/assets/hero-light.png" width="100%">
  </picture>
</a></p>

<p align="center">
  <a href="https://inorbit.hr">inorbit.hr</a> ·
  <a href="https://inorbit.hr/#tour">The tour, 3 min</a> ·
  <a href="https://docs.inorbit.hr">Docs</a> ·
  <a href="https://inorbit.hr/#pace">Public RFCs</a> ·
  <a href="mailto:reach@inorbit.hr">reach@inorbit.hr</a>
</p>

---

InOrbit is an engineering platform that connects your code, your architecture decisions,
your monitoring and what actually runs. It detects failures, carries an incident from the
monitor that saw it to the fix, and measures whether a change did what it claimed, whether a
person or an AI agent made it. Atlas, the evidence-backed map of your system, is in
development. We are a small company in Croatia, InOrbit d.o.o., in early access with
partners: what runs is marked live, and what does not is marked as such.

### The products

**Understand**

| Product | What it is | Status |
|---|---|---|
| [Atlas, the map](https://inorbit.hr/#atlas) | An evidence-backed model of your system | in development |
| [Decisions](https://inorbit.hr/#pace) | PRDs, ADRs and RFCs, linked to the code | preview |
| [Ask your system](https://inorbit.hr/#atlas) | Answers with the sources behind them | coming |

**Operate and verify**

| Product | What it is | Status |
|---|---|---|
| [Monitors](https://inorbit.hr/products/monitors/) | Endpoints checked on a schedule | live |
| [Incidents and postmortems](https://inorbit.hr/products/incidents/) | Impact measured on the monitor; acknowledge from the phone | preview |
| [chaos verify](https://inorbit.hr/#proof) | Changes measured before and after they roll | preview |
| [The evidence record](https://inorbit.hr/#proof) | One record per change, checkable by anyone | preview |

**Ways in**

| Product | What it is | Status |
|---|---|---|
| [The agent in your network](https://inorbit.hr/products/agent/) | Reads for Atlas; connects outbound only | preview |
| [Connections](https://inorbit.hr/#incidents) | Your tools feed the same evidence | in part |
| [Phone app](https://inorbit.hr/#elsewhere) | iPhone and Android | preview |
| [Browser extension](https://inorbit.hr/#elsewhere) | Record a flow, turn it into a test | preview |
| [One API: REST, MCP, SDKs and the CLI](https://docs.inorbit.hr/docs/reference/) | Every transport on the same routes | live |


Statuses are the ones on [inorbit.hr](https://inorbit.hr): live means anyone with access
uses it today, preview means it runs for partners or as a pre-release.

### Open source here

The agent, the SDKs and the command line are open source; the platform is not. Our public
RFCs, with a dated log of what landed, are on [inorbit.hr](https://inorbit.hr/#pace).

| Repository | What it is | Release |
| --- | --- | --- |
| [**dataplane**](https://github.com/inorbithr/dataplane) | The agent that runs in your network: checks from inside, connects outbound only. Its Helm chart is published with it. | [![agent](https://img.shields.io/github/v/release/inorbithr/dataplane?include_prereleases&label=agent&color=ff9e1b)](https://github.com/inorbithr/dataplane/releases) |
| [**sdk**](https://github.com/inorbithr/sdk) | SDKs for the InOrbit API (Rust, TypeScript, Python and Go, with C# and Java from source) and `iohr`, the command line | [![iohr](https://img.shields.io/github/v/release/inorbithr/sdk?include_prereleases&filter=iohr%2F*&label=iohr&color=ff9e1b)](https://github.com/inorbithr/sdk/releases) |
| [**homebrew-tap**](https://github.com/inorbithr/homebrew-tap) | `brew install inorbithr/tap/iohr`, the command line for macOS and Linux | follows the `iohr` releases |

### Try it

```sh
brew install inorbithr/tap/iohr
iohr login
```

Write to [reach@inorbit.hr](mailto:reach@inorbit.hr) for early access, a pilot or a
partnership. Security reports go to the contact in
[security.txt](https://inorbit.hr/.well-known/security.txt).
