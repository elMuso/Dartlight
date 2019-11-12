# Dartlight
It's for now, a fork of the official Dart highlight JSON to work with Sublime Text and Textastic. Some minor changes were made to work as a tmLanguage file.

## Installation for Sublime Text

Once you have [Package Control](http://wbond.net/sublime_packages/package_control) installed, follow
these instructions to install Dartlight for Sublime Text:

- Open the command palette:

  Operating System  | Keyboard Shortcut
  ----------------  | -----------------
  Linux             | <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
  Mac OS X          | <kbd>⌘</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> 
  Windows           | <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>

- Type 'install'
- Select **Package Control: Install Package**
- Type 'dartlight'
- Select **Dartlight**

You may need to restart Sublime Text
before you can start using all the features
in the Dartlight plugin.

## Installation for Textastic

On Mac OS X, clone this repository inside of `~/Library/Containers/com.textasticapp.textastic-mac/Data/Library/Application Support/Textastic`, then restart Textastic.

On iPad OS:
- Install [Working Copy](https://apps.apple.com/us/app/working-copy/id896694807) from the App Store and use it to clone this repository
- Start Textastic and go to 'Local Files'
- Create a folder named `#Textastic` (case sensitive, it should get a special cogwheel icon)
- Open both apps at once and drag the Dartlight folder into the `#Textastic` folder
- Close Textastic completely by swiping upwards in the app switcher, then restart it.

Please note that Textastic does not update Dartlight automatically.
