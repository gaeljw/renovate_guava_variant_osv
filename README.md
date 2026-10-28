# renovate_guava_variant_osv

Minimal reproduction: with `osvVulnerabilityAlerts` enabled, Renovate proposes
`com.google.guava:guava` `33.7.1-jre` -> `33.7.2-android` (variant switch) instead of `33.7.2-jre`.

See `pom.xml` and `renovate.json`.
