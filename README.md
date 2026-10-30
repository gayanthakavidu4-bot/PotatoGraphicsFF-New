# POTATO GRAPHICS v2.2 — All Games Optimizer

A rootless Android companion app with game launch shortcuts, general in-game graphics guidance, and basic device information.

## Included
- Game selector: Free Fire, PUBG Mobile, Call of Duty Mobile, Mobile Legends
- Launch installed games when Android exposes a matching launch package
- English / Sinhala interface
- RAM, this app's memory use, battery level and battery temperature
- App-visible storage volume, network connection type, Android thermal status (where supported)
- Simple tap counter test
- Safe gaming preparation tips
- GitHub Actions workflow to build a debug APK

## Build on GitHub
1. Extract this ZIP on your phone or computer.
2. Upload the **contents inside** the extracted `POTATO_GRAPHICS_v2.2` folder to the **root** of your GitHub repository. Keep the `.github` folder (including `.github/workflows/build.yml`).
3. Open the repository's **Actions** tab.
4. Select **Build POTATO GRAPHICS v2.2 APK** and choose **Run workflow**.
5. When it succeeds, open the run and download `POTATO-GRAPHICS-v2.2-APK` under Artifacts.

## Important limitations
- This is a guide and monitoring companion, not a game booster.
- It does not edit game files, inject code, unlock FPS, change CPU frequency, or control another app's memory.
- RAM is system-wide available RAM; app memory is for this app only.
- Storage is the app-visible storage volume, not a complete storage analyzer.
- The touch test counts taps; it does not measure hardware touch latency.
- Game package names may vary by region or edition. A game may be installed but not detected by the included launch shortcut.
- Performance depends on the phone and the game's own supported settings. No FPS or performance gain is guaranteed.

## App details
- Application ID: `com.potatographicsff.app`
- Version: `2.2` (versionCode 3)
- Minimum Android: 6.0 (API 23)
- Compile / target SDK: 35
