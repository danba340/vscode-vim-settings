# vscode-vim-settings
```
{
    "vim.easymotion": true,
    "vim.sneak": true,
    "vim.incsearch": true,
    "vim.useSystemClipboard": true,
    "vim.useCtrlKeys": true,
    "vim.hlsearch": true,
    "vim.insertModeKeyBindings": [
      {
        "before": ["j", "j"],
        "after": ["<Esc>"]
      },
      {
        "before": ["<C-q>"],
        "after": ["<Esc>"]
      }
    ],
    "vim.visualModeKeyBindings": [
      {
        "before": ["i", "i"],
        "after": ["<Esc>"]
      },
      {
        "before": ["<C-q>"],
        "after": ["<Esc>"]
      }
    ],
    "vim.normalModeKeyBindingsNonRecursive": [
      {
        "before": ["<C-j>"],
        "commands": ["editor.action.moveLinesDownAction"]
      },
      {
        "before": ["<C-k>"],
        "commands": ["editor.action.moveLinesUpAction"]
      },
      {
        "before": ["<C-q>"],
        "after": ["<Esc>"]
      }
    ],
    "vim.handleKeys": {
      "<C-a>": false,
      "<C-f>": false,
      "<C-d>": false,
    },
}
```
