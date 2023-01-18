# Welcome to OpenVEX!

OpenVEX is an implementation of the
[Vulnerability Exploitability Exchange](https://www.ntia.gov/files/ntia/publications/vex_one-page_summary.pdf)
(VEX for short) that is designed to be minimal, compliant, interoperable, and
embeddable.

## OpenVEX is...

### A Specification

OpenVEX documents are minimal JSON-LD files that capture the minimal requirements
for VEX as defined by the VEX working group organized by CISA. The
[OpenVEX Specification](https://github.com/openvex/spec/blob/main/OPENVEX-SPEC.md)
is owned and steered by the community.

### A Go Library

The project has a go library
([openvex/go-vex](https://github.com/openvex/go-vex)) that lets projects generate,
transform and consume OpenVEX files. It enables the ingestion of VEX metadata
expressed in other VEX implementations.

### A Set of Tools

Work is underway to create the tools software authors and consumers need to
handle VEX metadata. The current flagship project is
[`vexctl`](https://github.com/openvex/vexctl), a CLI to create, merge and
attest VEX documents.
