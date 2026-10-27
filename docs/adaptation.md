# Adaptation notes

The dark palette follows the Dracula reference found in Codex, mapped independently from the open-source upstream palette. Light mode uses the upstream official Alucard palette, not a native Codex light preset. Some surface and text roles are adapted for Tine readability.

## Sources

- readme: https://github.com/dracula/dracula-theme/blob/e22ebcc048b8aff586f9bc94db30ff5347070b42/README.md
- license: https://github.com/dracula/dracula-theme/blob/e22ebcc048b8aff586f9bc94db30ff5347070b42/LICENSE

## Mapping decisions

- Dark main background, foreground, cyan links, pink tags, purple accent and yellow mark foreground follow the official OSS Dracula palette.
- Light palette uses the official OSS Alucard background/foreground/purple accent/pink tags/selection. This is not claimed to be a native Codex light preset.
- Light cyan link is deepened from #036a96 to #035d84 and secondary text from #6c664b to #5c573f so these explicit roles retain at least 4.5:1 even on the text-selection surface.
- Surfaces beyond the source canvas are Tine/Prism adaptations. Dark selected/highlight/inline-code/control surfaces use #343746 rather than official #44475a, preserving the original pink and purple text readability.
- Contrast calculations cover explicit text roles across four surfaces, chosen and text-selection backgrounds, plus code and mark pairs; no claim about all host-derived or opacity-dimmed content.

## Validation

Local 0.1.0 preview passed Tine's official manifest checker with no errors or warnings. A synthetic Chromium fixture checked all 21 tokens per mode, light → dark → light switching, and specified body/title/link/tag/code/mark/selected combinations. Main-canvas light/dark body contrast is 15.89/13.36:1, links 6.98/10.29:1 and tags 7.33/5.97:1. The user supplied real Windows screenshots of the complete light and dark palettes after testing; these are included in both READMEs. The captures show the public welcome page, not every interaction or platform. Do not treat these calculations and fixture results as proof of all host-derived states, opacity-dimmed text or platforms.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.
