# IDDA Public Report Demo

Public-safe HTML artifact demonstrating the shape of an IDDA-style offline PoC report.

This repository contains only a client-facing report demo. It is intended to show how an offline PoC result can be presented as a readable HTML artifact with metrics, visual summaries, event classes, and public-safe examples.

## What this demo shows

- Offline sample reporting
- Event class distribution
- Visual summary cards
- Donut charts and ratio breakdowns
- Public-safe abstracted examples
- Clear PoC scope boundaries
- Human-readable HTML report format

## What this repository does not include

This repository does **not** include:

- raw logs
- customer data
- protected IDDA decision logic
- production thresholds
- tuning rules
- live ingestion code
- deployment details
- production runtime policies
- IDDA core implementation

## Scope boundary

This is not an intrusion detection claim, not a live ingestion benchmark, and not a production deployment.

The purpose of this artifact is to demonstrate the format of a possible IDDA-style offline PoC deliverable.

## Public-safe boundary

The report does not expose raw hostnames, usernames, IP addresses, local paths, TTY values, commands, raw log lines, or customer data.

Examples shown in the HTML are abstracted before rendering, using placeholders such as:

```text
host=[redacted]
user=[redacted]
path=[redacted]
command=[redacted]
