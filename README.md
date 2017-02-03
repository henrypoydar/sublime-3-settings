# Sublime 3 Settings

Preferences and settings for Sublime Text 3.

## Installation

Clone this repository into `/Users/henrypoydar/Library/Application Support/Sublime Text 3/Packages/User`
The `.gitignore` file is set up to whitelist only the settings file for this directory.

This is how:

    git init
    git remote add origin PATH/TO/REPO
    git fetch
    git checkout -t origin/master

## Packages

All packages must be installed via Package Control. Install Package Control following the instructions at https://packagecontrol.io

Basic packages:

- Vintageous
- VintageousOrigami
- Material Theme

## Enable key repeat

    defaults write com.sublimetext.3 ApplePressAndHoldEnabled -bool false
