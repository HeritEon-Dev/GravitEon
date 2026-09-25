# GravitEon

### All-in-one sorting, lookup and grouped data.

GravitEon is proprietary software being developed independently under HeritEon.

This repository presents a development preview: measured performance,
comparisons with established C++ libraries, and the next validation steps.

**Presentation and benchmarks only. No engine source code, binaries
or implementation details are distributed here.**

## Presentation

[Read the development preview (PDF)](docs/GravitEon_Development_Preview.pdf)

[HTML version](docs/GravitEon_Development_Preview.html)
— download and open locally in a browser.

## Benchmark results

The current run includes 97 completed test cases, with inputs reaching
10 million records.

- Lookup queries lead in 548 of 574 comparisons (95.5%).
- Selected lookup queries show time ratios above 10× against the fastest
  measured rival, reaching 15.11×.
- Sorting, index construction and grouped financial data are also covered.
- Cases where GravitEon trails are included in the presentation.

These are developer measurements on one disclosed platform.
The percentages count comparisons, not overall application speed gains.
The presentation documents the workloads, comparison rules and limitations.

[Download all 850 operation-level comparisons (CSV)](benchmarks/GravitEon_Benchmark_Comparisons.csv)

## Development status

GravitEon remains in development. Validation on public datasets,
starting with PaySim, is planned. Those results are not part of this preview.

## Access

This repository is for presenting and discussing the work.
It does not provide a software download or an open-source release.

For technical questions or evaluation enquiries:
[office@heriteon.com](mailto:office@heriteon.com)

[HeritEon](https://heriteon.com) ·
[LinkedIn](https://www.linkedin.com/company/heriteon/)
