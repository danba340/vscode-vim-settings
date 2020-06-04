# vscode-vim-settings

### Apart from below settings i also change in VS Code keyboard mappings:
From      |To     |
----------|-------|
Alt + UP  |Alt + k|
Alt + Down|Alt + j|

```javascript

{    
    "vim.useCtrlKeys": true,
    "vim.useSystemClipboard": true,
    // Insert mode
    "vim.insertModeKeyBindings": [
      // In insert mode jj to escape
      {
        "before": ["j", "j"],
        "after": ["<Esc>"]
      }
    ],
    // Visual mode
    "vim.visualModeKeyBindings": [
      // In visual mode i goes to insert mode
      {
        "before": ["i"],
        "after": ["<Esc>", "i"]
      }
    ],
    // Escaping from vim for below commands
    "vim.handleKeys": {
      // Select all
      "<C-a>": false,
      // VS Code search in file
      "<C-f>": false,
      // VS Code new marker @ next occurence
      "<C-d>": false,
      // Copy
      "<C-c>": false,
      // Cut
      "<C-x>": false,
      // Paste
      "<C-v>": false,
    },
}
```
