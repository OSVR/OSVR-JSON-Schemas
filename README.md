# OSVR JSON Schemas

> Maintained at <https://github.com/OSVR/OSVR-JSON-Schemas>

Shared JSON schemas for the OSVR ecosystem - used across multiple projects, so placed in a separate repository to have a single point of truth.

See the [project wiki][] for some useful JSON and JSON-Schema links/tools.

[project wiki]: https://github.com/OSVR/OSVR-JSON-Schemas/wiki

If you're seeing this as a subdirectory somewhere, that's probably because the schemas were included as a Git submodule or other similar mechanism. See the link above for the latest versions.

## Contents

### Schemas
- `device_descriptor_schema.json` - Schema for device descriptors (typically get compiled into plugins, though they may be parsed from source trees to generate compatibility lists).

- Display-related schemas

	- `display_descriptor_schema_v0.json` - Not present because it was never formalized, but noted here to record that there was an early, basically totally different display description format used around CES 2015, in case you encounter a totally-different looking descriptor or parser in the wild.

	- `display_descriptor_schema_v1.json` - A newer, somewhat incomplete and inconsistent, but importantly, widely established (used by the Unity plugin around the core v0.2 release) description

### Documentation
While we try to make the schemas sufficient documentation for the files they describe, sometimes additional prose documentation is helpful.

Documentation regarding `display_descriptor_schema_v1.json` is included in this repo, in Markdown format with illustrations (including illustration sources in SVG where applicable).


## License

This project: Licensed under the Apache License, Version 2.0.
