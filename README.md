# Jellyfin Themes

Custom CSS themes for Jellyfin.

## Themes

- `Aurora Stream`: static cinematic theme with no CSS animations.
- `Aurora Stream - Animated`: animated variant with ambience, card effects, and navigation highlights.

## Install In Jellyfin

1. Open Jellyfin as an administrator.
2. Go to `Dashboard` > `General` > `Custom CSS`.
3. Paste one of the import lines below.
4. Save, then refresh Jellyfin in your browser.

### Aurora Stream

```css
@import url("https://cdn.jsdelivr.net/gh/cloudd901/Jellyfin_Themes@main/Jellyfin_Themes/%5BCD9%5D%20Theme_Aurora%20Stream.css");
```

### Aurora Stream - Animated

```css
@import url("https://cdn.jsdelivr.net/gh/cloudd901/Jellyfin_Themes@main/Jellyfin_Themes/%5BCD9%5D%20Theme_Aurora%20Stream%20-%20Animated.css");
```

## Manual Install

Download one of the CSS files from `Jellyfin_Themes/`, open it in a text editor, and paste the full contents into Jellyfin's `Custom CSS` box.

## Files

- `Jellyfin_Themes/[CD9] Theme_Aurora Stream.css`: static theme.
- `Jellyfin_Themes/[CD9] Theme_Aurora Stream - Animated.css`: animated theme.

## Notes

- These themes are designed for Jellyfin Web and clients that load Jellyfin Web from your server.
- Some mouseover glass animations may not work in the Windows app.
- If you already have custom CSS, paste the import line above your local overrides.
- GitHub-backed jsDelivr URLs are used for imports so the CSS is served with browser-friendly stylesheet headers.
