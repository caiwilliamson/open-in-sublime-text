# Open in Sublime Text

A simple Automator Quick Action that adds 'Open in Sublime Text' to the Finder Context Menu.

You can also open a selected file or folder by pressing `Shift + Command + S`, or by clicking the 'Open in Sublime Text' Quick Action in the Finder Preview Panel.

## Installation
### Manual

1. [Download](https://github.com/caiwilliamson/open-in-sublime-text/archive/master.zip) and extract the ZIP.
2. Double-click `Open in Sublime Text.workflow`.
3. Click 'Install' in the pop-up.

### Command-line

The following one-liner will download and install 'Open in Sublime Text' for you.
```bash
bash <(curl -s https://raw.githubusercontent.com/caiwilliamson/open-in-sublime-text/master/install)
```
Have a look at the very simple `install` script if you want to know what it does.

## Settings
### Keyboard shortcut
Go to `System Preferences > Keyboard > Shortcuts > Services`. 'Open in Sublime Text' is under the  'Files and Folders' subheading. Click on the shortcut to change/remove it.

### Add/remove from the Finder Context Menu.
Go to `System Preferences > Keyboard > Shortcuts > Services` and enable/disable the check-mark next to 'Open in Sublime Text'.

### Add/remove from the Finder Preview Panel.
Go to `System Preferences > Extensions > Finder` and enable/disable the check-mark next to 'Open in Sublime Text'.

## Uninstallation
`rm -rf ~/Library/Services/Open\ in\ Sublime\ Text.workflow`