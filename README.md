# AURIORA

AURIORA is an open engineering and research ecosystem exploring intelligence, sensing, biological systems, embedded technology and human-machine interaction through open hardware and software.

This repository is the central hub of the ecosystem: the index that helps visitors, contributors and developers understand how AURIORA is structured and find the right repository, standard, guide, module or software project.

- Website: [auriora.org](https://auriora.org)
- GitHub organization: [github.com/auriora-org](https://github.com/auriora-org)

## Purpose of this repository

This repository serves as:

- the central index of the AURIORA ecosystem
- the primary navigation point for repositories
- the location of organization-level information
- a guide for contributors looking for the correct project

It contains no product source code, firmware, hardware design files or duplicated technical documentation. Implementation-specific content belongs in the dedicated repositories listed below.

## Standards and guides

The AURIORA Engineering Standard is the constitutional engineering reference of the platform; the companion guides define domain-specific practice. AES defines *what* must be done during development; the companions define *how* it is done in their domain. Where a companion and AES conflict, AES prevails.

```text
AURIORA Engineering Standard (AES)
├── AURIORA Hardware Design Guide (AHDG)
├── AURIORA Firmware Style Guide (AFSG)
├── AURIORA Software Style Guide (ASSG)
└── AURIORA Documentation Standard (ADS)
```

| ID | Document | Repository | Status |
|---|---|---|---|
| `AES` | AURIORA Engineering Standard | [auriora-engineering-standard](https://github.com/auriora-org/auriora-engineering-standard) | Stable |
| `AHDG` | AURIORA Hardware Design Guide | [auriora-hardware-design-guide](https://github.com/auriora-org/auriora-hardware-design-guide) | Stable |
| `AFSG` | AURIORA Firmware Style Guide | [auriora-firmware-style-guide](https://github.com/auriora-org/auriora-firmware-style-guide) | Stable |
| `ASSG` | AURIORA Software Style Guide | [auriora-software-style-guide](https://github.com/auriora-org/auriora-software-style-guide) | Stable |
| `ADS` | AURIORA Documentation Standard | [auriora-documentation-standard](https://github.com/auriora-org/auriora-documentation-standard) | Stable |

Document identifiers are allocated in the [AES document register](https://github.com/auriora-org/auriora-engineering-standard/blob/main/docs/registers/document-register.md).

## Hardware modules

The first AURIORA module families are in development. Their repositories are published when the designs reach a releasable state; hardware maturity is expressed with the AES compliance levels (Concept, Design, Release Candidate, Released).

| ID | Module | Repository | Status |
|---|---|---|---|
| `AAM-01` | Audio Module — audio stimulation: generates parametric sound patterns and plays back audio samples | Repository planned | Planned |
| `AAC-01` | Audio Controller — controller for the audio module family | Repository planned | Planned |
| `APEM-01` | Plant Electrophysiology Module — measurement of plant electrical signals | Repository planned | Planned |
| `APBM-01` | Plant Photobiology Module — light-based plant stimulation and measurement | Repository planned | Planned |

## Firmware

Module firmware, shared embedded libraries, bootloaders and protocol implementations are published alongside their hardware modules and follow the [AURIORA Firmware Style Guide](https://github.com/auriora-org/auriora-firmware-style-guide). There are no public firmware repositories yet.

## Software

Host-side software — desktop applications, command-line tools, development and test tooling — is published as the modules it supports become public, and follows the [AURIORA Software Style Guide](https://github.com/auriora-org/auriora-software-style-guide). There are no public software repositories yet.

## Research and data

Research notes, experiments, datasets and publications will appear here as public research material becomes available. This area is expected to grow.

## Websites and public resources

| Resource | Location | Status |
|---|---|---|
| AURIORA website | [auriora.org](https://auriora.org) — source in [auriora-website](https://github.com/auriora-org/auriora-website) | Stable |
| GitHub organization | [github.com/auriora-org](https://github.com/auriora-org) — profile in [.github](https://github.com/auriora-org/.github) | Stable |
| Documentation portal | Planned | Planned |

## Repository status legend

- **Active** — under active development
- **Experimental** — early-stage or research-oriented work
- **Stable** — mature and maintained
- **Planned** — repository or project not yet published
- **Archived** — no longer actively maintained

Repository status describes maturity, not commercial availability. For hardware, product maturity is expressed separately with the AES compliance levels.

## Repository naming convention

All public AURIORA repositories follow one naming scheme:

- names are lowercase, words separated by hyphens
- organization-wide repositories use the `auriora-` prefix: `auriora-engineering-standard`, `auriora-website`
- hardware module repositories use the official module identifier: `auriora-aam-01`, `auriora-apem-01`
- names are concise and predictable; no artificial category repositories (`hardware`, `software`) without real content

## Contributing

Identify the correct repository first, read its contribution instructions and open issues where the work belongs. This hub accepts issues only for broken links, missing or incorrect repository entries, and ecosystem structure suggestions — see [CONTRIBUTING.md](./CONTRIBUTING.md).

All AURIORA projects follow the applicable [standards and guides](#standards-and-guides).

## Licensing

Licensing differs by repository and artifact type: hardware design sources, firmware, software and documentation each use licenses appropriate to their domain. Always consult the `LICENSE` file of the repository you are using.

This hub repository is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](./LICENSE), like the AURIORA documentation repositories.

## Contact

- Website: [auriora.org](https://auriora.org)
- Email: [contact@auriora.org](mailto:contact@auriora.org)
- Repository-specific questions: the issue tracker of the repository concerned

## Maintenance rules

For maintainers of this hub:

- every listed repository has a current, factual one-line description
- broken links are removed or corrected
- planned repositories are never presented as active, and archived repositories are marked clearly
- descriptions are not duplicated from the repositories; the hub links, it does not restate
- the hub stays concise — detailed documentation belongs in the dedicated repositories
