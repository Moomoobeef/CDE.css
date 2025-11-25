## default
*from Solaris 8 (Intel Edition) "Default" theme (go figure)*

| Hexcode  | Description (according to CDE documentation)                                         |
| -------- | ------------------------------------------------------------------------------------ |
| \#b24d7a | Active Window Border                                                                 |
| \#aeb2c3 | Inactive Window Border                                                               |
| \#63639c | Background for workspace switcher One. Also the backdrop becomes this color as well. |
| \#fff7e9 | Background for text entries.                                                         |
| \#68a6a0 | Background for applications.                                                         |
| \#8dadc7 | Background for Menus, panes, workspace switcher Three and Dtterm background.         |
| \#d39798 | Background for workspace Four.                                                       |
| \#9793b5 | Front Panel background, workspace switcher Two and Dtfile background.                |
## dark
*from Solaris 8 (Intel Edition) "NorthernSky" theme*

| Hexcode  | Description (according to CDE documentation)                                         |
| -------- | ------------------------------------------------------------------------------------ |
| \#a47591 | Active Window Border                                                                 |
| \#1b5d6c | Inactive Window Border                                                               |
| \#0c5a87 | Background for workspace switcher One. Also the backdrop becomes this color as well. |
| \#00577a | Background for text entries.                                                         |
| \#41525c | Background for applications.                                                         |
| \#4b7b82 | Background for Menus, panes, workspace switcher Three and Dtterm background.         |
| \#27708b | Background for workspace Four.                                                       |
| \#3d407c | Front Panel background, workspace switcher Two and Dtfile background.                |
# Derived colors
### Border highlights/shadows
- +25% HSL lightness -> window border highlights
- -25% HSL lightness -> window border shadows

element emboss/deboss shadows/highlights are same as inactive window border
## Element colors
### window/element backgrounds
- color 2 -> basic background
- color 4 -> text entry background
- color 2 -7.5% HSL Lightness -> interior shaded areas (used for some elements and some backgrounds)
# Locations where border highlights/shadows are used
### Inactive window border
- border for inactive windows (duh)
- borders for *all* elements (buttons, sunken boxes, lines, etc.)
- interior border for even active windows
### Active window border
- used *only* for active window borders
