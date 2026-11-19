# Steam Digital Parasite Theme (Rounded)

A **Millennium** theme for the Steam client, inspired by **Capri** from *Cyberpunk: Edgerunners 2*. Neon rose & green on a deep dark background — a cyberpunk aesthetic for your Steam library. **Rounded variant.**

![Digital Parasite Theme](screenshot.png)

## Based on

This theme is built on top of **[Simple Dark.](https://github.com/shdwmtr/simply-dark)** by ShadowMonster, reworked with the Digital Parasite color palette. Simple Dark provides a solid, well-tested CSS structure for the Steam client; Digital Parasite swaps in the Capri-inspired neon colors.

## Rounded variant

The corner radii are driven by CSS variables in `webkit/webkit.css`:

```css
--border0: 4px;
--border1: 10px;
--border2: 20px;
--border25: 25px;
--border35: 35px;
--border4: 40px;
--border5: 50px;
--border8: 80px;
--border50: 50%;
```

The square variant sets `--border35/4/5/8/50` to `0px`; this rounded variant restores them.

## Installation

1. Install **[Millennium](https://steambrew.app/)** (the Steam modding framework).
2. Close Steam completely.
3. Copy the contents of the `Steam` folder into a new folder named `DigitalParasite-Rounded` in your Steam installation:
   ```
   Steam/millennium/themes/DigitalParasite-Rounded/
   ```
4. Restart Steam.
5. Go to **Steam → Millennium → Themes** and select **Digital Parasite Rounded**.
6. Reload Steam when prompted.

### Alternative (via Theme ID)

Once the theme is published on [steambrew.app](https://steambrew.app/themes), you can install it directly from Millennium:
- **Steam → Millennium → Themes → Install a theme** → paste the Theme ID.

## Features

- Dark cyberpunk background
- Rose and green neon accents
- Cyan links
- Custom scrollbars, buttons, inputs, tooltips, progress bars
- Styled Steam store (WebKit) with matching colors
- Fully functional library, friends, chat, settings, downloads, overlay

## Customization

The theme inherits Simple Dark's customization options (compacted header, wallet visibility, URL bar, etc.). Access them via **Steam → Millennium → Themes → Digital Parasite → Settings**.

## Credits

- **[Simple Dark.](https://github.com/shdwmtr/simply-dark)** by ShadowMonster — base CSS structure
- **Digital Parasite** concept by Sakyuu — color palette inspired by Capri (Cyberpunk: Edgerunners 2)
- **[Millennium](https://github.com/SteamClientHomebrew/Millennium)** — the modding framework

## License

MIT
