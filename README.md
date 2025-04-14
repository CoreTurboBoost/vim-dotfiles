# Vim configuration files

## Assumptions

 - These configuration files are intended to be used only on Unix like operating system, such as Linux.
 - Theses configuration files have only been tested on Debian Linux. Therefore they may not work on other operating systems.

## File placement

Move the files in `vim-config` to your local configuration directory (`~/.config/vim/`).
Move the files in `vim-runtime` to your local vim runtime directory (`~/.vim/`).
You may move `vimrc` to your home directory (`~/`) and name it `.vimrc`, resulting in the file `~/.vimrc`. This would be the default vim configuration (Make sure to backup an existing `~/.vimrc` if it already exists).

## Making aliases

Then make an alias to `~/.config/vim/vim-code` for the code editor and `~/.config/vim/vim-text` for the text editor. The aliases should be in your `~/.bashrc`.

- alias vimc="vim -u ~/.config/vim/vim-code"
- alias vimt="vim -u ~/.config/vim/vim-text"

## Opening the text editor

- To open the code editor run the `vimc` command. Just after opening the editor run `:PlugInstall` to install the new plug-ins.
- To open the text editor run the `vimt` command.
