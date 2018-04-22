# MacVim_config_files
This is my vim configuration for my system. 

Use cask if you don't have xcode installed or you are not able to install.
(If you have two vim version installed)

-  `brew cask install macvim --override-system-vim`
-  ` brew install vim`

Use `.vim` and `.vimrc` file from this repo. 

- Run `:BundleInstall`

### Shortcuts 

#### Line

* You can use ^ or 0 (Zero) in normal mode to move to the beginning of a line.

      ^ moves the cursor to the first non-blank character of a line
      0 always moves the cursor to the "first column"

You can also use Shifti to move and switch to Insert mode.

* No need to explicitly go to the end of line before doing a, use A;
Append text at the end of line [count] times

<ESC>GA



#### REFRESH THE PAGE :


* bufdo == this will reload all files in buffer.

#### To undo recent changes, from normal mode use the undo command:


u : undo last change (can be repeated to undo preceding commands)

Ctrl-R : Redo changes which were undone (undo the undos). Compare to . to
repeat a previous change, at the current cursor position.

#### SEARCH A WORD 

Press / and type word to search
To search in forward press 'SHIFT' key with  * key
To search in backward press 'SHIFT' key with # key

#### from NERD TREEE TO file opens right 

This will move between open windows (so you could hop between the NERDTree window, the file you are editing and the help window, for example... just hold down Ctrl and press w twice).
