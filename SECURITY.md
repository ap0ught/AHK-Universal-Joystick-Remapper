# Security Policy

## Supported versions

UJR is a legacy project and is no longer actively maintained.

| Version | Supported |
| --- | --- |
| 6.x and earlier | :x: |

For a maintained alternative, use [UCR](https://github.com/evilC/UCR).

## Reporting a vulnerability

If you discover a security issue in this repository:

1. Do not include secrets, exploit code, or other sensitive details in a public report.
2. Open a GitHub issue with a minimal description of the affected area and the impact.
3. Wait for a maintainer to confirm how follow-up details should be shared.

Because this project is unmaintained, fixes may be delayed or may not be released. If you depend on this tooling, review the source before use and plan to migrate to a maintained alternative.

## Expected network behavior

The legacy application checks for updates by reading a version file from `evilc.com`. Unexpected outbound network traffic should be treated as a sign that the binary or environment may have been modified.
