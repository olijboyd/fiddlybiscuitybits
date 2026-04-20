# Gemini CLI Instructions — Fiddly Biscuity Bits

This is a test Gemini instruction file for validating the TomeVault Relay end-to-end pipeline.

## Context

This repo is a sandbox used to exercise the GitHub App webhook path:
commit lands on main → webhook fires → relay drainer picks up the change →
SQLite row refreshed → convert/sync/distribute re-runs → format-mirror repos
under tomevault-io/ reflect the update.

## Style

- Prefer short, direct answers
- Ask before making destructive changes
- Keep explanations terse

(Dummy file — safe to delete after the relay round-trip is verified.)
