# Windhawk — Digital Parasite (Rounded)

[Windhawk](https://windhawk.net/) mod configurations themed with the Digital Parasite palette —
**rounded variant** (window corners via Custom Window Corner Radius, taskbar at the bottom).

## Installation

1. Install [Windhawk](https://windhawk.net/).
2. Open Windhawk and go to the **Mods** tab.
3. For each mod listed below, import the corresponding `.yaml` file:
   - Click **Import** (or **Advanced** → **Import**).
   - Select the `.yaml` file from this folder.
4. Enable the mods and restart Windows if prompted.

> The agent prepares these files; import them yourself in the Windhawk app.

## Mods used

| # | File | Mod | Description |
| --- | --- | --- | --- |
| 1 | `Alt-Tab-Flip-3D.yaml` | Alt+Tab Flip 3D (Vista Style) | Vista-style 3D Alt+Tab with blur background |
| 2 | `Alt-Tab-per-Monitor.yaml` | Alt+Tab Per Monitor | Alt+Tab switcher scoped per monitor |
| 3 | `Middle-Click-to-Close-on-the-Taskbar.yaml` | Middle-Click to Close on Taskbar | Middle-click a taskbar button to close the window |
| 4 | `Resource-Redirect.yaml` | Resource Redirect | Redirect system icons to Sweet Rainbow icon theme |
| 5 | `Taskbar-Tray-System-Icon-Tweaks.yaml` | Taskbar Tray System Icon Tweaks | Hide system tray icons, show desktop button |
| 6 | `Custom-Window-Corner-Radius.yaml` | Custom Window Corner Radius | Window corner radius 16px, small 6px |
| 7 | `Taskbar-Height-and-Icon-Size.yaml` | Taskbar height and icon size | Height 36, icons 22, buttons 36 |
| 8 | `Windows-11-Notification-Center-Styler.yaml` | Windows 11 Notification Center Styler | Dark panel with rose accents |
| 9 | `Windows-11-Start-Menu-Styler.yaml` | Windows 11 Start Menu Styler | Dark menu with rose hover highlight and cyan border |
| 10 | `Windows-11-Taskbar-Styler.yaml` | Windows 11 Taskbar Styler | Dark taskbar, rounded buttons, rose top border |
| 11 | `Taskbar-Labels.yaml` | Taskbar Labels for Windows 11 | Labels on taskbar buttons, width 160 |

## Not used in this variant

| Mod | Description |
| --- | --- |
| Disable rounded corners in Windows 11 | Disabled — rounded corners come from Custom Window Corner Radius |
| Taskbar auto-hide fine tuning | Not used |
| Taskbar on top for Windows 11 | Not used — the taskbar is at the **bottom** |
| Taskbar auto-hide speed | Not used |

## Notes

- The taskbar is at the **bottom**; the Taskbar Styler renders the rose border at the **top** of the bar.
- Taskbar buttons use `CornerRadius=10` to match the rounded theme.
- The Resource Redirect mod uses the **Sweet Rainbow** icon theme by niivu.
- Mod configurations were adapted from the Catppuccin Macchiato palette with Digital Parasite colors applied.
- Custom Window Corner Radius: `radius: 16`, `smallRadius: 6`, `tooltipRadius: -1`, `roundMaximizedAndSnapped: none`.
