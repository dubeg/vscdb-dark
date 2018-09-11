# VSCDB Dark
VSCode dubeg's dark theme.


## Theme definition
```
{
    "name": "VSCDB Dark",
    "type": "dark",
    "colors": {
        ...
    },
    "tokenColors": [
        ...
    ]
}
```


## Overrides 
User settings: `AppData/.../settings.json`
```json
{
    "workbench.colorCustomizations": {
        ...
    },
    "editor.tokenColorCustomizations" : {
        "textMateRules": [
            ...
        ]
    }
}

```


## File icons
Icons next to files and folders in the Explorer pane have their own different extension. I personally use `Studio Icons` by Jordan Lowe, but I dislike the expand arrows visible by default. 

To turn them off, open:

```
.vscode\extensions\<fileIconDir>\fileicons\<fileIconName>.json
```

Add at the top-level node of the file:

```
"hidesExplorerArrows": true
```


## Docs
- Docs: https://code.visualstudio.com/docs/getstarted/theme-color-reference
- Defaults: `C:\Program Files (x86)\Microsoft VS Code\resources\app\extensions\theme-defaults\themes\`
- Publishing: `https://code.visualstudio.com/docs/extensions/publish-extension#_publishing-extensions`