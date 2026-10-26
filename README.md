# dnsrecon Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **dnsrecon cookbook** — DNS enumeration from the command line. Wave-10 tool on Node-1 (wave-10 done except BBOT and certstream). Patterns are planned from the design, not yet from fleet runs. It is intended for Practitioners who enumerate DNS records and zones for authorized domains. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** dnsrecon patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Practitioners who enumerate DNS records and zones for authorized domains.

## Prerequisites

- dnsrecon in the fleet tooling
- An authorized domain
- Bash or PowerShell

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-enum` | Standard enumeration: records, wildcards, and zone walks |
| 02 | `02-bruteforce` | Subdomain brute-forcing with wordlists |
| 03 | `03-output` | Reading XML, JSON, and CSV outputs |

## Repository layout

```text
dnsrecon-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [amass-cookbook](https://github.com/ZQM-Computing/amass-cookbook) — Passive subdomain enumeration and graph output
- [subfinder-cookbook](https://github.com/ZQM-Computing/subfinder-cookbook) — Passive subdomain discovery from public sources
- [theharvester-cookbook](https://github.com/ZQM-Computing/theharvester-cookbook) — Passive reconnaissance: domains, emails, and hosts from public sources
