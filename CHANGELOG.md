# Changelog

All notable changes to this project are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Added
- Privacy-first telemetry server for QubHub Agent (FastAPI + SQLite): anonymous event
  ingestion (`/v1/events`, `/v1/events/bulk`), aggregate / daily / feature / model
  statistics, per-user event listing, and a `/health` probe.
- `telemetry_server/requirements.txt` so the service is reproducibly installable.
- CI workflow (byte-compile + FastAPI smoke test) and Dependabot weekly updates.
