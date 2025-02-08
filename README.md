{
"files.autoSave": "afterDelay",
"prettier.useTabs": true,
"prettier.trailingComma": "all",
"prettier.singleQuote": true,
"prettier.singleAttributePerLine": true,
"workbench.iconTheme": "vscode-icons",
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.cursorSmoothCaretAnimation": "on",
"editor.cursorStyle": "block",
"editor.lineHeight": 1.7,
"json.schemas": [],
"workbench.colorTheme": "Rosé Pine",
"supermaven.enable": {
"\*": false
},
"workbench.sideBar.location": "right",
"workbench.activityBar.location": "hidden",
"vim.commandLineModeKeyBindings": [],
"vim.commandLineModeKeyBindingsNonRecursive": [],
//
"editor.formatOnSave": true,
"editor.suggest.insertMode": "replace",
"terminal.integrated.fontFamily": "MesloLGS NF",
"editor.linkedEditing": true,
"javascript.updateImportsOnFileMove.enabled": "always",
"window.zoomLevel": 0.5,
"launch": {},
"[json]": {},
"workbench.statusBar.visible": false,
"editor.minimap.enabled": false,
"breadcrumbs.enabled": false,
"update.showReleaseNotes": false,
"zenMode.hideLineNumbers": false,
"editor.lineNumbers": "relative",
"vim.leader": "<Space>",
"vim.hlsearch": true,
"vim.normalModeKeyBindingsNonRecursive": [
// NAVIGATION
// switch b/w buffers
{ "before": ["<S-h>"], "commands": [":bprevious"] },
{ "before": ["<S-l>"], "commands": [":bnext"] },

    	// splits
    	{ "before": ["leader", "v"], "commands": [":vsplit"] },
    	{ "before": ["leader", "s"], "commands": [":split"] },

    	// panes
    	{
    		"before": ["leader", "h"],
    		"commands": ["workbench.action.focusLeftGroup"]
    	},
    	{
    		"before": ["leader", "j"],
    		"commands": ["workbench.action.focusBelowGroup"]
    	},
    	{
    		"before": ["leader", "k"],
    		"commands": ["workbench.action.focusAboveGroup"]
    	},
    	{
    		"before": ["leader", "l"],
    		"commands": ["workbench.action.focusRightGroup"]
    	},
    	// NICE TO HAVE
    	{ "before": ["leader", "w"], "commands": [":w!"] },
    	{ "before": ["leader", "q"], "commands": [":q!"] },
    	{ "before": ["leader", "x"], "commands": [":x!"] },
    	{
    		"before": ["[", "d"],
    		"commands": ["editor.action.marker.prev"]
    	},
    	{
    		"before": ["]", "d"],
    		"commands": ["editor.action.marker.next"]
    	},
    	{
    		"before": ["<leader>", "c", "a"],
    		"commands": ["editor.action.quickFix"]
    	},
    	{ "before": ["leader", "f"], "commands": ["workbench.action.quickOpen"] },
    	{ "before": ["leader", "p"], "commands": ["editor.action.formatDocument"] },
    	{
    		"before": ["g", "h"],
    		"commands": ["editor.action.showDefinitionPreviewHover"]
    	}
    ],
    "vim.visualModeKeyBindings": [
    	// Stay in visual mode while indenting
    	{ "before": ["<"], "commands": ["editor.action.outdentLines"] },
    	{ "before": [">"], "commands": ["editor.action.indentLines"] },
    	// Move selected lines while staying in visual mode
    	{ "before": ["J"], "commands": ["editor.action.moveLinesDownAction"] },
    	{ "before": ["K"], "commands": ["editor.action.moveLinesUpAction"] },
    	// toggle comment selection
    	{ "before": ["leader", "c"], "commands": ["editor.action.commentLine"] }
    ],
    "[typescriptreact]": {
    	"editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
    	"editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
    	"editor.defaultFormatter": "esbenp.prettier-vscode"
    }

}
