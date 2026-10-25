# Changelog

## 3.1.8

- Decode complete 128-byte AMG8833 frames, preserving signed-magnitude temperatures.
- Continue accepting the original unsigned 64-byte pixel format.
- Handle missing, unavailable and malformed pixel sensor states.
- Add standalone decoder tests and official HACS/Hassfest workflows.
- Link the matching ESPHome external-component firmware and document HACS custom-repository installation.
- Replace upstream-specific release automation that depends on the original maintainer token with explicit fork releases.

Hardware verification: Home Assistant 2026.10.2, ESPHome 2026.10.0, D1 Mini Pro and Grove AMG8833. Other upstream transports were not retested.
