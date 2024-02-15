preview:       
![color-scheme-preview.png](https://github.com/eztaah/simpledocs/blob/main/docs/color-scheme-preview.png?raw=true)

<br>

to apply the displayed color scheme, integrate the following JSON configuration into your settings:       
```json
{
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "comment.sd",
                "settings": {
                    "foreground": "#808080",
                    "fontStyle": "italic"
                }
            },
            {
                "scope": "bold.sd",
                "settings": {
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "title.sd",
                "settings": {
                    "foreground": "#b7895f",
                    "fontStyle": ""
                }
            },
            {
                "scope": "codeblock-border.sd",
                "settings": {
                    "foreground": "#a9ad5d",
                    "fontStyle": ""
                }
            },
            {
                "scope": "codeblock-content.sd",
                "settings": {
                    "foreground": "#95965c",
                    "fontStyle": ""
                }
            },
        ]
    }
}
```

<br>

build from source:    
$ vsce package --no-yarn

<br>

publish and manage extension:     
[https://code.visualstudio.com/api/working-with-extensions/publishing-extension](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)       
[https://marketplace.visualstudio.com/manage/publishers/eztaah](https://marketplace.visualstudio.com/manage/publishers/eztaah)     