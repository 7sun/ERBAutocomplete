ERB Autocomplete
======================
The package to help use erb template user that easy and quick to finish the ERB tag.
***

How to install
-------------

With [Package Control](http://wbond.net/sublime_packages/package_control):

1. Run "Package Control: Install Package" command, find and install `ERBAutocomplete` package.
2. Restart your sublime text editor.


Manually:

1. Clone or [download](https://github.com/CasperLaiTW/ERBAutocomplete/archive/master.zip "download") git repo into your Sublime Text packages folder.
  ```
  git clone https://github.com/CasperLaiTW/ERBAutocomplete.git "ERB Autocomplete"
  ```
2. Restart your sublime text editor.

*We are support ST2 and ST3 now.*
Usage
-------------
You would set syntax to **ERB**.

And you can:

Manually:

1. Type ERB keyword like **if**, **else** or nothing.
2. Press `ctrl` + `space`, will activate completion. ST would popup to tip you and select you want.

Automatic completion:

1. Open your user settings file.
2. Add `text.html.erb` to `auto_complete_selector`, you should according to your settings to set.

  This is example.
  ```json
  "auto_complete_selector" : "text.html.erb, source - comment, meta.tag - punctuation.definition.tag.begin"
  ```
3. Reset your Sublime Text editor.
4. And now you type **if**, **else**, the editor will automatic activate completion.


Mark / Unmark Comment
-------------
OSX:

* Mark comment – <kbd>Command+.</kbd>
* Unmark comment – <kbd>Command+,</kbd>

Linux / Windows:

* Mark comment – <kbd>Ctrl+.</kbd>
* Unmark comment – <kbd>Ctrl+,</kbd>





