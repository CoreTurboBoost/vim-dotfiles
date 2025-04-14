# Vim configuration files

## File placement

Move the files in `vim-config` to your local configuration directory (`~/.config/vim/` on Unix systems).
Move the files in `vim-runtime` to your local vim runtime directory (`~/.vim/`).
Move `vimrc` to your home directory (`~/`) and name it `.vimrc`, resulting in a file `~/.vimrc`. This is the default vim configuration (Make sure to backup an existing `~/.vimrc` if it already exists).

## Making aliases

Then make an alias to `~/.config/vim/vim-code` for the code editor and `~/.config/vim/vim-text` for the text editor. The aliases should be in your `~/.bashrc`.

- alias vimc="vim -u ~/.config/vim/vim-code"
- alias vimt="vim -u ~/.config/vim/vim-text"

## Opening the text editor

To open the code editor run the `vimc` command.
To open the text editor run the `vimt` command.
