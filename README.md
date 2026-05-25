# Quantum Machines

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
