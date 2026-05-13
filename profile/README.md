<div align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/soteria-tools/.github/blob/main/assets/LOGO-SOTERIA-FULL-WHITE.png?raw=true">
      <source media="(prefers-color-scheme: light)" srcset=".https://github.com/soteria-tools/.github/blob/main/assets/LOGO-SOTERIA-FULL-COLOUR.png?raw=true">
      <img alt="Soteria" src=".https://github.com/soteria-tools/.github/blob/main/assets/LOGO-SOTERIA-FULL-WHITE.png?raw=true" height="100">
    </picture>
</div>

<br />

<div align="center">

**Sound static analysis for the masses.**

Soteria uses symbolic execution to reliably find memory bugs, overflows, data races, and undefined behaviour in **Rust** and **C** codebases — at speeds that fit real development workflows.

[![Website](https://img.shields.io/badge/website-soteria--tools.com-02066f)](https://soteria-tools.com)
[![Stars](https://img.shields.io/github/stars/soteria-tools/soteria?style=flat&color=02066f)](https://github.com/soteria-tools/soteria)
[![Zulip Chat](https://img.shields.io/badge/join-zulip?logo=zulip&label=Zulip&labelColor=%2330363D&color=%232FBC4F)](https://soteria.zulipchat.com/)

</div>

---

### What is Soteria?

Soteria is a static analysis tool built on symbolic execution. It exhaustively explores execution paths in your code to surface bugs that fuzzing and traditional static analysis may miss — with no false positives by design.

- **86.9%** pass rate across Kani & Miri test suites
- **15.8×** faster than CBMC
- **19 pp** boost in LLM violation detection

---

### Key repositories

- [`soteria`](https://github.com/soteria-tools/soteria): The core symbolic execution engine, supporting Rust ([`soteria-rust`](https://github.com/soteria-tools/soteria/tree/main/soteria-rust)) and C ([`soteria-c`](https://github.com/soteria-tools/soteria/tree/main/soteria-c)).
- [`cargo-soteria`](https://github.com/soteria-tools/cargo-soteria): Cargo integration for Rust projects, enabling seamless analysis with `cargo soteria`.

---

<div align="center">

[Documentation](https://soteria-tools.com/docs) · [Getting started](https://soteria-tools.com/getting-started) · [Research](https://soteria-tools.com/research) · [Community](https://soteria.zulipchat.com)

</div>
