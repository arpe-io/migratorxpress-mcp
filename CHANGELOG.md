# Changelog

All notable changes to the MigratorXpress MCP Server will be documented in this file.

## [0.1.1] - 2026-02-23

### Added

- `server.json` MCP Registry configuration file with package metadata, transport settings, and environment variable definitions

### Changed

- GitHub repository URL updated from `aetperf/migratorxpress-mcp` to `arpe-io/migratorxpress-mcp` in `pyproject.toml`

## [0.1.0] - 2025-02-20

### Added

- Initial release of MigratorXpress MCP Server
- 6 MCP tools: preview_command, execute_command, validate_auth_file, list_capabilities, suggest_workflow, get_version
- Support for MigratorXpress v0.6.24
- Source databases: Oracle, PostgreSQL, SQL Server, Netezza
- Target databases: PostgreSQL, SQL Server
- Migration tasks: translate, create, transfer, diff, copy_pk, copy_ak, copy_fk, all
- License key masking in command display
- Version detection and capabilities registry
- Comprehensive test suite
