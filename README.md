# Chronicle Detection Rules

This is a collection of beginner-to-intermediate detection rules written for Google Chronicle using YARA-L. All rules are written using the `filter()` pattern for telemetry filtering and are designed for clarity, precision, and enrichment.

## Learning Journey

I started with no knowledge of YARA-L or Chronicle’s detection engine. Through deliberate practice and repeated questioning, I slowly understood:

1. The difference between classic YARA and Chronicle YARA-L
2. Why `filter()` is the preferred way to scope telemetry data
3. How to structure `outcome` blocks for SOC-friendly enrichment
4. How to turn real-world TTPs (tactics, techniques, procedures) into rules (this is a slow process)

## Rules Overview

All rules are:
- Written using the `filter()` method
- Include structured `outcome` blocks
- Cover both process and network-based detections
- Aligned where possible with MITRE ATT&CK techniques
