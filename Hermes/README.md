# Hermes — Digital Parasite

Two skins based on the Digital Parasite palette (Capri / *Cyberpunk: Edgerunners 2*):

| Skin | Corners | File |
|---|---|---|
| `digital-parasite` | Square (`--radius-scalar: 0`) | `digital-parasite.yaml` |
| `digital-parasite-rounded` | Rounded, matching YASB Okinami | `digital-parasite-rounded.yaml` |

## Installation

1. Copy the YAML into your Hermes skins folder:
   - Default: `~/.hermes/skins/`
   - Custom `HERMES_HOME`: `$HERMES_HOME/skins/`
2. Activate the skin:
   - CLI: `/skin digital-parasite-rounded`
   - Or set `display.skin: digital-parasite-rounded` in `config.yaml`.

## Notes

- Both skins are single-mode (dark). Missing values inherit from the default Hermes skin.
- The `customCSS` block injects Digital Parasite colors into the Hermes Desktop GUI (chat background and sidebar) and controls corner rounding.
- The rounded skin uses the same radii as [YASB Okinami](https://github.com/MrDLingters/Okinami_YASB), softened for the Hermes UI: 10px main, 8px medium, 4px small.
- Includes a custom spinner with faces `(✨)`, `(🎀)`, `(⚡)` and thinking verbs (pulsing, infecting, glitching, parasiting, morphing, clinking).

Based on the Hermes skin system — see [CONTRIBUTING.md](https://github.com/NousResearch/hermes-agent/blob/main/CONTRIBUTING.md#adding-a-skin--theme).

---

Adapted and maintained by **Sakyuu**.
