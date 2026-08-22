# Quantum Machines

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Quantum Machines is a Tel Aviv, Israel-based quantum control company that
builds the Quantum Orchestration Platform (QOP) — a unified hardware and
software stack for controlling quantum processors at the pulse level. Its
hardware portfolio centers on the OPX+ and OPX1000 controllers, built around
a custom Pulse Processing Unit (PPU) that executes classical control and
real-time feedback alongside arbitrary waveform generation, with
sub-microsecond classical-quantum round trips and 160 ns active reset
latency. The platform is programmed in QUA, the company's pulse-level
domain-specific language, exposed to developers through the qm-qua Python
SDK and an extensive open-source ecosystem under the
[qua-platform](https://github.com/qua-platform) GitHub organization.

Quantum Machines is qubit-modality agnostic, supporting superconducting,
semiconductor spin, trapped-ion, neutral-atom, and color-center systems, and
is used by university labs (MIT, Caltech, Harvard, Princeton, Weizmann) and
quantum startups (Alice & Bob, Diraq, EeroQ). They have partnered with
NVIDIA on DGX Quantum and acquired the Delft-based QHarbor team as a
European R&D hub.

There is no public REST API, OpenAPI specification, or self-service
developer signup; the QOP control surface is reached exclusively via the
qm-qua Python SDK against an OPX/OPX1000 controller (hardware or qm-saas
cloud simulator).

## Links

- Website: https://www.quantum-machines.co
- Documentation: https://docs.quantum-machines.co/latest/
- GitHub: https://github.com/qua-platform
- PyPI (qm-qua): https://pypi.org/project/qm-qua/
- PyPI (qm-saas): https://pypi.org/project/qm-saas/

## APIs / SDKs / Tools

| Name | Type | Description |
|---|---|---|
| [qm-qua Python SDK](https://docs.quantum-machines.co/latest/docs/API_references/qua/dsl_main/) | SDK | Official Python SDK for the QUA pulse-level language |
| [qm-saas](https://pypi.org/project/qm-saas/) | Cloud Simulator | Cloud-hosted OPX simulator |
| [qua-libs](https://github.com/qua-platform/qua-libs) | Library | High-level libraries and reference experiments over QUA |
| [py-qua-tools](https://github.com/qua-platform/py-qua-tools) | Toolbox | Python utilities for QUA experiments (qualang-tools on PyPI) |
| [QUAM](https://github.com/qua-platform/quam) | Framework | Quantum Abstract Machine — object model over QUA |
| [QUAM Builder](https://github.com/qua-platform/quam-builder) | Tool | Builder for QUAM state from wiring/config |
| [QUAlibrate](https://github.com/qua-platform/qualibrate) | Calibration | User-programmable calibration for large-scale quantum computers |
| [QUAlibrate App](https://github.com/qua-platform/qualibrate-app) | Web App | TypeScript front-end for QUAlibrate |
| [QUAlibrate Core](https://github.com/qua-platform/qualibrate-core) | Library | Core calibration node/graph abstractions |
| [QUAlibrate Runner](https://github.com/qua-platform/qualibrate-runner) | Service | Executes QUAlibrate calibration graphs |
| [QUAlibrate Config](https://github.com/qua-platform/qualibrate-config) | Config | Configuration management for QUAlibrate |
| [QUAlibration Libraries](https://github.com/qua-platform/qualibration-libs) | Library | Calibration graph building blocks |
| [QUA Dashboards](https://github.com/qua-platform/qua-dashboards) | Visualization | Interactive dashboards for QUA experiments |

## Hardware

- OPX+ — ultra-fast quantum controller
- OPX1000 — modular high-density hybrid control platform
- Octave — up/down conversion to 18 GHz
- QDAC-II / QDAC-II Compact — ultra-low-noise DACs
- QSwitch — software-controlled breakout box
- QBox — 24-channel breakout box
- QCage / QBoard / QFilter — cryogenic control components

## Tags

Quantum Computing, Quantum Control, Pulse Level Programming, QUA, OPX,
OPX1000, QOP, Quantum Orchestration Platform, Pulse Processing Unit,
Real Time Feedback, Arbitrary Waveform Generation, Superconducting Qubits,
Trapped Ions, Neutral Atoms, Color Centers, Cryogenic Electronics,
Hardware, Israel
