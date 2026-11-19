# Windhawk — Digital Parasite (Rounded)

[Windhawk](https://windhawk.net/) mod configurations themed with the Digital Parasite palette —
**rounded variant** (window corners via Custom Window Corner Radius).

## Installation

1. Install [Windhawk](https://windhawk.net/).
2. Open Windhawk and go to the **Mods** tab.
3. For each mod listed below, import the corresponding `.yaml` file:
   - Click **Import** (or **Advanced** → **Import**).
   - Select the `.yaml` file from this folder.
4. Enable the mods and restart Windows if prompted.

> The agent prepares these files; import them yourself in the Windhawk app.

## Mods

| # | File | Mod | Description |
| --- | --- | --- | --- |
| 1 | `Alt-Tab-Flip-3D.yaml` | Alt+Tab Flip 3D (Vista Style) | Vista-style 3D Alt+Tab with blur background |
| 2 | `Alt-Tab-per-Monitor.yaml` | Alt+Tab Per Monitor | Alt+Tab switcher scoped per monitor |
| 3 | `Middle-Click-to-Close-on-the-Taskbar.yaml` | Middle-Click to Close on Taskbar | Middle-click a taskbar button to close the window |
| 4 | `Resource-Redirect.yaml` | Resource Redirect | Redirect system icons to Sweet Rainbow icon theme |
| 5 | `Taskbar-Auto-Hide-Keyboard-Only.yaml` | Taskbar Auto-Hide Fine Tuning | Keyboard-only auto-hide with hotkeys |
| 6 | `Taskbar-Auto-Hide-Speed.yaml` | Taskbar Auto-Hide Speed | Faster taskbar auto-hide animation |
| 7 | `Taskbar-On-Top.yaml` | Taskbar on Top for Windows 11 | Move taskbar to the top of the screen |
| 8 | `Taskbar-Tray-System-Icon-Tweaks.yaml` | Taskbar Tray System Icon Tweaks | Hide system tray icons, show desktop button |
| 9 | `Custom-Window-Corner-Radius.yaml` | Custom Window Corner Radius | Window corner radius 16px, small 6px |
| 10 | `Windows-11-Notification-Center-Styler.yaml` | Windows 11 Notification Center Styler | Dark panel with rose accents |
| 11 | `Windows-11-Start-Menu-Styler.yaml` | Windows 11 Start Menu Styler | Dark menu with rose hover highlight and cyan border |
| 12 | `Windows-11-Taskbar-Styler.yaml` | Windows 11 Taskbar Styler | Dark taskbar with rose bottom border (taskbar on top) |

### Disabled mods

| Mod | Description |
| --- | --- |
| Disable rounded corners in Windows 11 | Disabled in this variant — rounded corners come from Custom Window Corner Radius |

### Pending

| Mod | Description |
| --- | --- |
| Taskbar height and icon size | Config to be provided |

## Notes

- The Taskbar Styler mod expects the taskbar to be positioned at the **top** of the screen. The rose border is rendered at the bottom of the taskbar bar.
- The Resource Redirect mod uses the **Sweet Rainbow** icon theme by niivu.
- Mod configurations were adapted from the Catppuccin Macchiato palette with Digital Parasite colors applied.
- Custom Window Corner Radius: `radius: 16`, `smallRadius: 6`, `tooltipRadius: -1`, `roundMaximizedAndSnapped: none`.
