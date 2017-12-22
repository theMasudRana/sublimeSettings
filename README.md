# sublimeSettings

Sublime text settings
```
{
	"always_show_minimap_viewport": true,
	"bold_folder_labels": true,
	"draw_minimap_border": true,
	"font_options":
	[
		"gray_antialias",
		"subpixel_antialias"
	],
	"font_size": 12,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_guide_options":
	[
		"draw_normal",
		"draw_active"
	],
	"line_padding_bottom": 0,
	"line_padding_top": 0,
	"material_theme_accent_red": true,
	"overlay_scroll_bars": "enabled",
	"spell_check": true
}
```

# Key Bindings
```
[
	{ "keys": ["ctrl+b"], "command": "toggle_side_bar" },
	{ "keys": ["ctrl+u"], "command": "upper_case" },
	{ "keys": ["ctrl+l"], "command": "lower_case" },
	{ "keys": ["ctrl+alt+s"], "command": "save_all" },
	{ "keys": ["alt+f3"], "command": "find_all_under" },
	{
		"keys": ["alt+shift+1"],
		"command": "set_layout",
		"args":
		{
			"cols": [0.0, 1.0],
			"rows": [0.0, 1.0],
			"cells": [[0, 0, 1, 1]]
		}
	},
	{
		"keys": ["alt+shift+2"],
		"command": "set_layout",
		"args":
		{
			"cols": [0.0, 0.5, 1.0],
			"rows": [0.0, 1.0],
			"cells": [[0, 0, 1, 1], [1, 0, 2, 1]]
		}
	},	
]
```