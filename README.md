# BondStats Central Bank Translator

**One monetary system. Different languages.**

A copyright-safe, original BondStats ontology for translating central-bank operational concepts across monetary systems without asserting false equivalence.

## Product rule

Every mapping must be classified as one of:
- exact / exact-concept / exact-example
- similar-function
- related
- no-direct-equivalent

This is intentionally stricter than a conventional glossary. The product should explain *function*, *market relevance* and *where comparisons break down*.

## Copyright / sourcing

The explanatory text and taxonomy in `data/translator.json` are original BondStats material. Institution and instrument names are factual identifiers. Do not paste third-party glossary prose, charts, logos, screenshots, or commercial database content into this repository.

Official primary sources should be used to verify mappings before expanding them. Current V1 research basis includes official Federal Reserve, ECB and Bank of Japan monetary-policy implementation documentation.

## Local preview

Serve the repository root with any static HTTP server. `index.html` fetches `data/translator.json`; opening it directly with `file://` may be blocked by browser fetch rules.

## Strong V2

Strong V2 expands the curated ontology while retaining the rule that no cross-central-bank mapping may be presented as equivalent merely because labels sound similar. The next production stage should add source URLs and verification metadata per mapping, then integrate the UI into BondStats.


Current ontology: **205 concepts**.
