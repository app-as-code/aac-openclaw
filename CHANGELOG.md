# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Upstream image tracks OpenClaw 2026.6.1 as defined in `service.yml`.

## [0.0.1]

### Added

- Initial App-as-Code service definition for OpenClaw (gateway on port 18789, bridge on port 18790).
- Persistent volumes for configuration and workspace.
- Traefik routing and automatic DNS integration for the gateway.
- README with configuration reference and project icon.
