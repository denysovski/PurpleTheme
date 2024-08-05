# BetterDiscord Purple Theme 🌸
Welcome to the BetterDiscord Purple Theme repository! This theme brings a modern purple colorway to your BetterDiscord.

## Features
- Elegant purple Colorway: A refreshing purple palette for all your Discord needs.
- Clean and Minimal Design: A simple and unobtrusive design that enhances your Discord interface.
- Customizable Options: Tailor the theme to your preferences with easy-to-edit CSS settings.

## Installation
To install the BetterDiscord purple theme, follow these steps:<br>

    Download the theme file: testMine.css
    Place the file in your BetterDiscord themes folder:
        Windows: %appdata%/BetterDiscord/themes
        Mac: ~/Library/Application Support/BetterDiscord/themes
        Linux: ~/.config/BetterDiscord/themes
    Enable the theme in BetterDiscord:
        Go to User Settings > Themes
        Find the Purple Theme and toggle it on

## Background-image property

```
--background-image: url('https://raw.githubusercontent.com/denysovski/PurpleTheme/main/purple.jpg');
```

## How to change background image with local source?
> „This is not possible. The application front end does not have filesystem access due to security problems that may arise from it. Theoretically this can be re-enabled with a plugin. But the use-case is very niche, and you are likely better off just using an online host.“ - RDG-01, Theme developer
</br>
Main source https://www.reddit.com/r/BetterDiscord/comments/1aib1vo/how_to_use_local_url_pulls_for_themes/

## How to change background image via online link?
The easiest solution to change the background image by changing url('') with the source URL of your image</br>
Be aware that when the image from online source gets deleted, you won't get to see the theme in Discord anymore.

- Find an image online and get it's source URL (For verification, make sure the ending of URL is .jpg, which leads to an image, not a website)
- Replace the background-image property url('') to your image URL

```
--background-image: url('https://wallpapers.com/images/hd/purple-cool-sqcgvfwstpv5gv4j.jpg');
```

- Save the code and upload it back to the folder - repeat steps in **Installation** part

## How to change background image via GitHub repository?
Harder and much longer way to change background image, but more efficient, because the online source can be deleted at any time, while your repository is here forever

- Upload your image to own GitHub repository of your choice (e.g. your account name "Jason", repository "JasonBack", image "PurpBack.jpg")
- Replace the link property to your own values

```
--background-image: url('https://raw.githubusercontent.com/Jason/JasonBack/main/PurpBack.jpg');
```

- Save the code and upload it back to the folder - repeat steps in **Installation** part

## Final message
Feel free to download and enjoy the BetterDiscord purple theme. If you like it, consider giving this repository a star 🌸!
</br>
All credits to original author - https://github.com/ClearVision/ClearVision-v6
</br>
</br>
This page provides a quick tutorial on how to set up my modified purple theme and change the background, thanks for reading until the end.


