# Custom Highlight Colors
Customize mentions, replying-to and Clyde highlight colors.
- In order to change colors, all you have to mess with is `mentioned-color`, `replying-color`, and `clyde-color`. These values are done in RGB (red, green, blue), so you can just use a simple [color picker](https://www.google.com/search?q=color+picker) off of Google.

## Importing
If instead you'd like to import this into your quick css, you can use
```css
@import url('https://discord-theme-addons.github.io/snippets/custom-highlight-colors/index.css');

:root {
    /* mentions */
    --mentioned-color: 250, 166, 26;
    --mentioned-pseudo: rgba(var(--mentioned-color));
    --background-mentioned: rgba(var(--mentioned-color), 0.05);
    --background-mentioned-hover: rgba(var(--mentioned-color), 0.08);

    /* replying */
    --replying-color: 114, 137, 218;
    --replying-pseudo: rgba(var(--replying-color));
    --background-replying: rgba(var(--replying-color), 0.05);
    --background-replying-hover: rgba(var(--replying-color), 0.08);

    /* clyde */
    --clyde-color: 114, 137, 218;
    --clyde-pseudo: rgba(var(--clyde-color));
    --background-clyde: rgba(var(--clyde-color), 0.05);
    --background-clyde-hover: rgba(var(--clyde-color), 0.08);
}
```
