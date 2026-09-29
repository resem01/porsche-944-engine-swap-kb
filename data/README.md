# Structured Data

Machine-readable project data used by the documentation and future analysis.

## Current files

- `source-index.csv` — source/provenance registry keyed by source ID
- `engine-specs.csv` — representative engine-family specifications
- `measurements.csv` — configuration-defined physical measurements and weights
- `parts.csv` — parts, kits, prices/check dates, and source references

Structured data should reference source IDs rather than embedding unsupported values. A value in these CSV files is not
automatically "verified"; its evidence class and status still control how it should be interpreted.

The human-readable source index is [`docs/SOURCE_INDEX.md`](../docs/SOURCE_INDEX.md).
