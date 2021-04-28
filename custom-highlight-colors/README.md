# Custom Highlight Colors
Customize mentions, replying-to and Clyde highlight colors. 

## Customization
If you're just wanting to change the colors, all you really need to mess with is every variable that has `-color` in it. These values are done in an RGB (red, green, blue) format, so you can just use a simple [color picker](https://www.google.com/search?q=color+picker) off of Google itself.

## Importing
If instead you'd like to import this into your quick css, you can use
```css
@import url('https://discord-theme-addons.github.io/snippets/custom-highlight-colors/index.css');

:root {
    --mentioned-color: 250, 166, 26;
    --mentioned-pseudo: rgba(var(--mentioned-color));
    --background-mentioned: rgba(var(--mentioned-color), 0.05);
    --background-mentioned-hover: rgba(var(--mentioned-color), 0.08);

    --replying-color: 114, 137, 218;
    --replying-pseudo: rgba(var(--replying-color));
    --background-replying: rgba(var(--replying-color), 0.05);
    --background-replying-hover: rgba(var(--replying-color), 0.08);

    --clyde-color: 114, 137, 218;
    --clyde-pseudo: rgba(var(--clyde-color));
    --background-clyde: rgba(var(--clyde-color), 0.05);
    --background-clyde-hover: rgba(var(--clyde-color), 0.08);
}
```