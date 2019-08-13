# Sublime Text3 User Settings


## Settings(\*.sublime-settings)

- Preferences.sublime-settings

## Keymap(\*.sublime-keymap)

- Default (OSX).sublime-keymap
- Default (Windows).sublime-keymap

## Build(\*.sublime-build)

- Python3.sublime-build

- node.sublime-build

## Snippets(\*.sublime-snippet)

- markdown

## Packages(\*.sublime-package)

- Package Control.sublime-package, 直接放入`.\Sublime Text3\Installed Packages`

## Installed Packages

- Package Control
- MarkdownPreview
- Nodejs
- Terminus

## Sublime Settings

### Terminus

- Add environment variables `Path: C:\Program Files\Git\bin`
- `Terminus.sublime-settings`:
```json
"shell_configs": [
    {
        "name": "Git Bash",
        "cmd": "bash.exe",
        "env": {},
        "enable": true,
        "default": true,
        "platforms": ["windows"]
    }
]
```
