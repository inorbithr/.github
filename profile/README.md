<p align="center">
  <a href="https://inorbit.hr">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/inorbithr/.github/main/.github/assets/logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/inorbithr/.github/main/.github/assets/logo-light.svg">
      <img alt="InOrbit logo: the InOrbit mark" src="https://raw.githubusercontent.com/inorbithr/.github/main/.github/assets/logo-light.svg" width="88" height="88">
    </picture>
  </a>
</p>

<h1 align="center">InOrbit</h1>

<p align="center">
  <b>AI engineering that has to prove its work.</b><br>
  Every change ends in evidence someone else can check without trusting the model that made it.
</p>

<p align="center">
  <a href="https://inorbit.hr">Website</a> ·
  <a href="https://docs.inorbit.hr">Docs</a> ·
  <a href="https://inorbit.hr/radar/">Radar</a> ·
  <a href="https://console.inorbit.hr">Console</a>
</p>

---

### The loop we build toward

`understand → observe → model → hypothesize → experiment → change → verify → grade → evidence`

Some steps run today, some in part, some are written down and not built yet. Each one links
to an RFC with a dated status log on [inorbit.hr](https://inorbit.hr), so you can see which.

### Open source here

| Repository | What it is | State |
| --- | --- | --- |
| [**sdk**](https://github.com/inorbithr/sdk) | Client libraries for the InOrbit API and `iohr`, the command line | 0.2.2: Rust, TypeScript, Python and Go on their registries; C# and Java tagged |
| [**dataplane**](https://github.com/inorbithr/dataplane) | The agent that runs checks inside your own network and connects out, so nothing opens inbound | Pre-releases only |
| [**homebrew-tap**](https://github.com/inorbithr/homebrew-tap) | `brew install inorbithr/tap/iohr` | Follows the CLI releases |

### Try it

```sh
brew install inorbithr/tap/iohr
iohr --help
```

### Where we are

Early access. A small company in Croatia (InOrbit d.o.o.), building in the open: what runs is
on the site, and what doesn't is labelled as such. Security reports go to the contact in
[security.txt](https://inorbit.hr/.well-known/security.txt).
