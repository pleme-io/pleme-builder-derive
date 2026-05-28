# pleme-builder-derive

Per-field fluent builder: pub fn with_<field>(mut self, v: <Type>) -> Self. Generated from a tatara-rust-ast PerFieldDeriveSpec.

[![Build](https://github.com/pleme-io/pleme-builder-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-builder-derive.svg)](https://crates.io/crates/pleme-builder-derive)

## Install

```toml
[dependencies]
pleme-builder-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
