# Sublime Config

### Plugin List
 - All Autocomplete
 - Babel (React)
 - Babel Snippets (React)
 - Emmet
 - Flow (Javascript analyzer)
 - HexViewer (Hex viewer and editor)
 - Package Control
 - jQuery (Bundle for jQuery)
 - pyV8 (Python Emmet)
 - Sublime Bookmarks
 - Angular 2 Spnippets (John Papa)
 - TypeScript

### Key Bindings  (Preferences > Key Bindings)
```JSON
[
	{ "keys": ["f1"], "command": "sublime_bookmark", "args": {"type": "goto_previous"} },
	{ "keys": ["f5"], "command": "refresh_folder_list"},
	{ "keys": ["tab"], "command": "expand_abbreviation_by_tab", "context":
	    [
	        { "operand": "source.js", "operator": "equal", "match_all": true, "key": "selector" },
	        { "match_all": true, "key": "selection_empty" },
	        { "operator": "equal", "operand": false, "match_all": true, "key": "has_next_field" },
	        { "operand": false, "operator": "equal", "match_all": true, "key": "auto_complete_visible" },
	        { "match_all": true, "key": "is_abbreviation" }
	    ]
	}
]

```
