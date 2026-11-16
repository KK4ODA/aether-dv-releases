# Aether DV: downloads

Installers and the update feed for **[Aether DV](https://github.com/KK4ODA/aether-dv)**, an open-source D-STAR data app for amateur radio in the tradition of D-RATS. It speaks the D-RATS protocol, so it can exchange chat, files and forms with D-RATS stations and use the same ratflectors.

**Features, screenshots, setup and source code are in the [main repository](https://github.com/KK4ODA/aether-dv#readme).** This repository only holds the releases.

![Aether DV chat on an IC-9700](https://raw.githubusercontent.com/KK4ODA/aether-dv/main/docs/screens/chat.png)

## Download

Get the newest release from the **[releases page](https://github.com/KK4ODA/aether-dv-releases/releases)**. Under *Assets*, pick the file for your system:

| System | File |
|---|---|
| Windows 10 or 11 (64-bit) | `Aether-DV_…_x64-setup.exe` (or the `.msi`) |
| macOS on Apple silicon (M1 or later) | `Aether-DV_…_aarch64.dmg` |
| Debian, Ubuntu and similar | `Aether-DV_…_amd64.deb` |
| Fedora, openSUSE and similar | `Aether-DV-…x86_64.rpm` |
| Other Linux | `Aether-DV_…_amd64.AppImage` |

You don't need the `.sig` files, `Aether-DV.app.tar.gz` or `latest.json`: the app's updater uses those.

Releases are marked *pre-release* while the version is 0.x. Aether DV has been bench-tested on an IC-9700 and an ID-52 PLUS on simplex, but not yet through repeaters or with D-RATS stations.

### First launch

The installers aren't code-signed yet, so your system will warn the first time:
- **Windows:** if SmartScreen says "Windows protected your PC", click **More info**, then **Run anyway**.
- **macOS:** if it says the app can't be opened, go to **System Settings > Privacy & Security**, scroll down and click **Open Anyway** next to Aether DV.

Updates are different: each one is signed with Aether DV's own key, and the app checks that signature before installing.

## Updates

The app checks this repository for a new version when it starts. When there is one, an update card appears: click it to download and install. The release notes for each version are on the [releases page](https://github.com/KK4ODA/aether-dv-releases/releases).

## Getting started

- **[Main README](https://github.com/KK4ODA/aether-dv#readme):** what Aether DV does, with screenshots.
- **[Setting up radios](https://github.com/KK4ODA/aether-dv/blob/main/docs/bench-tests.md#part-a--preparation-once):** COM ports, radio settings and the configuration file. The app's **Radio Setup** view has settings for each supported radio.
- **Problems or questions:** open an [issue in the main repository](https://github.com/KK4ODA/aether-dv/issues). A support bundle (in the app: **Diagnostics > Write support bundle**) helps a lot.

<!-- tota-support:start -->
## Support

aether-dv-releases is free and stays free. It is written by KK4ODA, who also runs
[Tiles on the Air](https://tilesontheair.com), a free program for portable
operators, and both are kept going by the people who use them. If aether-dv-releases is
useful to you, a contribution through the
[Tiles on the Air giving page](https://tilesontheair.com/Giving) helps keep this tool and Tiles
running. Nothing is ever locked behind it, and a bug report or an on-air
report helps just as much.
<!-- tota-support:end -->
