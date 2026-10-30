<p align="center"><a href="https://inorbit.hr">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/inorbithr/.github/main/.github/assets/hero-dark.png">
    <img alt="InOrbit: build and run automated software, keep control of every change" src="https://raw.githubusercontent.com/inorbithr/.github/main/.github/assets/hero-light.png" width="100%">
  </picture>
</a></p>

<p align="center">
  <a href="https://inorbit.hr">inorbit.hr</a> ·
  <a href="https://developers.inorbit.hr/docs/">Docs</a> ·
  <a href="https://rfcs.inorbit.hr">Public RFCs</a> ·
  <a href="https://status.inorbit.hr">Status</a> ·
  <a href="mailto:reach@inorbit.hr">reach@inorbit.hr</a>
</p>

---

InOrbit is one workspace where engineers and AI agents plan, build and run software. A
request or an incident becomes a plan, each change ships through a checked pull request and
a person's approval, and every step keeps its evidence. It is programmable through a
command line, SDKs, MCP and extensions, and its agent runs inside your network and only
connects outward.

We are a small company in Croatia, InOrbit d.o.o., working with partners before the
general release. SOC 2 and ISO 27001 are in preparation; no audit has been completed.

### Open source here

The agent, the SDKs and the command line are open source; the platform is not. The
[open source page](https://inorbit.hr/open-source/) lists them, and our public RFCs are at
[rfcs.inorbit.hr](https://rfcs.inorbit.hr).

| Repository | What it is | Release |
| --- | --- | --- |
| [**dataplane**](https://github.com/inorbithr/dataplane) | The agent that runs checks inside your network and connects outbound only. Its Helm chart is published with it. | [![agent](https://img.shields.io/github/v/release/inorbithr/dataplane?include_prereleases&label=agent&color=ff9e1b)](https://github.com/inorbithr/dataplane/releases) |
| [**sdk**](https://github.com/inorbithr/sdk) | `iohr`, the command line, and SDKs for the InOrbit API: Rust, TypeScript, Python and Go on their registries, C# and Java from source | [![iohr](https://img.shields.io/github/v/release/inorbithr/sdk?include_prereleases&filter=iohr%2F*&label=iohr&color=ff9e1b)](https://github.com/inorbithr/sdk/releases) |
| [**homebrew-tap**](https://github.com/inorbithr/homebrew-tap) | `brew install inorbithr/tap/iohr`, the command line for macOS and Linux | follows the `iohr` releases |

### Try it

```sh
brew trust inorbithr/tap
brew install inorbithr/tap/iohr
iohr login
```

Write to [reach@inorbit.hr](mailto:reach@inorbit.hr) for early access, a pilot or a
partnership. Security reports go to the contact in
[security.txt](https://inorbit.hr/.well-known/security.txt).
