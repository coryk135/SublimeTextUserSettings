SublimeTextUserSettings
=======================

My Sublime Text 2/3 User Settings Configuration
```json
{
	"bold_folder_labels": true,
	"caret_style": "phase",
	"close_windows_when_empty": true,
	"color_scheme": "Packages/Theme - Spacegray/base16-eighties.dark.tmTheme",
	"ensure_newline_at_eof_on_save": true,
	"font_size": 12,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
	],
	"indent_guide_options":
	[
		"draw_active"
	],
	"save_on_focus_lost": true,
	"scroll_past_end": true,
	"shift_tab_unindent": true,
	"theme": "Spacegray Eighties.sublime-theme",
	"translate_tabs_to_spaces": true
}

```

Key Binding
```json
[
    { "keys": ["j", "k"], "command": "exit_insert_mode", "context":
        [
            { "key": "setting.command_mode", "operand": false },
            { "key": "setting.is_widget", "operand": false }
        ]
    },
    { "keys": ["super+c"], "command": "noop", "context":
        [
            { "key": "selection_empty", "operator": "equal",
              "operand": true, "match_all": true }
        ]
    },
    { "keys": ["super+x"], "command": "noop", "context":
        [
            { "key": "selection_empty", "operator": "equal",
              "operand": true, "match_all": true }
        ]
    },
    { "keys": ["ctrl+c"], "command": "noop", "context":
        [
            { "key": "selection_empty", "operator": "equal",
              "operand": true, "match_all": true }
        ]
    },
    { "keys": ["ctrl+x"], "command": "noop", "context":
        [
            { "key": "selection_empty", "operator": "equal",
              "operand": true, "match_all": true }
        ]
    }
]
```

Packages
============
Package Control (required) https://sublime.wbond.net/installation
```
Emmet
Git
GitGutter
JsFormat
LESS
SideBarEnchancements
SublimeAStyleFormatter
Theme - Spacegray
Floobits
```
