# Log4Shell Propagation Analysis

This repository contains the scripts, queries, SBOM commands, and report files used for a staged Log4Shell propagation analysis across three Java-based projects:

- Apache Solr 8.11.0
- Spring Boot / VMware 2.5.0
- Ghidra 10.0.4

The analysis follows a four-stage model:

1. Structural Exposure
2. Vulnerable Class Presence
3. Code Reachability
4. Taint Path Confirmation

The goal of the repository is to show how far different tools can support each stage of the analysis, and where additional program-analysis techniques are required beyond SBOM generation.
