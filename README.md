# MacXWindowsUniversalUtilityScripts

A set of utility scripts working on both XWindows and macOS. Normally, these kind of scripts to not work on both XWindows and macOS because the underlying system is not the same.

The best way to use most of them is to set keyboard shortcuts to launch them from the GUI.

## Content

### PassWordGenerator

A password generator created in Python.

    PassWordGenerator

### ReadClipboard

A utility script to pipe text to the clipboard:

    echo test | ReadClipboard

### TypePassWord

A utility to type the password genereted by PassWordGenerator. It also copy the password to the clipboard.

    TypePassWord

### TypeSlowly

Simulates key strokes.

    TypeSlowly test

## Requirements

Python needs to be in `$PATH`. Either Python 2 or 3. macOS or XWindows.

## Installation

Put these scripts somewhere in your `$PATH`.

### macOS

No other requirement.

### XWindows

- xdotool
- xsel
