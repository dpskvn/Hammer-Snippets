Hammer for Mac snippets for Sublime Text
========================================

## About

A small collection of useful [Sublime Text](http://www.sublimetext.com/) snippets to be used with [Riot's](http://riothq.com) wonderful app [Hammer for Mac](http://hammerformac.com).

## Installation

### Via Package Control

1. Install [Package Control](http://wbond.net/sublime_packages/package_control)
2. Hit `⌘+⇧+P` to open the Command Palette
3. Look for Package Control: Install Package and hit `↵`
4. Search for `Hammer for Mac Snippets` and hit `↵`

### Manual

Navigate to your Packages directory and clone this repository:
    
    $ git clone https://github.com/DinoPaskvan/Hammer-Snippets.git

## Usage

Just type one of the triggers and hit `TAB` inside the editor.

| Snippet                  | Trigger | Output                               |
|--------------------------|:-------:|:------------------------------------:|
| HTML Include             | h-inc   | `<!-- @include filename -->`         |
| JavaScript Link (file)   | h-js    | `<!-- @javascript filename -->`      |
| JavaScript Link (folder) | h-jsf   | `<!-- @javascript path/to/js/* -->`  |
| Stylesheet Link (file)   | h-st    | `<!-- @javascript filename -->`      |
| Stylesheet Link (folder) | h-stf   | `<!-- @javascript path/to/css/* -->` |
| Smart Path               | h-pa    | `<!-- @path filename -->`            |
| Automatic Reload         | h-rel   | `<!-- @reload -->`                   |
| Image Placeholder        | h-img   | `<!-- @placeholder 300x400 Text -->` |
| Variable                 | h-var   | `<!-- $name value -->`               |
| Variable (Default Value) | h-vard  | `<!-- $name | Default Value -->`     |
| To do                    | h-td    | `<!-- @todo To Do Text -->` __(*)__  |
| 404 Fix                  | h-404   | `<base href="/">`                    |

__(*)__ Output varies for each language (HTML, CSS, SCSS, CoffeeScript, JavaScript). Table shows HTML output.


## Contributions

Feel free to fork this repository, fiddle with things and send pull requests.


## License

This plugin is licensed under the [MIT license](https://raw.github.com/DinoPaskvan/Hammer-Snippets/master/LICENSE).