# Glass
For when you want Discord *entirely* transparent.
## How it looks on top of applications;
![Glass](https://raw.githubusercontent.com/Lylythii/BetterDiscordAddons/main/Themes/Glass/glass.png)
## Video demonstration;
https://youtu.be/qx7v6kd8ihI
![Glass Video Demonstration](https://raw.githubusercontent.com/Lylythii/BetterDiscordAddons/main/Themes/Glass/preview.webp)

### Notes;
- Transparency needs to be enabled in settings for this to work properly, or usage of a custom background or compatible client will suffice. In the case of BetterDiscord or Vencord, refer to below to see how to enable transparency. This requires a full client restart.
- You can set a custom background manually by editing the CSS & providing a valid url. Or placing one of the below examples in the Custom CSS window. Alternatively, in the case of Vencord, paste the RAW url in the theme validator **AFTER** the url for the Glass theme.
- Theme has minor visual issues in Light mode, I suggest switching to Dark mode.

### Enable Transparency on Vencord
![Glass Video Demonstration](https://raw.githubusercontent.com/Lylythii/BetterDiscordAddons/main/Themes/Glass/vencord-transparency.webp)

### Enable Transparency on BetterDiscord
![Glass Video Demonstration](https://raw.githubusercontent.com/Lylythii/BetterDiscordAddons/main/Themes/Glass/betterdiscord-transparency.webp)

### Something not transparent?
[Open an issue please](https://github.com/Lylythii/BetterDiscordAddons/issues/new).

## Don't want to modify the theme directly to add a custom background?
## Place this (& your chosen background url) into "Custom CSS". (or some other method of applying CSS);
```
/* Set the background for the Glass theme */
:root,
.theme-dark,
.theme-light {
	--background-image: url('HTTPS_LINK_PNG_WEBP_ETC');
}
```

## Here's a good example;
```
/* Set the background for the Glass theme */
:root,
.theme-dark,
.theme-light {
	--background-image: url('https://raw.githubusercontent.com/Lylythii/BetterDiscordAddons/tree/main/Themes/Glass/background.png');
}
```
Raw url to preset theme background snippet for Vencord
```
https://raw.githubusercontent.com/Lylythii/BetterDiscordAddons/main/Themes/Glass/css_snippets/misc_example.css
```

## Here's another, using the same background as [Priscord](https://github.com/Lylythii/BetterDiscordAddons/tree/main/Priscord);
```
/* Set the background for the Glass theme */
:root,
.theme-dark,
.theme-light {
	--background-image: url('https://raw.githubusercontent.com/PrismLauncher/prismlauncher.org/40d89d06ae90c7cbef18b06f52fd9a4c30c61db8/src/img/background/prism-background.svg');
}
```
Raw url to preset theme background snippet for Vencord
```
https://raw.githubusercontent.com/Lylythii/BetterDiscordAddons/main/Themes/Glass/css_snippets/priscord_background.css
```
