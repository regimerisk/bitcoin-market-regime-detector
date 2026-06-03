# Changelog

All notable changes to this indicator are documented here.
Format based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/);
this project uses [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [1.0.0] — YYYY-MM-DD
### Added
- Initial public release of the simplified reference indicator.
- Five-regime classification: Bull, Bear, Range, Volatility, Transition.
- Rule-based engine: long-EMA trend + slope, ATR-percentile volatility, ADX directional strength.
- Chart background colouring by regime and an on-chart regime panel.
- Regime-change alerts (`alertcondition` plus a dynamic `alert()` on bar close).
- Tunable inputs for all trend, volatility, and range thresholds.

[Unreleased]: https://github.com/YOUR-ORG/bitcoin-market-regime-detector/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/YOUR-ORG/bitcoin-market-regime-detector/releases/tag/v1.0.0
