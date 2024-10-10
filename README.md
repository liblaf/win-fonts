# Windows Fonts

[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/liblaf/win-fonts/ci.yaml)](https://github.com/liblaf/win-fonts/actions/workflows/ci.yaml)

| Language             | Windows 11                                                                                       | Windows 10                                                                                       |
| -------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| Chinese (Simplified) | [link](https://github.com/liblaf/win-fonts/releases/download/Win11/Win11-Chinese_Simplified.zip) | [link](https://github.com/liblaf/win-fonts/releases/download/Win10/Win10-Chinese_Simplified.zip) |
| English              | [link](https://github.com/liblaf/win-fonts/releases/download/Win11/Win11-English.zip)            | [link](https://github.com/liblaf/win-fonts/releases/download/Win10/Win10-English.zip)            |

## Installation

### Linux

```bash
WIN=Win11
LANG=Chinese_Simplified
zip_file="$HOME/Downloads/$WIN-$LANG.zip"
wget --output-document="$zip_file" https://github.com/liblaf/win-fonts/releases/download/$WIN/$WIN-$LANG.zip
unzip -d "$HOME/.local/share/fonts/$WIN" "$zip_file"
fc-cache --force --verbose
```
