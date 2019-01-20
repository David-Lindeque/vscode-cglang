# vscode-cglang
Visual Studio Code integration of cglang.
Gherkin for C++.

See [cglang](https://github.com/David-Lindeque/cglang) for the **cglang** tool and documentation.

## Syntax Colourization
The extension provides a colourization grammar. It compatible with the standard themes.

## Snippets
The extension provides snippets for the most used bits of code. The following snippet triggers are available. Give them a try.
* feature
* background
* scenario
* outline
* import
* define
* grammar
* case

## Tips
* Make C++ sections more visible by changing the font settings of the specific section. The section associated with the C++ block are wrapped in the ```meta.embedded.block.cpp.cgfeature``` scope. For instance, edit the user settings file and add/update the following node.
```json
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "name": "meta.embedded.block.cpp.cgfeature",
                "scope": "meta.embedded.block.cpp.cgfeature",
                "settings": {
                    "fontStyle": "italic"
                }
            }
        ]
    }
```

## Installation
To install this extension, either clone the repo and git it installed (i.e.: build your own vsix file), or download and install the vsix file included in this repository. In order to do this, follow the following steps:
* Download the .vsix file (https://github.com/David-Lindeque/vscode-cglang/blob/master/vscode-cglang-0.0.1.vsix).
* In VSCode, on the 'Extensions' tab, click on the '...' and select 'Install from VSIX...'
* Select the downloaded .vsix file and click 'Install'.
* You might have to restart VSCode.

## More information

<small>See https://github.com/David-Lindeque/vscode-cglang for details about the extension.</small> 

<small>David Lindeque</small>