# vscode-vim-settings
```
Apart from these settings i change Alt + UP to Alt + k and Alt + DOWN to Alt + j in VS Code keyboard mapping
{
    "vim.easymotion": true,
    "vim.sneak": true,
    "vim.incsearch": true,
    "vim.hlsearch": true,
    
    // My settings start here
    
    "vim.useCtrlKeys": true,
    "vim.useSystemClipboard": true,
    // Insert mode
    "vim.insertModeKeyBindings": [
      // In insert mode jj to escape
      {
        "before": ["j", "j"],
        "after": ["<Esc>"]
      },
      // Ctrl + q to escape
      {
        "before": ["<C-q>"],
        "after": ["<Esc>"]
      }
    ],
    // Visual mode
    "vim.visualModeKeyBindings": [
      // In visual mode i goes to insert mode
      {
        "before": ["i"],
        "after": ["<Esc>", "i"]
      },
      // Ctrl + q to escape
      {
        "before": ["<C-q>"],
        "after": ["<Esc>"]
      }
    ],
    "vim.normalModeKeyBindingsNonRecursive": [
      // Ctrl + q to escape
      {
        "before": ["<C-q>"],
        "after": ["<Esc>"]
      }
    ],
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
