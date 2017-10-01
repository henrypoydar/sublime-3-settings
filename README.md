# Sublime 3 Settings

Preferences and settings for Sublime Text 3.

## Installation

Clone this repository into `~/Library/Application Support/Sublime Text 3/Packages/User`
The `.gitignore` file is set up to whitelist only the settings file for this directory.

This is how:

    git init
    git remote add origin PATH/TO/THIS/REPO
    git fetch
    git checkout -t origin/master

## Packages

All packages must be installed via Package Control. Install Package Control following the instructions at https://packagecontrol.io

Basic packages:

- Vintageous
- Origami
- Material Theme
- GitGutter
- Quick File Move
- Quick File Open
- Color Highlighter
- RubyTest

### Manual Installs

Clone `https://github.com/jlangston/Vintageous-Origami` into the 'Packages' directory. Overcomes some brittle Origami settings with Vintageous.

## Enable key repeat

    defaults write com.sublimetext.3 ApplePressAndHoldEnabled -bool false
