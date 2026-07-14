# EVM Hack PoCs

A public collection of EVM exploit proof-of-concept (PoC) archives for security research, education, and tooling.

These PoCs are generated from [evm-hack-registry](https://github.com/sanbir/evm-hack-registry) data and are intended to be used with [evm-hack-analyzer](https://github.com/sanbir/evm-hack-analyzer).

This repository contains **exactly the same data** shown on the [crypto.training hacks pages](https://crypto.training/hacks/).

## What is in this repo?

Each file is a ZIP archive named like:

```text
YYYY-MM-ProtocolName.zip
```

A typical archive includes:

| Path | Purpose |
|------|---------|
| `poc-data/runner.json` | Structured exploit / runner metadata for analysis |
| `anvil_state.json` | Snapshot state for local reproduction |
| `sources/` | Relevant contract sources used by the PoC |

There are hundreds of historical and recent DeFi / EVM hack PoCs spanning from early multi-sig incidents through modern protocol exploits.

## How to use these PoCs

1. Clone or download this repository.
2. Open a PoC ZIP in [evm-hack-analyzer](https://github.com/sanbir/evm-hack-analyzer).
3. Explore the vulnerability model, execution steps, and related sources.

You can also browse the same dataset interactively at:

- [https://crypto.training/hacks/](https://crypto.training/hacks/)

## Contribute your own research

You can analyze your own hack in [evm-hack-analyzer](https://github.com/sanbir/evm-hack-analyzer), mark the vulnerability and the exploit execution steps, then:

1. Save your PoC as a ZIP
2. Open a pull request against this repository: [sanbir/evm-hack-poc](https://github.com/sanbir/evm-hack-poc)

The most valuable and interesting PoCs will be merged so the whole community can benefit from your research.

### Optional: publish on IPFS

You can also publish your PoC on IPFS if you want your research to be truly decentralized.

## Expanding beyond DeFiHackLabs

We plan to expand our hack PoC research beyond the original [SunWeb3Sec/DeFiHackLabs](https://github.com/SunWeb3Sec/DeFiHackLabs) PoCs.

Your contributions are really welcomed and much appreciated.

## Ecosystem

| Project | Role |
|---------|------|
| [evm-hack-registry](https://github.com/sanbir/evm-hack-registry) | Source registry / structured hack data |
| [evm-hack-analyzer](https://github.com/sanbir/evm-hack-analyzer) | Analyzer UI & tooling to inspect and annotate exploits |
| [evm-hack-poc](https://github.com/sanbir/evm-hack-poc) (this repo) | Shareable PoC ZIP archives for the community |
| [crypto.training/hacks](https://crypto.training/hacks/) | Public browsable mirror of this dataset |

## Disclaimer

These materials are for **educational and defensive security research only**.

- Do not use this content to attack live systems or steal funds.
- Always follow applicable law and responsible disclosure practices.
- Reproducing historical exploits should be done in local / forked environments only.
