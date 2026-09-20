<p align="center"><img src="assets/next-wordmark.png" alt="NeXT" width="720"></p>

<p align="center"><a href="https://github.com/NV-Davyd/NeXT/releases/download/v1.6.0/NeXT-1.6.0-Setup.exe"><strong>Download NeXT 1.6.0 Setup</strong></a> · <a href="https://next-mod.pages.dev">Account</a></p>

NeXT is a mod for **CarX Drift Racing Online 2**, focused on improving and expanding the game experience.

The project is just getting started, with new features and improvements on the way.

## Install

1. Update CarX 2 through Steam to **0.20.3 alpha**, build **25369856** on the **alpha-test** branch.
2. Close CarX and exit Steam completely using **Steam → Exit**.
3. Download and run **NeXT-1.6.0-Setup.exe**. Confirm the detected CarX 2 folder.
4. Launch from Steam's normal **Play** button. Press **F10** (the default menu key) to connect through Steam if this is a new installation.

The first launch can take longer while game bindings are prepared. Setup includes its runtime; no separate .NET or PowerShell installation is needed. Access requires approval.

**Updating from 1.4 or earlier?** Run Setup once using the steps above. The old updater cannot complete this game update's loader migration. Your saved account link, key bindings and existing launch arguments are kept. Setup also moves the plugin to `BepInEx/plugins/NeXT/NeXT.dll` and retires the old `CarXTyres.dll`.

**Already on 1.5.0 or newer?** Steam's Play button checks for NeXT updates before the game starts. **OK** installs the update and restarts through Steam; **No** keeps your installed version. Later updates can leave Steam open. Keep the NeXT launch option added by Setup to retain these checks.

If a future game update needs a new NeXT compatibility release, update discovery still runs. Until a compatible release is installed, you can choose to start without NeXT. Account approval and release restrictions still apply.

Use **Setup** for manual installation. The smaller release ZIP is for the fallback updater and does not include the required loader migration. Setup preserves unrelated mods and settings; it stops if it finds an unrecognized modified loader or another Steam launch wrapper.

## What's new in 1.6.0

- Hold the inspection key (**F12** by default) to expand another player's name tag with tyre sizes, rear setup pressure, horsepower and weight. The tag grows upward and collapses on release.
- Move and resize individual HUD widgets in NeXT Settings, with Save and Cancel. Includes a movable drift-angle readout.
- Three or more damaged components collapse into a warning icon and count, keeping the speed readable.
- The supplied NeXT watermark shows the mod and game versions at the top-right in rooms. It replaces the team logo.
- Change your multiplayer name for the next connection. **Change name** is a separate website permission, disabled by default for player accounts.
- Fresh tyres can be requested below **20 km/h**, including reverse.
- Open the NeXT menu manually at any speed. Room dynostand tyre settings remain locked.
- Improved player-car detection prevents HUD/features dropping out during visual loading when moving the camera around a damaged car.

Your available controls are on your [account page](https://next-mod.pages.dev).

Change your keyboard shortcuts in **NeXT → Settings**, including the menu key. Click a key, then press its replacement. Escape cancels; **Reset defaults** restores the original keys. Your choices are saved on this PC.

Windows x64 · CarX 2 **0.20.3 alpha** · Steam build **25369856**
