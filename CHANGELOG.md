# Release notes

## 1.7.1 — 14 September 2026

Maintenance release for Steam game build **25255628**, Windows x64, Unity **6000.3.19f1**.

- Shared runtime services now manage player context and tyre sampling independently of the HUD.
- Account-session handling is separate from its panel; access labels say “Granted” to distinguish approval from a feature toggle.
- Build compatibility checks, controls and feature identifiers are centralized.
- Builds and packages record source and binary hashes for verification.
- Existing controls, the `CarXTyres.dll` installation path, stored account links and access grants remain compatible.

Validation: local builds completed without warnings or errors; 22 managed access checks, reader simulations, six runtime/compatibility checks and 20 service tests passed. An independent source-package rebuild produced the identical plugin DLL. Game startup and the account panel were checked on the supported build. Approved driving actions were not exercised during this release check because the test account was not linked.

### Download

Install **CarX2-Mod-1.7.1-build25255628-install.zip** from this release's Assets. The package includes BepInEx and matching Unity base libraries for a fresh installation. Existing BepInEx users should replace only the mod DLL, following `INSTALL-CarXTyres.txt`.

Feature access requires Steam linking and owner approval. A download alone does not grant access.

Installer SHA-256: `887B450FCFE18AC20469E6A11320546248139AA1FD16ED82222B299E0CD805DF`.

Plugin SHA-256: `39EDFDCC624FD35044B10C86053B7185B3C841B948A9CF20606843D3C148F3AA`.
