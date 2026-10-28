<div align="center">

# Dracula · Prism

**Violet dusk gathers at the window; by morning, warm paper keeps the light. A place for thoughts to glow, and quietly become words.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-bd93f9?labelColor=282a36)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-bd93f9?labelColor=282a36)
[![License: MIT](https://img.shields.io/badge/license-MIT-bd93f9?labelColor=282a36)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-dracula-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-dracula-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-dracula-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

A complete light-and-dark pair in the Prism collection: the violet night of Dracula, and the warm paper of its official Alucard companion. Cyan-blue links and rose-pink tags give each thought its own place.

Explore the full [Prism theme gallery](https://github.com/martinkoutecky/tine/discussions/786) to compare all 29 themes in light and dark modes.

### Dark mode

![Dracula · Prism in Tine dark mode](docs/dracula-dark.png)

### Light mode

![Dracula · Prism in Tine light mode](docs/dracula-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-dracula-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#fffbeb` | `#282a36` |
| Sidebar | `#f5f0df` | `#22242e` |
| Body | `#1f1f1f` | `#f8f8f2` |
| Heading | `#1f1f1f` | `#f8f8f2` |
| Accent | `#644ac9` | `#bd93f9` |
| Links | `#035d84` | `#8be9fd` |
| Tags | `#a3144d` | `#ff79c6` |
| Mark background | `#f1e6ad` | `#48452d` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Dracula / Alucard](https://github.com/dracula/dracula-theme) at `e22ebcc048b8aff586f9bc94db30ff5347070b42`, under MIT; see [LICENSE](LICENSE). The dark palette follows the Dracula reference found in Codex, mapped independently from the open-source upstream palette. Light mode uses the upstream official Alucard palette, not a native Codex light preset. Some surface and text roles are adapted for Tine readability.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-dracula-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.
