# vscode-vim-settings
```
{
    "editor.fontLigatures": true,
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
      }
    ],
    "vim.handleKeys": {
      "<C-a>": false,
      "<C-f>": false,
    } 
}
```
