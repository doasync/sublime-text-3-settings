# Sublime Text 3 Settings (by DoAsync)

![Example1](http://i.imgur.com/ZzlLkZG.png)

![Example2](http://i.imgur.com/wRwDALx.png)

### Packages

Packages installed from [Package Control](https://packagecontrol.io)

 - A File Icon
 - All Autocomplete
 - Babel
 - Boxy Theme
 - BracketHighlighter
 - CSS3
 - DocBlockr
 - Emmet
 - FileDiffs
 - GitGutter
 - Hayaku - tools for writing CSS faster
 - HTML-CSS-JS Prettify
 - JavaScript Completions
 - LESS
 - Less Tabs
 - Local History
 - Package Control
 - Sass
 - SideBarEnhancements
 - SublimeCodeIntel
 - SublimeLinter
 - SublimeLinter-contrib-eslint
 - SyncedSideBar
 - Tab Filter
 - TabsExtra

### Installation

1. Go to *Preferences -> Browse packages...*
2. Open `User` folder
3. Clone the repo to this folder

#### Windows 10

  ```bash
  cd %AppData%\Sublime Text 3\Packages\User
  git clone https://github.com/doasync/sublime-text-3-settings.git .
  ```

#### Ubuntu 17

  ```bash
  cd ~/.config/sublime-text-3/Packages/User
  git clone https://github.com/doasync/sublime-text-3-settings.git .
  ```

### General config

```json
{
  "always_show_minimap_viewport": true,
  "auto_complete_with_fields": true,
  "auto_find_in_selection": true,
  "caret_style": "blink",
  "detect_indentation": false,
  "drag_text": true,
  "draw_white_space": "selection",
  "ensure_newline_at_eof_on_save": true,
  "fallback_encoding": "UTF-8",
  "show_encoding": true,
  "folder_exclude_patterns": [".sass-cache", "node_modules"],
  "font_options": ["directwrite", "subpixel_antialias"],
  "highlight_line": true,
  "highlight_modified_tabs": true,
  "ignored_packages": ["Vintage", "ZenCoding"],
  "line_padding_bottom": 1,
  "line_padding_top": 1,
  "open_files_in_new_window": false,
  "tab_size": 2,
  "hot_exit": true,
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "word_separators": "./\\()\"'-:,.;<>~!@#%^&*|+=[]{}`~?",
  "word_wrap": "false"
}
```
