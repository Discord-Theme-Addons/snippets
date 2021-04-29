# Old Mentions
Bring back Discord's old mentions.

![preview](https://discord-theme-addons.github.io/snippets/assets/screenshots/old-mentions.png)

## Importing
If instead you'd like to import this into your quick css, you can use
```css
@import url('https://discord-theme-addons.github.io/snippets/old-mentions/index.css');

:root {
    /* Mentioned */
    --mentioned-color: 250, 166, 26;
    --mentioned-pseudo: rgba(var(--mentioned-color));
    --background-mentioned: rgba(var(--mentioned-color), 0.05);
    --background-mentioned-hover: rgba(var(--mentioned-color), 0.08);

    /* Replying */
    --replying-color: 114, 137, 218;
    --replying-pseudo: rgba(var(--replying-color));
    --background-replying: rgba(var(--replying-color), 0.05);
    --background-replying-hover: rgba(var(--replying-color), 0.08);
}
```