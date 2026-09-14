# CarX 2 Mod

Downloads for the CarX Drift Racing Online 2 mod. **CarX 2 Mod is a working name.**

**[Download version 1.7.1](https://github.com/NV-Davyd/CarX2-Mod/releases/tag/v1.7.1)** · Windows x64 · Steam game build **25255628**

Choose **CarX2-Mod-1.7.1-build25255628-install.zip** under the release's Assets. The automatically generated “Source code” archives contain this downloads repository's documentation and do not install the mod. Development source is maintained privately.

## Features and controls

| Feature | Control |
| --- | --- |
| Tyre-life HUD | Follows the game's native tyre-temperature widget |
| Refresh mounted tyres | Apostrophe (`'`) |
| Save / return to a waypoint | F6 / F7 |
| Native room dynostand | F8 while parked in a multiplayer room |
| Faster spectating | Existing Spectate / next / previous controls |
| Account linking and access | F10 |

The mod also includes a team watermark. Features require linking the playing Steam account and owner approval through the [access website](https://carx-mod-access.carx-mod-access.workers.dev). Downloading the mod does not grant feature access.

## Install or update

1. Close the game and open its installation folder through Steam: **Properties → Installed Files → Browse**.
2. If BepInEx is already installed, copy only `BepInEx/plugins/CarXTyres/CarXTyres.dll` from the ZIP to the same location in the game folder. Keep your existing loader, settings and other mods.
3. For a fresh installation, extract the full ZIP beside the game executable. Leave `BepInEx/unity-libs/6000.3.19.zip` zipped.
4. Launch through Steam, then press **F10** to link the account and check access. The first launch can take longer while BepInEx generates bindings.

See the [complete installation and rollback instructions](INSTALL-CarXTyres.txt) and [release notes](CHANGELOG.md). The package is pinned to build **25255628** and its exact game-file hashes; a different build needs a compatible mod release.

Keep `BepInEx/config/CarXModAccess` when updating or rolling back: it stores the local account link. To disable the mod, close the game and move `CarXTyres.dll` out of `BepInEx/plugins`.

## Verify the download

The release includes `SHA256SUMS.txt` and a release manifest. In PowerShell:

```powershell
Get-FileHash './CarX2-Mod-1.7.1-build25255628-install.zip' -Algorithm SHA256
```

Expected SHA-256:

```text
887B450FCFE18AC20469E6A11320546248139AA1FD16ED82222B299E0CD805DF
```

The ZIP also contains a separate `SHA256SUMS.txt` for its contents. BepInEx and bundled dependencies retain their upstream licenses; the package includes BepInEx's license and upstream source link.
