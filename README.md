# Sublime Text 2 W3C Console Validator

Sublime Text 2 Inline Console W3C Validator for Mac

## Requirements

1. Homebrew Package Installer for Mac
	- Download Here: [Homebrew Package Manager](http://brew.sh/)
2. cURL Command Line Tool
	- Run this command in Terminal:
	`$ brew install curl`

## Installation

### 1. Copy Python Files

Copy the *validate.py* and *w3c-validator.py* files into Sublime's Package folder.

Finder Path:
`/Library/Application Support/Sublime Text 2/Packages/User`

### 2. Map Sublime Keyboard Shortcut

In Sublime, Go To:

**Sublime Text 2 > Preferences > Key Bindings - User**
	
Copy/paste this snippet:	
	
	[
		{ "keys": ["ctrl+alt+v"], "command": "validate" }
	]
	
### 3. Restart Sublime

Cmd + Q

##Usage

1. Open a CSS/HTML page within Sublime
2. Open Sublime Console *(View > Show Console)*
3. Use Key Command: *Ctrl+Alt+V*

---

Soruce: [@ehamiter](https://github.com/ehamiter) via [SublimeText.com Forums](http://www.sublimetext.com/forum/viewtopic.php?f=5&t=2262)
