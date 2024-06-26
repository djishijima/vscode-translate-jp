<<<<<<< HEAD
# vscode-translate-jp
VS Code 用のGoogle/Bing テキスト/コメント翻訳拡張機能
=======
# Translate it

This extension is a text/comment translator powered by **Google Translate** (or **Bing Translator**).

## Features

- Translates selected texts from `Source Language` to `Target Language`
  - Automatically detects `Source Language` and `Target Language`
    - `Automatic Target Language` is your prefer display language of VSCode
    - You can also change the `Target Language` in the **Extension Settings**
- Translates only comments when you select comments and codes
  - Supports more than 30 programming languages
  - See below a [demo](#usage)
- Displays translated result as **Hover Message**
  - You can change the `Target Language` and re-translate, by click **Target Language** on header of hover message
  - See below a [demo](#usage)
- And supports history logging in the **Output Channel**
  - See below a [demo](#history-logging)
- Now, you can choose your preferred translation API
  - Currently, `Google` and `Bing` translation APIs are supported

## Installation

To install this extension go to `View->Extensions` and search for `translate-jp` (or `Translate it`). Next click Install.

## Usage

To use the extension go to the Command Palette (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on Windows) and launch `Translate it` command.
> Recommends to use keyboard shortcut `Shift+Alt+T`.

![Demo 1](./images/readme/demo1.gif)

Or select `Translate it` from context menu (`Right-click` on editor).
> It's available when you select some text (single or multi select).

![Demo 2](./images/readme/demo2.png)

And you can remove translation highlighting, if you select `Remove Translation Highlighting` from context menu (`Right-click` on editor).
> or Launch `Translate it: Remove Translation Highlighting` command on the Command Palette.  

> Recommends to use keyboard shortcut `Shift+Alt+T`.

![Demo 3](./images/readme/demo3.png)

## History Logging

You can find the histories of translation in the **Output Channel**.

![Demo 4](./images/readme/demo4.png)

## Settings

Table of contributed settings (prefix "translateIt."):

| Name                     | Default       | Description                                                                                            |
| ------------------------ | ------------- | ------------------------------------------------------------------------------------------------------ |
| hoverDisplay             | `true`        | Display translated result as hover message (if `false`, always open **Output Channel** instead)        |
| hoverDisplayHeader       | `true`        | Display hover message with header area : `"Source Language → Target Language"`                         |
| hoverMultiLineFormatting | `true`        | Display hover message with Multi-Line Formatting                                                       |
| targetLanguage           | `"Automatic"` | Target language ([list the supported](https://cloud.google.com/translate/docs/languages)) translate to |
| api                      | `"Google"`    | Preferred translation api to used                                                                      |

## Issues

If you find any problems using this extension or you want to propose new features to it, feel free to open an issue on [Github](https://github.com/djishijima/vscode-translate-jp/issues).

## Release Notes

Detailed Release Notes are available [here](https://github.com/djishijima/vscode-translate-jp/blob/master/CHANGELOG.md) or above **Changelog** tab.

## Attributions

Icon made by [Freepik](https://www.flaticon.com/authors/freepik) from [www.flaticon.com](https://www.flaticon.com/)
>>>>>>> 4b84085 (Initial commit)
