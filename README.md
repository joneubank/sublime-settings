# sublime-setup
Sublime Text 3 Custom User Settings

Includes Key Bindings and Preferences

## Setup Instructions
Clone this repository into the Sublime Text User preferences folder:

With path relative to user directory on OSX, default install location:
```
git clone https://github.com/joneubank/sublime-setup.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```

## Preferences

Listing here options that have been overwritten from the defaults.


### Display

* **Sublime Theme**: Default
* **Size**: 14
* **Margin**: 0
* **Fade Fold Buttons**: False
* **Ruler**: 79 - Indicator for max standard line length, follows PEP8 standard
* **Tabs as Spaces**: True
* **Highlight current line**: True
* **Caret**: Solid and wide
* **Draw White Space**: All
* **Indent Guides**: Draw Active


### Controls
* **Word Separators**: added underscores
* **Scroll past end**: true
* **Trailing White Space**: Trim on save, force last line is newline character
* **Line Endings**: Unix
* **Shift Tab**: Always un-indent
* **Find Selected Text**: Set true for cross-platform consistency


## Application
* **Ignore Folders**: target (java war build path)


## Key Bindings

Key bindings setup for OSX use:

| Keys | Command |
|:---- |:------- |
| Cmd + Shift + D | Delete Line |
| Cmd + Shift + C | Duplicate Line (Copy Below) |
