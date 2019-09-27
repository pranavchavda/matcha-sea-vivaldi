# Vivaldi Matcha Sea Theme


The Matcha Sea theme (this one) is forked from https://github.com/drakkar1969/Vivaldi-Arc-Theme
it is set of custom css files that integrate Vivaldi's UI with Manjaro 18.1's default gnome and xfce theme Rework of Tiamarth's [original theme](https://github.com/Tiamarth/Arc-for-Vivaldi) for Vivaldi.


This is my first time using github, so please forgive the lack of commits, etc. I'll learn as I go.


## Screenshots:
(soon)
## Features:

- Vivaldi, but looks great on manjaro with matcha sea.

## Installation

Find the `style` directory in your Vivaldi install directory, which should be in the following location: `/opt/vivaldi/resources/vivaldi/style`.  

To **integrate with Arc,** save `arc.css` in the `style` directory (you should be left with a directory structure like this: `resources/vivaldi/style/arc.css`). Then open `resources/vivaldi/browser.html` in a text and add the following to `<head>`  
`<link rel="stylesheet" href="style/arc.css" />`

This custom CSS integrates settings in Vivaldi's built-in theme editor (the custom CSS is necessary to integrate with Arc because you cannot currently customize every aspect of Vivaldi from the editor).  

Alternatively, clone this into any directory and specify the directory under tools->settings->appearance->custom ui modification. this feature may not be enabled by default, check vivaldi's settings.ini file to enable it

Settings for Vivaldi's built-in theme editor:

| Matcha Sea                         | Matcha Dark Sea                    | Matcha Light Sea                  |
| --------------------------------- | --------------------------------- | --------------------------------- |
| Background: #f7f7f7               | 
| Foreground: #273134               |
| Highlight: #2eb398                | 
| Accent: #1b2224                   |
| [ ] Accent Color from Active Page |
| [x] Apply Accent Color to Window  |
| [x] Transparent Tabs              |
| Corner Rounding: 3px              |

-----------------------

*Note*: I really wish this wasn't necessary and that Vivaldi would detect the current gtk theme and theme itself the way chrome and firefox already do. 
