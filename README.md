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
    },
    { "keys": ["super+shift+d"], "command": "run_macro_file",
        "args": {"file": "res://Packages/Default/Delete Line.sublime-macro"}
    },
    { "keys": ["home"], "command": "move_to", "args": {"to": "bol"} },
    { "keys": ["end"], "command": "move_to", "args": {"to": "eol"} },
    { "keys": ["shift+end"], "command": "move_to", "args": {"to": "eol", "extend": true} },
    { "keys": ["shift+home"], "command": "move_to", "args": {"to": "bol", "extend": true } }
]
```

Packages
============
Package Control [10/26/2015] (required) https://sublime.wbond.net/installation
```
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

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
