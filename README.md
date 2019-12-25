
# Sublime Text Open Auto Completion

How to autocomplete inside a word?

With the package when I press `m` on the step 3, the auto completion show up automatically:

![sublime_shell](https://user-images.githubusercontent.com/5332158/28495366-c78c1578-6f20-11e7-8bbb-dd5ade8348b0.gif)

On the animation I:

1. Type `m` then press enter for the autocomplete
1. Press `left_arrow`, left_arrow`, left_arrow`, `backspace`
1. Then I press `m` again.

But without the package, Sublime Text does not show the auto completion:

![sublime_shell](https://user-images.githubusercontent.com/5332158/28495372-e5489c58-6f20-11e7-8a60-ae99d5472d8f.gif)

It open the auto completion when typing inside a word.


## Installation

### By Package Control

1. Download & Install **`Sublime Text 3`** (https://www.sublimetext.com/3)
1. Go to the menu **`Tools -> Install Package Control`**, then,
   wait few seconds until the installation finishes up
1. Now,
   Go to the menu **`Preferences -> Package Control`**
1. Type **`Add Channel`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Go to the menu **`Tools -> Command Palette...
   (Ctrl+Shift+P)`**
1. Type **`Preferences:
   Package Control Settings – User`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   find the following setting on your **`Package Control.sublime-settings`** file:
   ```js
       "channels":
       [
           "https://packagecontrol.io/channel_v3.json",
           "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
       ],
   ```
1. And,
   change it to the following, i.e.,
   put the **`https://raw.githubusercontent...`** line as first:
   ```js
       "channels":
       [
           "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
           "https://packagecontrol.io/channel_v3.json",
       ],
   ```
   * The **`https://raw.githubusercontent...`** line must to be added before the **`https://packagecontrol.io...`** one, otherwise,
     you will not install this forked version of the package,
     but the original available on the Package Control default channel **`https://packagecontrol.io...`**
1. Now,
   go to the menu **`Preferences -> Package Control`**
1. Type **`Install Package`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
search for **`OpenAutoCompletion`** and press <kbd>Enter</kbd>

See also:

1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


## Bibliography

1. https://forum.sublimetext.com/t/how-to-autocomplete-inside-a-word/28646
1. [SublimeTextIssues#1829](https://github.com/SublimeTextIssues/Core/issues/1829) A new setting to allow open the auto completion when inside word


## License

All files in this repository are released under GNU General Public License v3.0
or the latest version available on http://www.gnu.org/licenses/gpl.html

1. The [LICENSE](LICENSE) file for the GPL v3.0 license
1. The website https://www.gnu.org/licenses/gpl-3.0.en.html

For more information.


