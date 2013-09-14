Hammer for Mac snippets for Sublime Text
========================================

## About

A small collection of useful [Sublime Text](http://www.sublimetext.com/) snippets to be used with [Riot's](http://riothq.com) wonderful app [Hammer for Mac](http://hammerformac.com).

## Installation

### Via Package Control

1. Install [Package Control](https://sublime.wbond.net/)
2. Hit `⌘+⇧+P` to open the Command Palette
3. Look for Package Control: Install Package and hit `↵`
4. Search for `Hammer for Mac Snippets` and hit `↵`

### Manual

Navigate to your Packages directory and clone this repository:
    
    $ git clone https://github.com/DinoPaskvan/Hammer-Snippets.git

## Usage

Just type one of the triggers and hit `TAB` inside the editor.

| Snippet                  | Trigger | Output                                        |
|--------------------------|:-------:|:---------------------------------------------:|
| 404 Fix                  | h-404   | `<base href="/">`                             |
| Automatic Reload         | h-rel   | `<!-- @reload -->`                            |
| HTML Include             | h-inc   | `<!-- @include filename -->`                  |
| Image Placeholder        | h-img   | `<!-- @placeholder 300x400 Text -->`          |
| JavaScript Link (file)   | h-js    | `<!-- @javascript filename -->`               |
| JavaScript Link (folder) | h-jsf   | `<!-- @javascript path/to/js/* -->`           |
| Smart Path               | h-pa    | `<!-- @path filename -->`                     |
| Stylesheet Link (file)   | h-st    | `<!-- @stylesheet filename -->`               |
| Stylesheet Link (folder) | h-stf   | `<!-- @stylesheet path/to/css/* -->`          |
| To do                    | h-td    | `<!-- @todo To Do Text -->` __(1)__           |
| Variable                 | h-var   | `<!-- $name value -->`                        |
| Variable (Default Value) | h-vard  | `<!-- $name [pipe] Default Value -->` __(2)__ |

__(1)__ Output varies for each language (HTML, HAML, CSS, SCSS, CoffeeScript, JavaScript). Table shows HTML output.   
__(2)__ The `|` character breaks the table syntax and cannot be escaped. The actual output is: `<!-- $name | Default Value -->`

## Contributions

Feel free to fork this repository, fiddle with things and send pull requests.


## License

This plugin is licensed under the [MIT license](https://raw.github.com/DinoPaskvan/Hammer-Snippets/master/LICENSE).