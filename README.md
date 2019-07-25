# Dracula for [GameMaker Studio 2](https://www.yoyogames.com/gamemaker)

> A dark theme for [GameMaker Studio 2](https://www.yoyogames.com/gamemaker).

![Screenshot](https://media.discordapp.net/attachments/392980753228496896/589562899261947925/unknown.png)

## Install

[Video Tutorial](https://www.youtube.com/watch?v=DV_JkP_VXdQ)

### Written Install Instructions

* Download this https://github.com/tonystr/Dracula/archive/master.zip

* Unzip it, rename the folder "Dracula"

* Move it to:

        - Windows: C:\ProgramData\GameMakerStudio2\Skins
        - macOS: /⁨Users⁩/⁨Shared⁩/⁨GameMakerStudio2⁩/⁨Skins⁩

* File -> Preferences -> General Settings -> IDE skin -> Dracula -> Apply. If the skin does not show up in this list, try restarting gms2, and make sure the theme is installed at the correct location (it needs to be `..\Skins\Dracula`, not `..\Skins\master\Dracula`, for example)

* Restart GMS2

* If the text doesn't look right (letters have different widths), see troubleshooting below

## Troubleshooting

### Non-monospaced font

if you don't have the font, "Inconsolata" installed on your machine, gamemaker will default to some font that is not monospaced (characters have different widths, resulting in lines not aligning with eachother properly). This can be solved by going to "File > Preferences > Text Editors > Code Editor > Colours > Default", and selecting a monospaced font from the dropdown menu next to "Font Name". If you're feeling adventurous, install some other monospaced fonts from the internet, and try them out! I recommend trying "Roboto Mono", "Fira Mono", "PT Mono" and "Droid Sans Mono".

### Installed the theme, but still doesn't show up in settings

If the above install locations do not work, you can try alternative paths: 

        - Windows: \GameMaker Studio 2 Desktop\GUI\Skins\Dracula
        - macOS: /Applications/GameMaker Studio 2.app/Contents/MonoBundle/GUI/Skins

The reason this is not listed as the main theme path is that it depends on where your gamemaker installation lies (steam? program files? desktop?), and because it will be cleared with each GMS2 update, meaning you have to manually re-install it every time you update. If this still doesn't work, shoot me (TonyStr) a DM over email, twitter or anywhere else.

### Broken GUI elements, or inaccessible GUI

There may be parts of gamemaker that are not covered by this theme. The DnD editor, for instance, is not supported, and may be completely broken with the theme. If you spot some issues anywhere else than with the DnD editor, please open an issue on this github page, or attempt to fix it yourself (then open a Pull Request to this repository).

## Team

This theme is maintained by the following person(s) and a bunch of [awesome contributors](https://github.com/tonystr/Dracula/graphs/contributors). The color palette included in the image editor is EDG36 by [Endesga](https://twitter.com/ENDESGA)

[![Tony Strømsnæs](https://avatars3.githubusercontent.com/u/30723101?v=3&s=70)](https://github.com/tonystr) |
--- |
[Tony Strømsnæs](https://github.com/tonystr) |

## License

[MIT License](./LICENSE)
